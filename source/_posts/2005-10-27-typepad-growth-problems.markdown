---
layout: post
title: "TypePad Growth Problems"
date: 2005-10-27 06:43
comments: true
categories: Computers
author: Oliver Thylmann
---


Mena and Ben have posted a note on the recent TypePad performance problems entitled &lt;a title=&quot; Six Apart - Mena's Corner: The Ups &amp; Downs of a Successful Service&quot; href=&quot;http://www.sixapart.com/about/corner/2005/10/the_ups_downs_o.html&quot;&gt;The Ups &amp; Downs of a Successful Service&lt;/a&gt;. I can fully relate to how hard it is to get a system to be really scalable and get the power you need. It's not easy to run a fast growing web site and when running the IT side of one of the biggest performance based advertising networks in Germany (now [Ligatus](http://www.ligatus.de/) part of [OnVista Group](http://www.onvista-group.de/)) I was fortunate enough to have an existing infrastructure to base everything on as OnVista was already running [onvista.de](http://onvista.de), the biggest bank indepedent financial portal in Germany.

Looking for a hosting facility is a fun business, especially if you need it scalable and if you then start thinking about the immense power that Blade Servers need you start to sweat. IBM for example will only allow you to put stuff into their racks or racks that pull in cold air in the front and push it back out through the back of the racks. Some hosting centers push air into the racks from below the floor and pull it back out at the top but the fans, or rather turbines that are in the blade centers pull from the front and push out in the back and as they are so big, the airflow could get problematic if it needs to be diverted to the top. You also need A LOT of power. A fully equipped blade center needs at least 2 lines of 16A power, but for failover, you need 4. Now if you put 3 blade centers in one rack, you kind of need 8 lines of power (sharing two between two centers) and that's already well above the standard setting that man centers provide.

As recently posted by Cringely the climate control systems need 3 times the power than a rack pulls in, so you kind of need 8 + 24 lines of power (ok, not really, but still a lot) and if the blade center boots up, it sucks all the power it can get. It actually sounds like an airplane starting. Very funny.

At the 240mbps that Ben quotes, and presuming you pull 5mbps on each server, you need 48 servers already. That's without factoring in that you need failovers and database servers in the backend, and load balancing and and and.

I was fortunate enough to be able to offload a huge deal of the traffic to [Akamai](http://www.akamai.com/), as the ads can be cached, pulling load and traffic of the backend and making the entire system immensely scalable in terms of advertisements delivered.

So people of TypePad, I feel with you. Your task is a lot bigger than mine was. Hang in there, better times will come. I for one will stay loyal.

