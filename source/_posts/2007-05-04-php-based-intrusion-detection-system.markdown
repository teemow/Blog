---
layout: post
title: "PHP based Intrusion Detection System"
date: 2007-05-04 17:05
comments: true
categories: Web 2.0
author: Oliver Thylmann
---










This is one of the first things that [Mario](http://mario.heideri.ch) started to implement when he arrived here at [Ormigo](https://ormigo.com/). It's now called phpids and available for all to use, already gaining some traction with the security crowd. The thing is that we are dealing with lots of personal data here at Ormigo, so we want to try to make as sure as possible that it's safe.

What the phpids does is listen in on strange requests coming into a php based application and gives them a certain escalation state. Based on state it can choose, or rather be told to, do certain things, like fully deny access from a certain IP, remove the page for that user and only show a warning, do nothing and log, send our email alerts, whatever. It's there to make sure that you are not running blind. Holes in the application are sure to happen, but the biggest problem is not knowing about them.

You can check out the code right [here](http://code.google.com/p/phpids/)  on Google Code, or [join the Google Group](http://groups.google.de/group/php-ids) or simply do a [Smoketest](http://phpids.heideri.ch). Have fun and be sure to report back.

Since [coming-out](http://christ1an.blogspot.com/2007/05/php-based-intrusion-detection-system.html), there [has]( http://www.dragoslungu.com/2007/05/02/php-based-web-application-ids-ips/) [been](http://www.buayacorp.com/archivos/php-ids-intrusion-detection-system/) [some](http://www.logadmin.net/2007/05/sistema-de-deteccin-de-intrusos-basado.html) [international](http://www.nexen.net/actualites/securite/16978-intrusion_detection_system_en_php.php) [coverage](http://www.0x000000.com/?i=263) already and this is just the start. Obviously this creates an overhead but hey, let's see where it takes us, and from a management perspective you do need to calculate the potential costs of a breach of your application against the possible costs of a few more servers.

I am looking forward to seeing more people take it up and contribute back into the project.

