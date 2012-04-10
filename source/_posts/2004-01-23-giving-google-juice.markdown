---
layout: post
title: "Giving Google Juice"
date: 2004-01-23 06:07
comments: true
categories: Business
author: Oliver Thylmann
---


Yesterday I added &lt;a&gt;furl to the services I use and I will be doing so a lot starting now. I just need to get used to not pressing bookmark, but furl, and not sending eMails to work with links I want to look at there but to furl it. It's a great service, check it out.

The nice thing is that you can also add your latest entries from Furl to your own website, at the time via JavaScript. I am already including my People feeds from [Bloglines](http://www.bloglines.com/), another great service by the way, via JavaScript. There is one bad thing with this JavaScript integration though. Bots can't follow the link because they simply ignore JavaScript. So I wondered if I cannot simply include them in PHP and started looking for a URL that I could include that didn't return JavaScript code with it. Nothing to be found, on either of the services. So yesterday evening I mailed both Furl and Bloglines with the question of providing none JavaScript feeds. 

Furler numero 1 Mike answered first in that they do provide an RSS Feed or if I needed something else, and I had to admit that I was playing it a bit lazy there, as I could have integrated that. I replied that I can do that, but that I was just being lazy (you have to honest :)) and simply wanted to include plain HTML. A few hours later, back comes a link that works perfectly! Now I include [my 10 latest furls](http://www.furl.net/htLatest.jsp?id=368&amp;count=10) in PHP just fine.

Then I wake up and I have a mail from Bloglines founder [Mark Fletcher](http://www.wingedpig.com/) say nothing more than thanking me f or the suggestion and that they will have a HTML version soon. &quot;*;-)*&quot;. Just 30 minutes later I get an eMail that they just rolled it out. If you go to the help page on [sharing your Bloglines subscriptions](http://www.bloglines.com/help/share/) you get walked through to a page that will then give you a JavaScript version and it now says:

*If you use PHP or another method to include raw HTML into your blog, use the following URL instead, which returns the blogroll as HTML. 

http://rpc.bloglines.com/blogroll?html=1&amp;id=biz&amp;folder=People&amp;target=_blank*

Now how cool is that?That line might even be put there for me, as it fits to my question, but emm... I doubt that. :) Both services responded by implementing it and they did it amazingly fast. Thank you Bloglines and thank your Furl for the great service!


