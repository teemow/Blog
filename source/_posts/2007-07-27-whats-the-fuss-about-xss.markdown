---
layout: post
title: "What's the fuss about XSS"
date: 2007-07-27 15:47
comments: true
categories: Web 2.0
author: Oliver Thylmann
---







XSS stands for cross site scripting. Another interesting acronym is Cross-site request forgery (CSRF). All in all, what most of you should think about is that for web sites that are written without security in mind, or that simply have a bug, you can possibly infiltrate code of your own as an outsider. A good example of this would be the [MySpace Worm](http://namb.la/popular/tech.html) which enabled the creator to have somebody who visited his MySpace profile, automatically add him as a friend. Additionally, that person automatically added his little code to their profile, automatically making all people that visited that persons profile the authors friend again.

So let's see how long it took him to get a few friends. He included a little bit of code on his profile when he had 73 friends, an hour later somebody looked at his profile (1 more friend, bit more code on that persons page), 7 hours later he had 221 friend requests, one hour later  480, then another (he since accepted the 480 ;)) 561 another hour later, ... 3 hours later 2503 friends and 6373 request; 5 hours later 2503 friends, 917084 requests, a few minutes later over a million friend requests.

Now that's really fun. I mean nobody was hurt. But what follows next can be just a small little addition to that little worm, or an add you see, or a forum posting, or an article, ... .

As seen in this article that has just been published, entitled [U R Insecure - how URl exploits are changing the webappsec landscape](http://www.gnucitizen.org/blog/u-r-insecure-how-uri-exploits-are-changing-the-webappsec-landscape), you can at this time on firefox, or ie, or any other browser really as long as it is on windows, infect the file system. What does that mean again? It means that provided I have somehow been able to inject code on a web site you are visiting, I can open a command prompt on your machine without you noticing, download a small application, install it, and then can do virtually anything to you. What could that be?


    * I delete all contents of your hard drive (actually don't need the app for that)
    * I turn of your computer
    * I scan all network drives for a file with &quot;financial&quot;, &quot;next&quot;, &quot;quarter&quot;, &quot;confidential&quot; or something mixing those (of course then sending me those files)


Just to connect this again to the MySpace Worms. Within a few hours I'd have turned off a million PCs, or scanned them for confidential material. You will by now come up with your own ideas. The thing is that the door is wide open because a system in browsers allows you to open another application. There might be a joost:// prefix on your machine and Joost might be insecure (not saying it is!) and I embed a link that will open joost://something that will again give me access to the file system.

This is not posted to make anyone afraid, but it should alert us all that this Web 2.0 idea, and all the JavaScript usage, doesn't make things easier. We can't just bang out an Alpha release of something without some idea of security. This is possibly getting dangerous and we need to be aware. With suddenly being able to get online apps offline the problem will only be bigger. We can write great apps that run in a browser and I am looking forward to more cool things coming there, but keep in mind that it's not all as simple as it sounds. Imagine this working on the iPhone (I am not aware that it is). I'll just call a few numbers and you are broke and I am rich.


