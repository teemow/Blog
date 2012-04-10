---
layout: post
title: "The Gollum Browser - Wikipedia Ajax Love"
date: 2005-11-28 12:37
comments: true
categories: Web 2.0
author: Oliver Thylmann
---





A new browser has appeared and this one is doing something very specific. It accesses Wikipedia, that's it. The Browser is called [Gollum, the Wikipedia Browser](http://gollum.easycp.de/en/) and is written in Ajax, with PHP5 driving the code behind it. This really means that you can very simply include the browser as a popup.

function gollum(q, l, wl)
{
var wikiwin =  window.open(&quot;http://gollum.easycp.de/gollum/gollum.php?a=core&amp;l=&quot;+((l)?l:'')+&quot;&amp;wl=&quot;+((wl)?wl:'')+&quot;&amp;q=&quot;+((q)?q:''), &quot;WIKI_ENVIRONMENT&quot;, &quot;height=580, width=780, top=0, left=0, menubar=0, location=0, resizable=1, status=1&quot;);
wikiwin.focus();
}

Having the required script in this post, would allow me to simple link &lt;a title=&quot;Term in Wikipedia look up&quot; href=&quot;http://blog.thylmann.net/gollum('Germany','en','en')&quot;&gt;Germany&lt;/a&gt; and clicking the word would end up opening the browser with the Wikipedia Definition on it. I could of course simply link, but this would be only half as cool, wouldn't it?

{&lt;a rel=&quot;tag&quot; href=&quot;http://technorati.com/tag/Web+2.0&quot;&gt;Web 2.0&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://technorati.com/tag/Gollum&quot;&gt;Gollum&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://technorati.com/tag/Ajax&quot;&gt;Ajax&lt;/a&gt;, &lt;a rel=&quot;tag&quot; href=&quot;http://technorati.com/tag/Wikipedia&quot;&gt;Wikipedia&lt;/a&gt;}


