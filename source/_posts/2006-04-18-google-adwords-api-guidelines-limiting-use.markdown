---
layout: post
title: "Google AdWords API Guidelines limiting use"
date: 2006-04-18 09:26
comments: true
categories: Advertising
author: Oliver Thylmann
---







If you are working with the AdWords API I'd read the new [Terms](http://www.google.com/apis/adwords/terms_preview.html) because there is some very restricting information in there called Co-Mingling:

*III 2 (c) Co-Mingling of Campaign Management Data. This Section III(2)(c) does not apply to End-Advertiser-Only AdWords API Clients. *

*i. Inputs Fields. The AdWords API Client must not show in the same area of a page, or otherwise visually or functionally associate, any input fields for collecting or transmitting AdWords API Campaign Management Data with the content of Third Parties or input fields for collecting or transmitting data to Third Parties. For example, an AdWords API Client must not (a) use the same input field or button to collect or use data that will be used as both AdWords API Campaign Management Data and also as data or instructions for a campaign on a Third Party advertising network, or (b) use input fields or buttons to collect or use data for AdWords API Campaign Management Data which are visually adjacent to input fields or buttons that are used to collect or use data or instructions for a campaign on a Third Party advertising network.*

*ii. Functional Separation. Any information collected from an input field used to collect AdWords API Campaign Management Data may be used only to manage and report on AdWords accounts. Similarly, any information or data used as AdWords API Campaign Management Data must have been collected from an input field used only to collect AdWords API Campaign Management Data. For example, the AdWords API Client may not offer a functionality that copies data from a non-AdWords account into an AdWords account or from an AdWords account to a non-AdWords account.*

*iii. Campaign Management Data Storage. All AdWords API Campaign Management Data must be stored separate from Third Party advertising network data. Additionally, AdWords API Campaign Management Data may not be stored in a manner that is associated (through relational data structures, links or otherwise) with Third Party advertising network data.*

*(d) Co-Mingling of Reporting Data. AdWords API Report Data may be displayed in the same area of the screen as, or adjacent to, non-Google data for the then-current end user, as long as it is labeled as Google data. Also, an AdWords API Client may display aggregated data that is calculated in part or in whole based on data or information from a Third Party. This Section III(2)(d) does not apply to End-Advertiser-Only AdWords API Clients, except that all AdWords API Clients may not display non-Google data in a manner that would lead any person to reasonably attribute such data to Google or an AdWords account.*

On thing is important here. This does not apply to End-Advertiser-Only AdWords API Clients, but anyone that resells SEM Management systems, will have a problem. If you have your own network for example, and resell that network plus AdWords management to a client, you cannot really do that. Well you can, but you need to do it fully separately, without the two systems learning from each other. If you run a service provider for SEM campaigns, this is important to you.







