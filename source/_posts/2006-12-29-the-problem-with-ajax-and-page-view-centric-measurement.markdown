---
layout: post
title: "The Problem with AJAX and Page View Centric Measurement"
date: 2006-12-29 15:36
comments: true
categories: Web 2.0
author: Oliver Thylmann
---





We love to compare things. That's why [IVW Online](http://www.ivw-online.de/) is so important in Germany, and others world wide. IVW has started out as the company that measures circulation of news papers in Germany and IVW Online is doing the same thing for Web Sites. The idea is that everyone has a standard tracking pixel on their site and this measures page impressions. I never thought this would be very brilliant as a page impression is not a page impression. Forum traffic is totally different from search traffic or high quality editorial content. IVW Online recently worked with [AGOF](http://www.agof.de/) to give us a unique user count, which took a long time to set as a standard as it is very hard to agree on what a unique user is on a web site.

Why is that hard? Because you can use cookies but not everyone uses cookies and those that do might be three people at the same PC. Those that don't mostly are not trackable and especially stuff like proxies makes it even more problematic. But they agreed on something that they call true, which is as good as anything else. It just needs to be the same statistic.

Now the problem becomes even worse because of AJAX. Matt Cutts from Google has a [great post](http://www.mattcutts.com/blog/page-view-metrics-bah-humbug/) on it. The thing is that moderate use of AJAX is a good thing, but if you are IVW tracked, it might be a bad thing because suddenly you seem small. I can leave [Google Finance](http://finance.google.com/) open all day and see the share prices move around, only doing one page impression for the site. Thankfully this is something where AGOF can help, but I still presume that lots of sites out there opt out of using AJAX as their traffic will seem to decline, like it did for Yahoo!, who moved their mail system to a new version using AJAX. This is a good move and I hope the start-ups out there go the same direction.

Another good post on the problem of measuring a sites importance is t[he one by VentureBeat on the new funding of Digg](http://venturebeat.com/2006/12/28/news-site-digg-raises-85m-more-rejects-evidence-it-has-been-gamed/). Comscore for example doesn't count RSS traffic, another problem for sites having high traction.


