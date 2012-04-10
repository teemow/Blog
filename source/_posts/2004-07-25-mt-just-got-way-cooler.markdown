---
layout: post
title: "MT just got way cooler"
date: 2004-07-25 08:33
comments: true
categories: Blogging
author: Oliver Thylmann
---


This is a [very nice post on TypePost](http://www.typeblog.de/archiv/2004/07/movable_type_31.html) (German), giving some details on MovableType 3.1. The most interesting, beyond sub-categories, which is very nice, is that it will have a DynamicEngine, meaning that you can decide to not rebuild the site but have it be rendered live. Very cool indeed that is. On top of that, you can just include PHP modules, which is something I already did in my previous installation though. You can just make MT publish PHP code without a problem. What is likely improved is the potential to get some extra hooks into your PHP code that makes it interact with the MT installation. Very nice indeed. Possibly a result from [the Wordpress - Six Apart meetup](http://www.loiclemeur.com/english/2004/06/mt_and_wordpres.html), but that's full speculation on my part. :)

&lt;b&gt;Update&lt;/b&gt;: Nice additional info from [Scot's post about it](http://birdhouse.org/blog/archives/001380.php) from no one else than [Anil Dash](http://www.anildash.com/):

&lt;I&gt;We'll be explaining more on this soon, but the PHP integration in MT3.1 makes use of Smarty, so the caching of dynamic templates is pretty smart.&lt;/I&gt;

This came as a reply to a question by [Erwin](http://www.transpontine.com/blog/) about only scanning templates for PHP code once and then not doing this until they are changed again. This is really what Smarty does so Anil's comment does make some sense.


