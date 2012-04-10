---
layout: post
title: "OpenAds getting $15.5 Million and other Ad Stuff"
date: 2008-01-17 06:49
comments: true
categories: Advertising
author: Oliver Thylmann
---







Congratulations to [OpenAds](http://openads.org)! I [included OpenAds in two recent posts](http://blog.thylmann.net/tag/openads/) and now they are getting more money to really develop their vision further. With their [announcement of a hosted service](http://blog.openads.org/01/hosted-version-of-openads/) I think they might be further along to bringing real [change to the advertising market](http://blog.thylmann.net/2007/07/03/we-need-a-small-little-change-to-banner-serving/) in general, even though that might not be their initial focus. The market is big enough as it is. One thing they really bring to the plate is that they are a real alternative for big publishers as a banner server now. With a $15 million investment, they have the money behind them to explain to a big publisher that they are not going away and especially the big ones don't want WPP, Microsoft or Google running all of their ads.

As [Saul Klein puts it](http://localglobe.blogspot.com/2008/01/big-day-for-open-source.html), OpenAds, the server, already serves billions of ad impressions (I'll add &quot;a day&quot; to that quote) and with the hosted version, access to OpenAds will even get easier.  I hope they do have a good idea on how they will handle the infrastructure, especially for statistics delivery. :)

I have been running OpenAds here on the blog from time to time, and have introduced it in different places where something more banner server like was needed, in relation to the stuff I have built in the last few years (being more AdSense like Systems, which add the complexity of ads within ads). OpenAds is really powerful and is getting better with each release, meaning that if you are running ads on your site, I'd look into it.

I started testing the German AdScale some time ago, and sadly they do not filter out non-German traffic. So if I run their system on my blog as default, 90% of the ads served make no sense whatsoever. That is where OpenAds is an easy solution and where a hosted version would be even better, because setting up OpenAds on my Server is actually a bit overkill for my little bit of geotargeting. At the moment AdScale is off again while I set up OpenAds (or get access to the hosted version due to this post ;)) and then I will probably benchmark it against our system at [Ormigo](https://ormigo.com/) (which we haven't opened up yet, doing specific deals with specific publishers at the moment). I might try out Proximic, which surely has an interesting system (they are using the [Vector Space Model](http://en.wikipedia.org/wiki/Vector_space_mode) for content match, possibly a learning system ala [Support Vector Machines](http://en.wikipedia.org/wiki/Support_vector_machine), which would be a lot nicer). The problem I see with Proximic, is that they announced [having secured access to eBay's Shopping.com and Yahoo! Shopping's product listing](http://www.techcrunch.com/2008/01/15/proximic-signs-deals-with-yahoo-and-ebay-to-turn-product-listings-into-contextual-ads-taking-on-adsense/), among others. That means that they have access to a lot of potential &quot;ads&quot;. The problem is that they don't really pay. Google isn't so good because it does content match, but because it has high prices. Sure, content match is nice, but YPN made more money for publishers when they optimized for revenue without content match as far as I know (this was in the private beta phase). Google does the content match for traffic quality. What CPC might you get for a book buy. A presume a few cents. I just searched for a few books on google and the only one that gives an ad is &quot;The Innovator's Dilemma&quot; ... for Clayton                              Christensen's consulting company (he wrote the book ;)). So I would even presume that if 3 cents minimum bid would be possibly earned in these searches, somebody would bid on them. I do see a lot of power in their matching technology though, but I do know that there are other players out there that do content match (even matching the content to keywords you give them). All the power to a startup from Germany that has somehow gotten international attention though!

I know of a trial by one of the big affiliate system to get us out of a publisher deal and their performance was well below ours (previous company). This stuff is very complicated, with strategy (if it exists), options, brand and performance being just a few of the influencing factors on the publisher side.

Sorry that this turned out to be a bit of a rant ... but the Ad market _is_ interesting. And bringing the local ad market really online is even more fun :)

Update: OpenAds running again on blog (via old server, problems with lighttpd here it seems, don't have invocation codes or banner types selectable and preference settings don't save for those). Hence AdScale enabled for a second time, now with more ads, and hopefully limited to Germany. If you are in the US and see AdScale Ads ... tell me :)


