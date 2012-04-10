---
layout: post
title: "Emerging Technologies Hype Cycle by Gartner"
date: 2006-08-18 07:39
comments: true
categories: Web 2.0
author: Oliver Thylmann
---









Some days ago [Gartner](http://gartner.com/) has released their [2006 Emerging Technologies Hype Cycle](http://www.gartner.com/it/page.jsp?id=495475) and there is some interesting stuff in there.

As a side note, I had the same graph placed in front of me for coding languages in an argument by consultants to change a web platform from PHP to Java in my [last job](http://ligatus.de/). Thankfully I, with the help of the team, wasn't easily convinced and we stuck with PHP back then. I am still sticking with PHP now, even though I could go Ruby, but for now I am happy with the decision.

Anyway, back to the Gartner report. To start with, here is the hype cycle:

&lt;img width=&quot;450&quot; vspace=&quot;4&quot; hspace=&quot;4&quot; height=&quot;251&quot; border=&quot;1&quot; align=&quot;middle&quot; alt=&quot;Gartner Hype Cycle&quot; src=&quot;http://blog.thylmann.net/gartner.jpg&quot; /&gt;

The general idea is that at the top of the curve, the hype around something is amazingly high and it needs to go through a valley of disillusion to be really adaptable by a large enterprise. All in all, this is not necessarily incorrect, but obviously depends on how far out there the company is and how far it sees technology as something of its core capabilities.

So one big part of all of this is Web 2.0. Social Network Analysis is obviously one thing and I have to agree that with reasonably big sets of data, this can get really interesting. Ajax is the second item on their list and they also see a lot of potential there, but I like this part:

*High levels of impact and business value can only be achieved when the development process encompasses innovations in usability and reliance on complementary server-side processing (as is done in Google Maps).*

One thing that is also important here is that with the current hype around frameworks and splitting code in a Model-View-Controller fashion again, the general way of working with JavaScript is a real problem. A lot of controller parts are suddenly back in the view and you don't want that. Having been able to get some very good developers on board at [Ormigo](http://ormigo.com/), I am happy to say that we seem to have found a good solution though. [Timo](http://teemow.com/) has already [posted about it](http://cakebakery.de/2006/08/17/waschmittel-in-der-kuche/) on [Cake Bakery](http://cakebakery.de). What Timo and [Dirk](http://olbertz.de/) developed is a model-view-controller system for Ajax, with the help of things like JSON and [jQuery](http://jquery.com/). Our templates are now fully free of JavaScript and the entire Ajax Framework is being tested via Unit Tests. Of course there are still some rough edges but things are moving along nicely and we are thinking about putting the entire system on Google Code or something similar in the not too distant future.

Management Tip: Buy your coders all the books they want to read because there are some interesting things bound to happen, especially if you have people that have a thirst for knowledge.

Collective Intelligence is another big term that Gartner throws around and boy do I believe it to be true. While we often think about speed to delivery, which might make a command control system more worthwhile, many people forget that software is more like art. There is not one way to do something, but a million and diversity of opinion might slow you down in the short term, but make you more agile in the long term. Additionally, switching costs on the net are close to zero (in the absence of interlinking users for example and allowing for internal networks to build) and that means that the small things make a difference. These small things mean that you need collective intelligence to find them. You need to rely on your users and be able to adapt fast. Uncertainty is a big thing that management will have to deal with in the future. I'd like to quote somebody here:

*People are not afraid of change. They fear the unknown. - Dick Brown, chairman CEO of EDS*

With no clear view of what will happen next, the known will have to become that things are unclear. Change needs to become part of the development system. For that, you need the right people.

*If you don't like change, you're going to like irrelevance even less. - General Eric Shinseki, Chief of Staff, U.S. Army*

;)

Mashups are also mentioned but I believe their importance to be rated as moderate only because the idea of the mashup is so diverse. I sure as hell can host my static files on Amazon S3, get Maps via Google, Geocode via a third party, score data via somebody else and ... . You get the idea. That's a mashup if you want.

All in all, the future is continuing to be interesting, but I am repeating myself.







