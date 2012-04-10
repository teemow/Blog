---
layout: post
title: "Tim Bray on Search"
date: 2004-02-03 20:21
comments: true
categories: Web Development
author: Oliver Thylmann
---


I read Tim Bray's ([look at that resume!](http://www.tbray.org/ongoing/When/200x/2004/01/01/WhatNext)) [On Search, the Series](http://www.tbray.org/ongoing/When/200x/2003/07/30/OnSearchTOC) on my way to Oxford last week and it's a truely great piece on the internals of building and/or running a search engine. Here are a few thoughts about the search space and a few interesting bits from his paper.


&lt;!-- more --&gt;


He co-founded Open Text Index, which at one point was the only search engine next to Lycos and Infoseek it seems. Now of course there are lots of different players and I remember some of them from when I looked closer into EIPs (Enterprise Information Portals) some years back (an interesting space to say the least).  He also points out that one of the big historical players was WAIS, which is now part of Hummingbird (who are into EIPs) and can be found at [wais.com](http://www.wais.com/). Previously, back in the beginning to mid 1990s, you could get to it via &lt;i&gt;wais:&lt;/i&gt;, yep, that's wais instead of http :) I can even remember using that when I got my first PC, which was running Windows 95 and was connected to the Internet via a 10mbit/s Laser on the roof of the student home.

But back to the subject of search. Now search systems cost well into the six digits, and some of it might even be warranted in the sense that some of the systems out there even build a Taxonomy of your Documents and order them into the right categories. Tim continues with some stats, saying that less than 0.5% of all search users use the &quot;advanced search&quot; screen, and they enter on average 1.3 words before hitting enter. This is with how little information a search engine will have to work with. They also almost never look at the second results page. 

[How Search Works](http://www.tbray.org/ongoing/When/200x/2003/06/18/HowSearchWorks) covers the basics of search-engine engineering, with docs, postings, words and the wonderful index. Great stuff to read if you are interested in how you can efficiently bring order into chaos. 

He also has a great example of how hard it is for search engines to gather the meaning out of a sentence by just knowing the words. Check this: &quot;&lt;i&gt;Time flies like an arrow, but fruit flies like bananas.&lt;/i&gt;&quot; Another problem is german, where we have words made up of several different words. In the Oxford English Dictionary, &quot;set&quot;, &quot;run&quot;, &quot;get&quot; are the words with the longest entries.

As for Google, he concludes that it is more important how popular something is, than to know what it is about, ... in search he means. And it's an interested conclusion to take from how Google ranks it's entries, by popularity, and that people perceive the order of the results to be good.

Another goodie for the SEM people out there, &lt;i&gt;frequencies matter more than counts&lt;/i&gt;, meaning that if there is a word that is very rare in your article, it will have more weight in searches than another word.

As for free open source search-engines, Tim Bray thinks that [Lucene](http://jakarta.apache.org/lucene/), now part of Apache, is probably the best one out there. There is lots more stuff in there including infos on how to build your own crawler and, as a final article, his [Basic Resource Finder](http://www.tbray.org/ongoing/When/200x/2003/12/16/BRF), a search-engine that still needs to be built.


