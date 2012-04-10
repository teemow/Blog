---
layout: post
title: "Hashcash installed to counter spam"
date: 2006-12-20 10:17
comments: true
categories: Blogging
author: Oliver Thylmann
---






Akismet currently holds 34000 comment spams and several thousand are added each day, partly moving the server up to loads far over 50 and making everything unresponsive. Hence, I needed another solution and found [Hashcash](http://elliottback.com/wp/archives/2005/10/23/wordpress-hashcash-30-beta/), a wordpress plugin that arguably works better than Captcha. So what does it do? Here is what they say on the site:
&lt;em&gt;Every four hours, your blog picks a random large number (close to 32 bits). Whenever a visitor visits your permalink pages, an ajax call is made which retrieves some javascript. This javascript first decrypts itself, then executes itself again to retrieve the secret value, which it sets in the form. If a comment does not have this value, it is rejected. If a comment is rejected more than four times, the user is blocked for a specified period of time.&lt;/em&gt;

Sounds good and I hope it will work. Let's see what happens. As long as I am not at 3000 comment spams a day, I am happy.


