---
layout: post
title: "PayPal Phishing"
date: 2004-11-30 11:44
comments: true
categories: Computers
author: Oliver Thylmann
---


&lt;p&gt;Ok, I have been caught in a phishing attempt. Not that I used a wrong url to give my password or anything but I simply didn't get it. This one was a mail seemingly from PayPal and it didn't have any links to none PayPal sites in it. The thing is that it didn't have a clickable link either, so there couldn't be a hidden &lt;em&gt;a href&lt;/em&gt; there somewhere, or so I thought. But let's start with the eMail. This is what I received:&lt;/p&gt;

&lt;p&gt;[&lt;img width=&quot;200&quot; height=&quot;301&quot; border=&quot;0&quot; src=&quot;http://owt.typepad.com/blog/images/mail.jpg&quot; alt=&quot;Mail&quot; /&gt;](http://owt.typepad.com/photos/uncategorized/mail.jpg)&lt;/p&gt;

&lt;p&gt;As you might notice it does seem quite reasonable even though it says nowhere why I did do something wrong with my account. As the url was not clickable I didn't think about it much. I later looked at the source after not finding anything wrong with the account in question and here is what I found: &lt;/p&gt;

&lt;pre&gt;&lt;P align=left&gt;&lt;br /&gt;[ value=&quot;New Window!&quot;&lt;br /&gt; onClick&lt;br /&gt;&amp;nbsp; =&quot;window.open('http://cddvdmp3.50megs.com/cgi/index.html',&lt;br /&gt; 'window_name', 'window_options'); return false&quot;&amp;nbsp; &amp;nbsp;&lt;br /&gt;&amp;nbsp; &amp;nbsp;&amp;nbsp; &gt;&amp;nbsp; &lt;br /&gt;&amp;nbsp; https://www.paypal.com/cgi-bin/webscr?cmd=_login-run &lt;br /&gt;&amp;nbsp; ](http://cddvdmp3.50megs.com/cgi/index.html )[ target=_self&gt;](http://cddvdmp3.50megs.com/cgi/index.html)&lt;/P&gt;&lt;br /&gt;&lt;P&gt;&amp;nbsp;&lt;/P&gt;&lt;/pre&gt;

&lt;p&gt;Aha... there are some fake thingies around the URL but it might be that they are just exploiting some problem in Outlook or something because it didn't turn up anything in GMail. I have to admit though that I have been caught.&lt;br /&gt;
&lt;/p&gt;

