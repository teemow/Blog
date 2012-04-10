---
layout: post
title: "Danger lurks around the corner"
date: 2002-09-12 08:36
comments: true
categories: Wireless
author: Oliver Thylmann
---


(Originally published on infoSync) Some months ago, when I visited Danger.com, the site still had a flash animation explaining that Danger was just arround the corner - and it still is. That is, it's not here yet, but based on reports trickling in, Danger is peeking around that corner and readying itself to take center stage.


&lt;!-- more --&gt;


With review devices still being a scarce resource, I dug arround to find out how the device works, what it can do and how Danger is integrating and using their backend to make it all work. After completing the digging, I noticed that I'm getting more interested and not less, which of course is a good sign.

The T-Mobile SideKick will be the first device based on the Danger reference design named HipTop. The device is 116 mm wide, 65 mm high and 28 mm thick, with a 240 x 160 pixel 16-shade grayscale display. It comes with 16 MB of RAM and 12-chord polyphony based on the Beatnik Engine.

Lucky me, the manual for the T-Mobile SideKick appeared a while ago on U.S. regulatory organ FCC&amp;rsquo;s website, and holds some good clues as to what we can expect from the device. Among other things, the SideKick comes with a hands-free headset, a wrist strap and a USB cable. The screen swivels open sideways, revealing the keyboard under it. The USB cable seems to be there for software recovery, as diagnosed by Customer Support, and does not appear to have any other uses. If all goes well, you shouldn't even need it, as Danger can alert users of the SideKick/HipTop of new software updates which can be installed over the air. Such updates range from updating parts of the core operating system to applications on the device.

The device also has several buttons on the side, namely a power on/off button, Jump, Menu, a wheel and a back button. From the sound of it, a quite complete interface.

The first hint of something entirely new, excluding the new design, is the device's activation process, which is executed through the T-Mobile welcoming screen when the device is switched on for the first time. Here, you can create a new user, which will also create an e-mail address like username@tmail.com. In Germany, this will likely be t-email.de, which is the current mailing system, and if users are lucky, the SideKick will be able to make use of existing accounts.

Ringtones can be assigned to AIM buddies since, yes, the SideKick includes an AIM compatible IM tool, as well as to individual callers. For messaging, you can either use AIM, e-mail or SMS, all three of which are distinct applications, eligible for separate upgrades and to my current knowledge totally independent of one another. This also means that licensees of the HipTop reference design can decide which of these applications they want to ship with the device, while users will have a clearer view of costs. In Europe, SMS messages cost extra while e-mails might be part of a GPRS flat-rate, which makes the distinction important.

The Jump screen holds all of the user's applications, including Browser, AIM, Email, Phone, Phone Messages (sms), Address Book, Calendar, To Do, Notes, Camera and Games. The Menu button will give you a menu on any application you are currently using showing you the options you can set or things you can do.

A fun feature is that you can also customize everything via your Desktop by signing in at www.t-mobile.com with your phone number and password. This works because the SideKick actively synchronizes all of the information stored on the device with a server sitting in the Danger network center. This syncronization takes place whenever there is an active GPRS (up to 4 channels downstream, 1 channel upstream) connection, and updates on either side will be queued until this is possible - providing users with the same data in their browser as on their SideKick. This is exactly why the device will be sold with a GPRS flat-rate in the U.S., which as far as I'm concerned is an absolute necessity. The SideKick has no option to turn of GPRS and is built to be always online, continously synchronizing with the server backend. This means that users have little control over the amount of bandwidth they use, making a flat-rate necessary.

As a digression, making the flat-rate - at least for synchronization - a must-have for users of the device will yield interesting results with carriers that introduce devices based on the HipTop reference design. The mere availability of a flat-rate offering will make it hard for carriers to argue why it shouldn't be available for users of other devices too, which might result in carriers devising a method of only channelling syncronization over the flat-rate, even though I'm not sure if this is technically feasible.

The e-mail application is also capable of querying external accounts via POP3, and what's interesting is that it's not the device performing the action - it's the servers in Danger's network center. The SideKick only talks to Danger&amp;rsquo;s servers over a special protocol, which then query the external account. The SideKick doesn't have a clue what the POP3 protocol is. The same goes for AIM messages, which means that Danger can easily add new support for other protocols since this only requires server-side changes to software. Mind you, I have no information suggesting the company will add support for any other IM tools, but just mention that it's likely to be possible (particularly should carriers request it). If AOL decides to change the AIM protocol, there is nothing the user needs to do on his side; Danger just needs to change things on the side of their servers. It's also worth noting that once you have logged into AIM and have a GPRS connection active, you will stay connected even if you exit the application. You need to log out of the application to stop being listed as online. A very good thing in our mind, as the T-Mobile MDA and O2 XDA devices only hold an active data connection until they go into standby (although this problem is said to be taken care of in an upcoming software update).

Another big issue is the back-end service - excluding the obvious fact that Danger makes its money by providing the back-end as a service to carriers - which comes into play when users access websites. When requesting for example www.cnn.com, the query will first go to the Danger back-end, which will request the page and adapt the site for the SideKick's limited browsing capabilities. In the process, content that's bandwidth intensive or otherwise can't be used is removed - for instance, color images will be converted to grayscale and scaled for the SideKick screen since the device can&amp;rsquo;t use them anyway, thus conserving bandwidth. In general, think of the backbone as the user's window to the world.

What everybody already seems to know is that the device will not synchronize information with your desktop, and that's been one of the few complaints about the device. But hey, it kind of does. You can import contacts from your desktop PIM application via the the T-Mobile website, and since the device synchronizes towards information stored there, you'll have your contacts from Outlook, Entourage (Apple OS X) or the Palm Desktop in your device no time. Notice the Mac support? Lots of students have Macs, and the SideKick might be just the cheap and stylish device they - and other Mac owners - are looking for.

One thing to remember is that Danger&amp;rsquo;s users are the people that buy the device, but Danger&amp;rsquo;s customers, where the real money comes in, are the carriers. As such, users will very likely not be able to buy the device directly from Danger, but will have to hope that a carrier which covers their area will sell it. To those of you who do get to play with one; have fun, as from what I've seen this will be quite a device when it arrives.


