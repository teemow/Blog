---
layout: post
title: "Amazon S3 Pricing Changes"
date: 2007-05-04 13:32
comments: true
categories: Web 2.0
author: Oliver Thylmann
---







&lt;p&gt;Damn they are good! [Amazon](http://amazon.com) has done a pricing upgrade to their [S3 System](http://www.amazon.com/gp/browse.html?node=16427261). The new prices are effective for June 1st of this year and they probably found out how some people use S3. I have been raving about the system for some time already and so it is no wonder that we are using it at [Ormigo](https://ormigo.com).&lt;/p&gt;

&lt;p&gt;As we are running large advertising campaigns around products that are interesting for local service providers, we need our ads solution to be both flexible and very scalable. Running ads on big portals means that your system needs to work. Previously I had worked together with [Akamai](http://akamai.com/), whom I still like very much, but they are rather expensive and some hits still come down to your servers. Above that it only really works well if you have a relatively high caching time.&lt;/p&gt;

&lt;p&gt;Amazon S3 is a very cool middle thing in that it allows us to upload our ads to their system and not have any impact on our servers. Through the API we can automatically update the ads whenever we want. Additional flexibility will come when we lean more on EC2 as additional help, but we will see how this goes. For now I am very happy with what we have as a first step. And sure, S3 can go down, but you know what... so can our servers. At this time I am reasonably sure that S3 has more resources available to keep the servers up than we do. :)&lt;/p&gt;

&lt;p&gt;How does the pricing change effect us though. Simple. Above the bandwidth charges they are adding per request charges, which is a logical thing. For us this will possibly add up to a bit more costs as ads are relatively small and mostly text based. Bandwidth prices for uploads are cut in half, and bandwidth prices for download are decreased a little bit dependent on volume you take.&lt;/p&gt;

&lt;p&gt;Above that PUT and LIST requests will be $0.01 CPM and GET requests are $0.001 CPM. That is really ok I have to say and I actually like the system, which makes it more transparent and easier for Amazon to calculate profitably. Looking forward to seeing the next bill.&lt;/p&gt;


