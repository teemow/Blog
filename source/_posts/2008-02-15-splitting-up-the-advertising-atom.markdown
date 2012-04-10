---
layout: post
title: "Splitting up the Advertising Atom"
date: 2008-02-15 10:05
comments: true
categories: Advertising
author: Oliver Thylmann
---








I [wrote about the ad market needing a change](http://blog.thylmann.net/2007/07/03/we-need-a-small-little-change-to-banner-serving/) in July of last year, and now Emre Sokullu explained the idea very well in his post entitled [Plan B for Microsoft: Split up the Advertising Atom](http://www.readwriteweb.com/archives/plan_b_for_microsoft_split_up_the_advertising_atom.php).

He take the Microhoo deal as a starting point, thinking about how Microsoft can beat Google, but it's not really something that is unique to Microhoo. The suggestion he has is something that is bigger than Google, bigger than any advertising system out there. Think VISA for advertising.

His idea is best explained via the picture below from his post:

&lt;img src=&quot;http://www.readwriteweb.com/images/openad-model.jpg&quot; height=&quot;427&quot; width=&quot;543&quot; /&gt;

The idea is that you split everything up, and create it around a standard so that the different silos can interact. The cool thing is that this is how our AdServer at [Ormigo](https://ormigo.com/) is structured, first because it makes for an amazingly efficient ad server that runs on Amazon's Web Services Infrastructure, and it provides for some interesting new possibilities.

Our products that we advertise are within different objects stored on S3 (inventory silo) and the Placement Silo is really our AdServer that holds all the information about the Placements. The very cool thing about the above model is that you can have different inventories fill the same placement, or add on top of that different parameter silos that take care of optimization. Thing content match or behavioural targeting.

The cool thing is that you would enable [Open Innovation](http://en.wikipedia.org/wiki/Open_innovation). Of course there are lots of things still to be thought out to make it really open, meaning you make it a VISA model in which everybody can use everything and can do what they want with it but they will need to adhere to a set of rules and standards. This might make prices more transparent, and open up for real competition, which will not be good for everyone. But the thing is that it enables is a really open market place where different people can write a Placement Silo for TV ads that suddenly grab the right Ads from the Inventory Silo, optimized through a Facebook Parameter Silo to only show ads my Friends like. Who gets what? Who pays what? What about the wining and dining part of advertising? Lots of things not settled, but worth thinking about.

