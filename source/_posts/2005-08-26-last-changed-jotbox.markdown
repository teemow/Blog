---
layout: post
title: "Last Changed JotBox"
date: 2005-08-26 10:55
comments: true
categories: JotSpot
author: Oliver Thylmann
---


Due to playing a little bit more with [JotSpot](http://jot.com/), I now created ourselves a little last changed miniWindow for our Toolbar. I really like to know what is changing around me, so something like this should be on the main page or somewhere else. I opted for the Toolbar as there is an error message for people using the WYSIWYG editor on the main page otherwise.

The script is rather simple. 


&lt;jot:miniWindow title=&quot;Latest Changes&quot; contentStyle=&quot;font-size:8pt;&quot; width=&quot;80&quot; hidden=&quot;false&quot;&gt;
&lt;jot:search order=&quot;editTime-&quot; set=&quot;nodeResult&quot; limit=&quot;5&quot; forAll=&quot;true&quot; /&gt;
&lt;jot:loop over=&quot;nodeResult&quot; set=&quot;node&quot;&gt;
&amp;nbsp;&amp;nbsp;&amp;nbsp;1. [[wiki:${node/path}][${node/name}]] (${node/time/relative} by ${node/user})
&lt;/jot:loop&gt;
&lt;/jot:miniWindow&gt;


Remember that the spaces are important. A 3 whitespace indent before the 1 will make this into a list going from 1 to 5 (due to the limit=&quot;5&quot;) in the loop. You simply need to create this code in something like LastChangedBox within your Wiki and then include that in your Toolbar (simply click edit in the toolbar and it will be self explanatory). Bingo, you now have your last 5 changes pages, with the time from now and who changed them in your toolbar.

