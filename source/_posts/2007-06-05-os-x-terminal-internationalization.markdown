---
layout: post
title: "OS X Terminal Internationalization"
date: 2007-06-05 19:02
comments: true
categories: Computers
author: Oliver Thylmann
---






&lt;p&gt;I have a problem and I have high hopes that this might solve it. A little background is in order. To manage our internal documents we are using [Subversion](http://subversion.tigris.org/). Not only for development stuff but also for all other documents. The nice thing is that everything is versioned, backed up, and available from every pc. A small &lt;em&gt;svn update&lt;/em&gt;, and all documents are up to date, a small &lt;em&gt;svn commit&lt;/em&gt; with a comment and your new version is in. All cool.&lt;/p&gt;

&lt;p&gt;On Windows, we don't have a problem but on OS X there is one. The thing is that Subversion was done for development stuff and the shell is not really done for the average joe. There is a tool for OS X called [svnX](http://www.apple.com/downloads/macosx/development_tools/svnx.html) but that is really nothing more than a wrapper for the shell commands. The OS X shell is not properly internalized. The problem is that the German letters like Ã¼Ã¤Ã¶ do not propperly work, and for business documents, this is something you use a lot. E.g. Founding would be called GrÃ¼ndung.&lt;/p&gt;

&lt;p&gt;As the internationalization is not perfect, svn checkout will get the documents on your hard disk. After that is done you have one document that is called GrÃ¼ndung.doc for example. But when you do a ls, you will not get GrÃ¼ndung.doc but something like GruSOMETHINGndung.doc. When Subversion then does a status check it will tell you that you do not have GrÃ¼ndung.doc in your directory and a GruSOMETHINGndung.doc that does not have a status in the Subversion directory. As there are lots of documents with Ã¤Ã¶Ã¼ you will have e.g. 30 documents that are not subversioned and 30 document that are missing.&lt;/p&gt;

&lt;p&gt;Now that is a PAIN! And all tries to internationalize the shell have been unsuccessful. .profile now includes:&lt;/p&gt;

&lt;p&gt;&lt;em&gt;export LC&lt;em&gt;CTYPE=de&lt;/em&gt;DE.UTF-8
export LC&lt;em&gt;ALL=de&lt;/em&gt;DE.UTF-8
export LANG=de&lt;em&gt;DE.UTF-8
export LANG=en&lt;/em&gt;US.UTF-8&lt;/em&gt;&lt;/p&gt;

&lt;p&gt;Nothing. I also built a new bash from MacPorts. Nothing either. I would be happy for any suggestions.&lt;/p&gt;



