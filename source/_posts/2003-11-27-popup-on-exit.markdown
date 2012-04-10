---
layout: post
title: "Popup on Exit"
date: 2003-11-27 12:26
comments: true
categories: Web Development
author: Oliver Thylmann
---


I recently had the problem of trying to have a Popup open when a user closes a page. Knowing people in the porn biz helps ;) So this is it:


&lt;script LANGUAGE=&quot;JavaScript&quot;&gt;
&lt;!--
var exit=true;
function ciao()
{
if (exit)
window.open('http://ennead.de');
}
// --&gt;
&lt;/SCRIPT&gt;


Then you add 

onUnload=&quot;javascript:exit=false&quot; 

to all your links to that the popup doesn't come up when somebody clicks a link.

You're done. Congratulations. :)

&lt;B&gt;Update**: Thanks to [Jeremy](http://www.ensight.org/)'s comment I'll add that you have to add a 'onUnload=&quot;ciao()&quot;' to your body tag for this to work. I almost had everyone breaking out in sweat there as it didn't work ;)

