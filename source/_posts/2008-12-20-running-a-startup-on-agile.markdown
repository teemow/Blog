---
layout: post
title: "Running a Startup on Agile"
date: 2008-12-20 13:34
comments: true
categories: Software Development
author: Oliver Thylmann
---







I have this one sitting in my &quot;To Blog&quot; bookmarks list for ages now, so here it goes. It is actually inspired by a great post by Eric Ries entitled &quot;[A new version of the Joel Test](http://startuplessonslearned.blogspot.com/2008/09/new-version-of-joel-test-draft.html)&quot;. The original [Joel Test](http://www.joelonsoftware.com/articles/fog0000000043.html) was written in 2000 and Eric tried to update it a little bit based on his experience in software development in agile teams. Same as him I start with Joel's list.

	* Do you use source control? Yes, essential and check.
	* Can you make a build in one step? We have continuous integration, so check.
	* Do you make daily builds? Well, building continuously would qualify I think. Ok, we could always do with more automated test but we are doing ok.
	* Do you have a bug database? Sure, check.
	* Do you fix bugs before writing code? There I am with Eric, yes we try to, but bug is not bug. There are some things we accept to fix later. But we do have an ASAP list that gets precendence over anything else.
	* Do you have an up-to-date schedule? Here I again agree with Eric, damn I agree aa lot with him, but that's the point. What we learned is that not the schedule is important, but keeping sprints short. As soon as a sprint goes over more than 2 weeks we have a problem of too big a backlog for the next one, too long testing, too much waiting, too hard to test features and the like. Our progress, which is what it is about, is better with shorter sprints, which take less planning and can actually be planned on the spot.
	* Do you have a spec? Eric rephrases that into &quot;does the team have a clear objective?&quot; Yes, this is what is important. We try to have a 1-3 sentence goal for each sprint. Everything is aligned to that. There are then cross functional teams that build the spec. In the first meeting we create scribbles, get the features down, try to make the interactions clear, and go from there. This first meeting is very important though and we have failed in this before because you need the cross functional team there and you need to discuss things to the end and fight it out and the team needs to stay fixed afterwards. This is sometimes hard, but very important.
	* Do programmers have quiet working conditions? It's not one size fits all. Two of our devs moved out of each others office because one likes to hear to music and one likes it quiet. Some want company, some don't. You need to enable that.
	* Do you use the best tools money can buy? We try to and this should probably be taking up a bit more, but hey, we are a startup that watches the money.
	* Do you have testers? Everybody writes tests first and then codes, as best possible. Yes, we have somebody responsible that makes sure everybody does that, but developer is developer. This is still to be decided in my mind. After a certain team size you probably need someone that takes care of the infrastructure, enabling automated testing by developers, and builds new test cases and handles the release process. But for small teams, it's a team responsibility.
	* Do new candidates write code during their interview? We didn't do that yet, but more or less knew the people we hired, so it wasn't so necessary. What we would be doing more in the future to give a new developer full responsibility for a new feature that is laid out so that it interacts with the entire platform. Then let everything be discussed in the weekly code review.
	* Do you do hallway usability testing? Majorly lacking here, sorry. We are trying to keep iterations short but will probably have to do some learning in this field.

Next up are some of his suggestions. Yes, we do work in small batches and through daily scrums we know who is working on what and hence there are little conflicts at checking. He also talks about practicing the five Whys which I remember from the MBA. It's a great idea. Why is it a great idea? Because it allows you to think up till the root cause? Why does that help? Because you don't fix something that does not need fixing but what really went wrong. Why? Because after the first idea you ask why again and go on from there... get the point? 5 Whys. It's a great system and oh so simple.

He then goes on to talk about the difference between defects and polish. This is very important to understand. We build a feature, often taking the easy way for the interface (after we learned building it complicated first is nuts ;)) and how it works but making sure there  are no bugs, that it works, and does so reliably. From there we can build polish if need be. This is a subtle difference, but an important one.

His last point is probably the most important one: Does everyone (he names programmers but that's not enough) understand how what they are doing relates to the company strategy, well being, vision, day to day business? This is where the cross functional teams help. It helps programmers understand what people do. A good developer will go nuts finding out that somebody sits there doing something in the interface for 2 hours every day when the dev can whip up something simple and get that down to 5 minutes. But you need to have communication.

That is actually one thing that I would like to add. The most important thing, and the reason for being of Agile, is that you have communication. The entire point of now doing waterfall development is that you know that the biggest problem in software development is that people speak different languages. Every party will need to try to work out what the other party really means. That is hard, and painful sometimes but only understanding will lead to good code.


