---
layout: post
title: "Moving to MMS"
date: 2002-01-09 08:24
comments: true
categories: Wireless
author: Oliver Thylmann
---


(Originally published on infoSync) It's a mess! Currently, all GSM phones can send SMS text messages, and if you have a Nokia phone you can also send and receive ring-tones and bitmaps - to other Nokia phones, that is. Others wanted their phones to have that capability too though, especially because ring tones and images are a lucrative business. Now, manufacturers such as Ericsson and Siemens have adopted a messaging standard called EMS in some phones. Nokia didn't, arguing (maybe rightfully so) that their phones can already do what EMS has to offer. Result: nobody dares to use the damn thing because you have no clue if it will arrive at a phone that supports you type of message.


&lt;!-- more --&gt;


The business for ring tones, images, screensavers and the like is booming, with companies previously doing only adult entertainment now jumping on the running train, which really shows that there is money to be made. People love these things, and I recently saw a Siemens ad which was trying to make it clear to the viewer that the Siemens C45 can be customized with ring tones, to fit the user's personality. Another ad I saw was from Nokia saying something along the lines of &quot;soon you will be able to watch videos on your Nokia mobile phone.&quot; All these companies are trying to hammer it into your head that your phone is capable of more than voice calls and sms messages.

But, if you send an image, or a ring tone, from a Nokia phone to a Siemens phone, then you will get 3 or more SMS messages with a seemingly random collection of letters. The sender of course pays for 3 SMS messages without even knowing. For all he knows he just sent a nice image of a birthday cake.

What does that tell us? Among other things that the maximum size of SMS messages is to small. We need the option of sending big chunks of data to a phone that understands them. Things like colour photos from home, a short video clip from the first steps of your daughter, an MP3 sound byte with the best wishes for your birthday from your parents - and the list goes on. We also need another billing method that works in relation to the size of the message. Some GPRS phones already have an entry in their preferences called &quot;SMS over GPRS&quot;, but this is not yet enabled by most operators.

The great saviour from all of this mess might be a new standard called Multimedia Messaging Service, or MMS in short, which is now accepted by all (or at least all significant) mobile devices manufacturers and carriers as the next messaging standard to be used. MMS will let users of supportive devices send and receive messages with not only text but also graphics, images as well as audio and video clips. Yes, you read that correctly. Video sequences, audio clips and high-quality images will be able to be sent from and to MMS enabled phones. It's a new world of messaging!

MMS supports the following formats (partial list):
GIF and JPEG
MPEG-4
MP3, WAV and MIDI


Of course, not every mobile phone will be able to receive MMS messages from the very beginning, which is why the so-called Multimedia Messaging Service Centres (MMS-C) can route MMS messages to different destinations. This can be a mobile terminal or a web page and in the case of sending the MMS message to a web page, the MMS-C will send a standard SMS message to the receiver to tell them of an arrived multimedia message and how to reach it.

Now, since we are already talking about e-mail, there are a few changes in MMS that make it a bit more like e-mail. One of those things is that you will have CC (carbon copy) and BCC (blind carbon copy) fields. But let's get a bit more technical to understand what is really happening, because some interesting things turn up there. For one, MMS messages are pushed to your phone with the help of a system called WAP Push, which also uses the WAP Gateway/Proxy to talk to your phone. Push is available in WAP starting with version 1.2. Many users might not want huge amounts of data sent to their phone - which they will possibly have to pay for - to be pushed to them every few minutes, especially on their birthday when thousands of friends send them the last birthday greeting video. Introducing: MMS On-Demand Push. This is a method where the MMS message is stored on a server, while you are sent an SMS message to alert you of the arrival. You can then decide if you want to read it now or later, much like checking your e-mail.

Whoa, hang on a minute there, some people will say now. SMS messages go over an extra signalling channel and will the WAP Push be happening over that channel? Nope. That's probably one of the bigger differences compared with SMS, and also the reason why you need at least GPRS capabilities in the networks. MMS runs over IP based mobile networks and needs the possibility of bandwidth based billing. It will not use the SMS signalling channel. This is possible since new 3G networks have vastly higher capacities than 2G networks, so that the extra use of the traffic channel will not be a problem for the networks. You will need to have a phone that operates in the Class-A mode in GPRS though, which means that the GPRS link stays active even when you are doing other things.

MMS messages will also not use a specific protocol, but instead WAP and general Internet protocols like SMTP, HTTP, MIME and others. SMTP and MIME will link the Multimedia Messaging Service Environment to your device making MMS kind of like a presentation layer for basic e-mail protocols. The first systems will be based on WAP protocols though.

An important part of MMS will also be something like revenue sharing between the carriers and third parties, especially as many of the first messages will be originating from Internet connected PCs.

Many people will now say that the close similarities to e-mail will enable spamming mobile phones beyond current comprehension - and in general, I agree. This becomes even clearer once you find out that there is a user profile with MMS which you can manage via an Internet connection. You will be able to decide which media types to get directly and which to leave on the server for later pick-up via the internet, when to receive notifications and, now get read, include filtering rules and routing tables for unsolicited and undesirable messages. Whee.

All in all, the introduction of MMS will bring us one standard for all phones with the back-up via e-mail communication. This might really bring us new possibilities in relation to things we can send with our phones. With that, things will get a bit more dangerous in relation to spam - but like they say, you can't have your cake and eat it too.

