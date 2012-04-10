---
layout: post
title: "Google Revealed"
date: 2006-09-03 14:13
comments: true
categories: Business
author: Oliver Thylmann
---







Just building a company, reading articles about how companies work obviously interest me. They have interested me before actually. So [here](http://www.informationweek.com/management/showArticle.jhtml?articleID=192300292&amp;pgno=1&amp;queryText=) is an article on InformationWeek entitled [Google Revealed: The IT Strategy That Makes It Work](http://www.informationweek.com/management/showArticle.jhtml?articleID=192300292&amp;pgno=1&amp;queryText=) that is really interesting.

&lt;em&gt;Google's programmers are 50% to 100% more productive than their peers at other Web companies, a result of the custom libraries Google developed to support programming of massively parallel systems, Arnold says. He estimates the company's competitors have to spend four times as much to keep up.&lt;/em&gt;

That is the first thing I absolutely see as true. If you have a focus on IT then you will need to make your developers perform well. The thing is that this is not a linear equation. Sometimes developers have to do things that make you slower to make your faster. Our developers just worked on a MVC framework for JavaScript. Just putting JavaScript in the Views of cakePhp would have made us faster in the short run, but in the long run, the new solution is a lot better and already paying off now.

&lt;em&gt;To wring every ounce of performance from its hardware, Google writes custom software--lots of it. Major innovations include MapReduce, a programming model to simplify processing and create large data sets; BigTable, a system for storing and managing massive amounts of data; Sawzall, an interpreted programming language for analyzing large data sets in a distributed computing environment; Google File System, a distributed file system for data-intensive applications; and Google Workqueue, a system that groups queries and schedules them for distributed processing.&lt;/em&gt;

Lots of innovation here. The problem is that we are both reading a writing a lot and that's a different thing that a large read only system. I am not even sure if AdWords runs on the same system or if they need more of a standard database approach there. They probably still figured it out :)  Google also has its own Web server that uses a CGI interface for linking in databases, which seems to be faster for them. Makes me think again about lighttpd which looks very promising.

Google also built its own CRM, which I can fully understand based on the CRMs that are out there, but are using Oracle Financials for the financial backend, which again I understand with that kind of stuff being a lot more standard without Google being able to do much about it.

Next interesting things is that Google uses a matrix like management structure with everyone reporting to different people at the same time, which in general is complicated and probably works a lot better for developers than sales people, but which can be made more manageable with technology. Above that, Google engineers switch projects every three months, which again needs a different management system. This is also one of the reasons they make sure that they hire interesting and intelligent people, because they have to get into new products fast.

&lt;em&gt;Lots of small, short-lived projects mean traditional project management software based on task lists isn't right for Google. For one thing, techies aren't very good at cataloging how they spend their hours. What they are good at, it turns out, is writing up a few short sentences or snippets about what they do each day. Those get compiled in a database along with periodic updates from project leaders about a team's deliverables. The project system tags the input by topic and routes to the appropriate people. &quot;This is not hard AI,&quot; Merrill says. Still, who else manages workers like this?&lt;/em&gt;

I really like that approach because task management isn't perfect. As soon as your developers understand where you are going and what you are doing and what needs to get done, then the good ones pretty much know themselves what to do. With our agile approach we are at least going as far as not telling everyone what they need to do but just having task lists per sprint and everyone takes what they want to to, being responsibly for achieving sprint goals as a team.  The employee review system is actually very 360 degrees, a lot more than with other companies but something you need for their matrix system.

&lt;em&gt;Google employees use Linux, Mac OS, and Windows on desktop computers, depending on their needs and desires. Many use homegrown programs such as Google Desktop, Google Earth, the acquired Writely word processor, and the recently launched Google Spreadsheets. In general, if an employee wants certain software, he or she can request it through the company intranet without jumping through a lot of hoops for approval.&lt;/em&gt;

100% agreed. Don't make somebody use something when they want to use something else. You just loose performance. We now have 2 windows laptops, to mac laptops and one ubuntu laptop here. Who am I to complain. I just need to make sure the internal system work with each of those systems. As the quasi CIO of Google says:

&lt;em&gt;&quot;Most people in my job try to control. 'Here are the three things you can buy.'&quot; Merrill explains. &quot;I try to control as a little as I possibly can but make it easy to work within parameters that I know how to work with.&quot; &lt;/em&gt;

And again agreed:  The right approach, as Merrill sees it: Talk a lot; use data, not intuition; automate wherever you can.  Ok, the intuition part is relative, mainly because since my last MBA course on Creativity, Innovation and Change, I am now 100% sure that intuition coupled with experience means that your full brain capability can make a lot faster and better decisions if you don't try to put everything in hard numbers.

Then this bit on how they hire:

&lt;em&gt;At Google, however, examples abound, such as the way the company decides on new employees. &quot;No one can hire anyone here,&quot; Merrill insists. &quot;Hiring decisions are made by public groups. We all hire everyone.&quot;&lt;/em&gt;

Again agreed, with that idea actually having come to my mind through[Nerd Herding](http://www.calevans.com/view.php/page/nerdherding) by Cal Evans.

&lt;!-- technorati tags start --&gt;

Technorati Tags: &lt;a rel=&quot;tag&quot; href=&quot;http://www.technorati.com/tag/Agile&quot;&gt;Agile&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://www.technorati.com/tag/Cal%20Evans&quot;&gt;Cal Evans&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://www.technorati.com/tag/Developers&quot;&gt;Developers&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://www.technorati.com/tag/Google&quot;&gt;Google&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://www.technorati.com/tag/Nerd%20Herding&quot;&gt;Nerd Herding&lt;/a&gt;

&lt;!-- technorati tags end --&gt;


