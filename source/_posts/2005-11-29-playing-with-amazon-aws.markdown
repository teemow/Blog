---
layout: post
title: "Playing with Amazon AWS"
date: 2005-11-29 11:19
comments: true
categories: Advertising
author: Oliver Thylmann
---







I have been playing a bit with [Yahoo! Shoposphere](http://shopping.yahoo.com/shoposphere/) which I [posted about](http://blog.thylmann.net/2005/11/yahoo_shoposphe.html) recently. I really like the concept, but sadly there is no revenue share yet and no way to attach my contact data to my shopping list. It's also actually geared to putting things in there that are already in your hands, that you tested. But I wanted to look at using something like that in relation to AdSense.

AdSense allows you to add a default ad that would be shown instead of the public service announcements that come there if Google does not find anything to link to your site. But what to add? There are some services that tailor to this system but I always felt you would have to do something that is very personal to yourself. Enter Amazon's Wishlist and the Amazon WebService, [AWS](http://www.amazon.com/gp/aws/landing.html) in short.

There you can register and get your developer ID and actually build a nice REST query that will give you back your Wishlist. It currently only seems to do that for a US wishlist but who cares. I set one up and the query is easy to set up, especially with the help of [AWS Zone](http://www.awszone.com/).

Here is my query:

&lt;code&gt; &lt;/code&gt;
http://xml-us.amznxslt.com/onca/xml?Service=AWSECommerceService
&amp;Version=2005-03-23
&amp;Operation=ListLookup
&amp;Style=http%3A%2F%2Fthylmann.net%2Fmy-wishlist%2Famazon.xslt
&amp;ContentType=text%2Fhtml
&amp;SubscriptionId=hidden
&amp;ListId=UOV88WC3Q1WF
&amp;ListType=WishList
&amp;Condition=All
&amp;DeliveryMethod=Ship
&amp;ResponseGroup=Images%2CSmall
&amp;Sort=LastUpdated
That gives me a lookup of a specific wishlist, returning text/html, including images and a description, ordered by last updated. It would be nice to be ordering by rating but that did not seem to be there.

You see one interesting item in there, which is *Style*. There another URL can be found:

*http://thylmann.net/my-wishlist/amazon.xslt*

This is a relatively simple XSLT file that turn the output I get into anything I want, server side, by AWS. Very handy indeed. These together already give me a small box in the standard size of an AdSense ad, configurable in design, with the 4 items I have in my Wishlist over there.

Next comes PHP, which mangles what comes out of there a bit, because what I really need is an output in kind of Javascript. One thing that is important is that the output HTML needs to be all in one line, without ' or it will not return anything.

&lt;code&gt; &lt;/code&gt;
? print &quot;document.write('&quot;;
$string = fopen(&quot;the above url&quot;, &quot;r&quot;);
// now I replace both linebreaks and '
while (!feof($string)) {
$buffer = fgets($string, 4096);
$say = ereg_replace(&quot;n&quot;,&quot;&quot;,$buffer);
$say2 = ereg_replace(&quot;'&quot;,&quot; &quot;,$say);
echo $say2;
}
fclose($string);
print &quot;');&quot;;
?
What does that give me? It produces the following output, which I can theoretically add as my default AdSense ad, built from my Wishlist, configurable in CSS, and with the stuff automatically going to the right address if somebody chooses to send them around. :)

Comment: The Sigma Lense and Lowepro is already communicated to other people, so I am very sorry for my readers that they will only be able to give me the other two items if they are so inclined ;)







