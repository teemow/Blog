---
layout: post
title: "The Hubbub about PubSubHubbub"
date: 2009-08-12 19:42
comments: true
categories: Web 2.0
author: Oliver Thylmann
---






Ok, you have to love the name. [Pubsubhubbub](http://code.google.com/p/pubsubhubbub/) is simply the best name for a technology for ages, period. And it is currently pitted as the better step towards a [Google Wave](http://wave.google.com/) like future than Google Wave itself.

So what is PubSubHubbub:


  A simple, open, server-to-server web-hook-based pubsub (publish/subscribe) protocol as an extension to Atom (and RSS).


In longer terms, it is part of a system that removes the need for Google Reader to query my RSS feed every few hours to see if there is something new, instead allowing for Google Reader to be notified when something changes. The argument is that it gives us the live web and it decreases resource need. For a better into check out [This Week in Google Episode 2](http://twit.tv/twig2).

I really like it and so does Anil Dash as visible in his post [The Web Way vs. The Wave Way](http://dashes.com/anil/2009/08/what-works-the-web-way-vs-the-wave-way.html).

There is just one thing that makes me wonder. I remember a long time ago when MovableType was it, with everyone arguing that it was better to have the blogging platform publish static HTML files when you published a blog post as you are publishing so few of them in relation to the traffic that the resources are better spent there. But servers got more powerful and Wordpress changed this around to say that you want easy and fast publishing, the possibility to change your design around, the switch things, which makes it better to have the publishing be dynamic. This is what I see again here. We had centralized systems and only a few of them but slowly we are getting more and we want to move around. This changes how the content should be put together. We have friends all over the place and hence on request we do not want them to come from one source but from several, which is starting to become possible due to server power and general infrastructure items like Pubsubhubbub. It's push due to the underlying changes in how we interact with each other and what we say is important.

We somehow want near-real-time communications. The problem I see though with Pubsubhubbub is how the technology scales if you have for example 1 million friends on twitter. With a centralized system this is relatively easy. If each of your posts needs to be published to 300.000 hubs, this starts to become a pain. But with a polling mechanism it would not be live. How much resources are we will to spend for live, and who will pay the bill?


