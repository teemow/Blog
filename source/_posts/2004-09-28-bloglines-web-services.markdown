---
layout: post
title: "Bloglines Web Services"
date: 2004-09-28 07:09
comments: true
categories: Blogging
author: Oliver Thylmann
---


Mark Fletcher just [posted about Bloglines Web Services](http://www.wingedpig.com/archives/000178.html), a new system from Bloglines which will be fully announced with a [press release](http://www.bloglines.com/about/pr_09282004) tomorrow, but Mark could not hold out and wait any longer, so there goes the announcement and it's something that will likely help remove a problem with RSS that some have started to see. 

The problem comes from the fact that RSS Readers will query a feed several times a day and can potentially create huge Bandwidth need on the side of the publisher. [Bloglines Web Services](http://www.bloglines.com/services/) help soften that problem because they will offer feeds directly through a RESTful API. Through the API Bloglines acts as a RSS cache and also helps feedreaders to only query well-formed RSS 2.0 or OPML. The coolest bit though is why I really use Bloglines. It allows me to read my feeds whereever I am and only have unread feeds, independent on where I read the other ones, on the next computer. Through the API, desktop readers can now sync via several computers!  Congratulations on the move Mark and congratulations to the entire team! On to downloading [Feeddemon](http://www.feeddemon.com/) to try this out :)

&lt;b&gt;Update&lt;/b&gt;: In Feeddemon you simply subscribe to http://rpc.bloglines.com/listsubs , then enter your username and password and you are good to go. It doesn't seem to sync with my online subscription just yet, but I might not have the beta version that Mark talks about.

&lt;b&gt;Update 2&lt;/b&gt;: Feeddemon seems to ignore the categories that Bloglines sends over. These should become channels.


