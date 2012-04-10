---
layout: post
title: "Moved Server to x|encon pro series"
date: 2007-10-06 16:05
comments: true
categories: Computers
author: Oliver Thylmann
---






The [Hetzner](http://hetzner.de/) Server I had up till now, also hosting the [Ormigo Blog](http://blog.ormigo.com/blog/) and a few other things, was starting to be a bit expensive for the little work it did. I had their entry level dedicated server with 1GB Ram, two 160GB Disks, and theoretically unlimited bandwidth, for 49 EURs. It's a great price if you need it.

Then [Timo](http://teemow.com/) pointed me to [x|encon](http://xencon.net) who are providing Xen based Virtual Servers. We have been running avirtualized infrastructure at Ormigo for some time, and I am currently looking into Xen based hosting systems ([Globalways.net](http://www.globalways.net/) is a very good candidate). While x|encon does not really feature the high end systems we need, it did seem like a perfect match for what I was looking for. I actually started out with their smallest x|entry server with 48 MB of RAM but had to find out that with my limited time and unix skills, I didn't managed to get both my Noserub and Blog installed on the server at the same time. It would just move up to load 6 and die on me, even though I opted for a very small mysql config and lighttpd running on a minimal debian install.

Because I want my stuff up and running, and I don't have time to waste fully getting a tiny installation running with php5 and all, I now changed over to the smallest x|pro with 256MB ram, 2 CPUs, more storage and so on. At 19,99 EURs it is still not too expensive really and it has some nice benefits.

First of all, x|encon support rocks! They have been very forthcoming with my many requests for changes and questions. There were some hickups along the way, but that was me wanting to have the server now and they having a process of putting hosts online for your to work with via SSH but with limited connectivity before your bank account is cleared. The other thing that happened is that I did a hard reset of the server on a german holiday when they were moving the management interface. Ah well. I was a stressful customer.

What is very cool is the management interface itself. I can set bandwidth limits for the server, firewall rules, make a snapshot of the current system, reinitialize with a new OS, start and stop the server, boot it in the rescue system, have an internal network (and could take the server of the internet alltogether as a backend database server for example), ... and I can connect to the console directly seeing my server boot. The upgrade process to the new server worked wonderfully, having 30 minutes of downtime because the higher resources ment that my &quot;server&quot; needed to be moved to a new machine. When it was back up, I just need a short break in rescue mode to scale the hard disk up to the new level and up I was, with the same installation, all my added packages, all my files, everything, ... just more ram, cpu, harddisk, bandwidth, ... very nice indeed.

This is really what I like about the virtualized infrastructure bit. You get very scalable, especially if you are willing to spend a bit more money than I did now.

Looking forward to playing a bit more with this stuff and I might actually have 6 servers at x|encon some time, doing different tasks, on and off the internet. Cool. :)


