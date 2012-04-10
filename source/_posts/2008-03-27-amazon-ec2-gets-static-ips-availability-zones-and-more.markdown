---
layout: post
title: "Amazon EC2 gets Static IPs, Availability Zones and more"
date: 2008-03-27 11:59
comments: true
categories: Web 2.0
author: Oliver Thylmann
---









&lt;p&gt;How I love [Amazon AWS](http://aws.amazon.com). In October there were already [hints about Static IPs](http://blog.thylmann.net/2007/10/09/amazon-aws-sla-and-unique-ip/) and now they are here. Check out the [Amazon Web Services Blog post](http://aws.typepad.com/aws/2008/03/new-ec2-feature.html) about all of the new stuff.&lt;/p&gt;

&lt;p&gt;First of all, we now have what they call Elastic IP Addresses and the system is very cool. You get up to 5 IPs to start with. You get one via an API call to AllocateAddress, which allocates you one fixed IP that then belongs to you. Without you using it you pay 1 cent per hour. But you can then do an AssociateAddress and it is attached to a Server and becomes free, meaning you no longer pay for its usage. You can then DisassociateAddress and ReleaseAddress if you do not plan to use it at all.&lt;/p&gt;

&lt;p&gt;Then couple that with Availability Zones, which are zones in their Network Infrastructure that are insulated from each other so that if one zone goes down, another does not (in theory, there might always be odd cases, chance if you want ;)).&lt;/p&gt;

&lt;p&gt;This really means you can do more for a high availability solution with Amazon AWS and if they now start a NOC in Germany, I will possibly never do my own Server again. But they are not here yet so we are just using it for parts of our system, and I am taking a look at [Globalways](http://globalways.net).&lt;/p&gt;

&lt;p&gt;But again, congratulations to the entire Team behind Amazon EC2 for pulling this one of. Thank you. No more DynDNS for our Ad Server :)&lt;/p&gt;


