---
layout: post
title: "Gmail problems in different server pools"
date: 2005-10-28 12:19
comments: true
categories: Computers
author: Oliver Thylmann
---


&lt;p&gt;
Greetings everyone. On and off I seem to be having problems with my POP access to Gmail and I now seem to have found the reason for all of this, just if some others also have the problem. The problem itself is that the pop request just times out. The problem seems to be with Google or something on the route to some of the server pools. 
&lt;/p&gt;&lt;p&gt;
It was working fine and I ran a traceroute to pop.gmail.com and ended up going over:
&lt;/p&gt;&lt;p&gt;
&lt;i&gt;11  po13-0.chicr2.chicago.opentransit.net (193.251.240.137)  154.259 ms * *
&lt;br /&gt;12  66.249.95.253 (66.249.95.253)  158.005 ms  158.562 ms *
&lt;br /&gt;[...]
&lt;br /&gt;15  64.233.175.97 (64.233.175.97)  244.343 ms  239.228 ms  243.426 ms
&lt;br /&gt;[...]
&lt;br /&gt;17  72.14.205.109 (72.14.205.109)  240.442 ms 72.14.236.142 (72.14.236.142)  251.769 ms 66.249.94.73 (66.249.94.73)  237.330 ms&lt;/i&gt;
&lt;/p&gt;&lt;p&gt;
It worked just fine. I seem to be somewhere in Chicago there. 
&lt;/p&gt;&lt;p&gt;
Next it stops working again and where am I? 
&lt;/p&gt;&lt;p&gt;
&lt;i&gt; 7  br1.frankfurt1.iphh.net (80.231.66.38)  56.323 ms  56.652 ms  56.785 ms
&lt;br /&gt; 8  216.239.46.48 (216.239.46.48)  66.315 ms  57.540 ms  56.848 ms
&lt;br /&gt; 9  64.233.175.248 (64.233.175.248)  63.733 ms  63.763 ms  64.019 ms
&lt;br /&gt;10  216.239.43.84 (216.239.43.84)  66.259 ms  75.122 ms 216.239.43.89 (216.239.43.89)  64.718 ms
&lt;br /&gt;11  216.239.43.88 (216.239.43.88)  64.565 ms  64.047 ms  63.464 ms
&lt;br /&gt;12  216.239.43.84 (216.239.43.84)  66.127 ms  67.032 ms 64.233.175.246 (64.233.175.246)  66.150 ms
&lt;br /&gt;13  216.239.43.42 (216.239.43.42)  67.479 ms 72.14.236.150 (72.14.236.150)  78.471 ms 216.239.43.34 (216.239.43.34)  79.919 ms
&lt;br /&gt;14  64.233.183.109 (64.233.183.109)  67.929 ms  66.769 ms 216.239.43.30 (216.239.43.30)  72.721 ms
&lt;br /&gt;&lt;/i&gt;
&lt;/p&gt;&lt;p&gt;
The hop back and forth seems a bit weird there. At the next try when it is not working I am in Frankfurt again.
&lt;/p&gt;&lt;p&gt;
&lt;i&gt;
&lt;br /&gt;7  br1.frankfurt1.iphh.net (80.231.66.38)  56.530 ms  58.030 ms  56.345 ms
&lt;br /&gt; 8  216.239.46.48 (216.239.46.48)  57.547 ms  57.390 ms  56.825 ms
&lt;br /&gt; 9  64.233.175.248 (64.233.175.248)  63.578 ms  64.133 ms  63.929 ms
&lt;br /&gt;10  216.239.43.80 (216.239.43.80)  79.355 ms  67.291 ms 216.239.43.89 (216.239.43.89)  63.445 ms
&lt;br /&gt;11  216.239.43.88 (216.239.43.88)  63.757 ms  83.265 ms  63.496 ms
&lt;br /&gt;12  64.233.175.246 (64.233.175.246)  66.718 ms  70.648 ms  66.321 ms
&lt;br /&gt;13  216.239.43.26 (216.239.43.26)  68.140 ms 216.239.43.30 (216.239.43.30)  66.530 ms 72.14.236.146 (72.14.236.146)  66.717 ms
&lt;br /&gt;14  216.239.43.30 (216.239.43.30)  66.663 ms 72.14.236.146 (72.14.236.146)  66.918 ms 64.233.183.109 (64.233.183.109)  66.586 ms
&lt;br /&gt;&lt;/i&gt;
&lt;/p&gt;&lt;p&gt;
If anyone from Google is listening, please look into it, and I am always happy to provide more answers to any questions. The problems are both on a Mac with Mail and on an XP machine with Outlook.
&lt;/p&gt;&lt;p&gt;
Greetings from Germany, where I wish I get my mail from Chicago again. ;)
&lt;/p&gt;

