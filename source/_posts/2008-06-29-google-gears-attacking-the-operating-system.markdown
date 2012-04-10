---
layout: post
title: "Google Gears attacking the Operating System"
date: 2008-06-29 07:32
comments: true
categories: Web 2.0
author: Oliver Thylmann
---








This is really as far as it goes. Google [Gears](http://gears.google.com), or now Gears, as it [de-branded](http://alex.dojotoolkit.org/?p=677), makes your browser in conjunction with a web site, into an offline application, or simply an application with local components. Because it started out by simply giving your offline access to GMail or Google Reader, and now the folks behind Wordpress have announced that [Wordpress 2.6 will have Gears integrated to speed up](http://almaer.com/blog/speed-up-with-wordpress-and-gears) the Admin Interface. Matt actually adds a few points [here](http://ma.tt/2008/05/infrastructure-as-competitive-advantage/), among others linking to the [Performance Page](http://developer.yahoo.com/performance/) on the Yahoo! Developer Network saying that something like 85% of the performance is in the frontend, meaning it is felt performance. This brings him on to Google Gears and how local servers will make CDNs obsolete.

While I do believe that there is a lot of power in Google Gears, I am not seeing yet where they will make CDNs obsolete. There is lots of stuff I do not cache or cannot cache in the browser. Above that, I know of at least one person that will scream up when you mention something like Google Gears or AIR. The thing is that these are systems that give Web Apps very deep access into your system and we just don't have the mindset yet to really secure web applications. A simple link sent to you, might result in something loading in some un-secure AIR or Gears app and destroy your computer. This is a risk we have to deal with somehow, but I am pretty sure that is on the mind of the Google engineers and the others that are working on Gears.

I do fully believe Matt though that the line between servers and application is shifting in that you will less and less worry about your server infrastructure. I had a longer talk about this with the CEO from [Globalways](http://globalways.net), who are running a Xen virtualisation Platform.

But back to Gears, Techcrunch has [a lot more interesting points](http://www.techcrunch.com/2008/06/13/google-drives-towards-microsoft-and-adobe-with-gears/), e.g. that [Gears was implemented by MySpace for their messsaging](http://www.techcrunch.com/2008/05/28/myspace-shows-facebook-how-its-done-google-gears-to-power-messaging/).
Today Gears supports a whole host of new features, some that it has in common with the other next generation web API efforts from Microsoft and Adobe while others are a result of their own innovation. Function calls [available to developers](http://code.google.com/p/gears/w/list) include background processes (no more hourglass), client-side image manipulation, location-awareness, better file uploading and a local database inside the browser.
It's really getting interesting here in that you might want to give your users the option to simply download Gears and use it and suddenly can write a lot more powerful web applications, with less servers. Looking forward to trying out the new Wordpress to see how it works with Gears.

