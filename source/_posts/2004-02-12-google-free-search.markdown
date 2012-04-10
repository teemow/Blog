---
layout: post
title: "Google Free Search"
date: 2004-02-12 19:28
comments: true
categories: Web Development
author: Oliver Thylmann
---


I don't know if I missed something but I just found [Google Free Search](http://www.google.com/services/free.html) which allows you to customize the results page to your perferences with logo and colors and things like this. I actually have to admit that I hacked the Google Logo away as it does look weird on my background. We'll see if that changes somehow. Would be good to have some kind of transparency on it that works. 

But while I am at it, I do have a question for the Google Freaks out there. Is there an option to only get results back where the file types end in something, e.g. .html. The thing is as the search is now it finds any page on my site with a given word, including the monthly and category archives, instead of just giving me the entries. I know these end in index.html, but this is invisible and not in the target url as such. And Google actually makes a difference between /index.html and /. Any ideas? Am I making myself clear? :)

**Update**: Thanks to [Charles Jones](http://charleswjones.com) I looked at the filetype variable a little closer. I now added a hidden variable to the search box with the name as_filetype (not filetype on its own) and value &quot;html&quot;, which not only returns files in html but only returns results which end in .html, which is exactly what I wanted. The results should be a lot clearer now, not including category pages and the like.

