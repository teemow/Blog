---
layout: post
title: "&quot;You Don't Know Jack About VoIP&quot;"
date: 2004-09-24 12:02
comments: true
categories: Computers
author: Oliver Thylmann
---


That's the title: &lt;a title=&quot;ACM Queue - You Don't Know Jack About VoIP - The Communications they are a-changin'.&quot; href=&quot;http://www.acmqueue.com/modules.php?name=Content&amp;pa=showpage&amp;pid=203&quot;&gt;ACM Queue - You Don't Know Jack About VoIP - The Communications they are a-changin'.

And it's a very good article I have to admit. It gives a great explanation of ENUM for example: 

*ENUM. The best-understood and most widely deployed name resolution system today is the DNS (domain name system). In the DNS, names are written from right to left, with the most general part of the address on the right, and more specific names written to the left (e.g., www.ietf.org). In the PSTN, telephone numbers are written from left to right, with the most general part of the number written on the left and the more specific toward the right (e.g., 1.212.543.6789). ENUM calls for telephone numbers to be written DNS-style, rooted at the domain e164.arpa. So, 1.212.543.6789 becomes 9.8.7.6.3.4.5.2.1.2.1.e164.arpa. Interestingly, each digit is treated as a subdomain. This allows ENUM to ignore the nuances of country codes, city codes, etc. that vary broadly worldwide. When this address is queried, the DNS can return a specific IP address corresponding to the telephone number, or it can return a rule for rewriting the original number into some other form. For example, rules can be returned to rewrite 1.212.543.6789 as sip:36789@nyc-gw.example.net, sip:caryfitz@service-provider.com. ENUM offers the possibility to reuse the worldwide DNS for VoIP. ENUM is a standard set by the IETF as RFC3761.*

The cool thing about this is that you can publish your phone number, manage where you are at, and when an ENUM capable device calls, then it is directly routed to the right phone. Add location based services to that, and you might get some cool stuff. :)

In Germany you can go to [Portunity](http://www.portunity.net/enum) and order for free (currently) a place for your phone forwarding. You can then check up on your ENUM entry at [enum-center.de](http://www.enum-center.de/).


