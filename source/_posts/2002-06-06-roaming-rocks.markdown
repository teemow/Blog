---
layout: post
title: "Roaming Rocks"
date: 2002-06-06 07:58
comments: true
categories: Wireless
author: Oliver Thylmann
---


(Originally published on infoSync) Holidays are a wonderful invention, particularly if you're going somewhere profoundly different to your home country. Living in wet and cold Germany, hot and dry Egypt sounded like a good plan for a vacation. The interesting thing is that the trip was one of those experiences where I noticed how important coverage and roaming really is, particularly in Europe where we've got small countries and people frequently travel across borders - and thus end up on other mobile phone networks. In this article, I'll attempt to give an introduction to how roaming works in general, as well as take a closer look at the more complicated issue of GPRS roaming.


&lt;!-- more --&gt;


Roaming, in short, is about potentially allowing you to use your phone even if your home network is not reachable, be it because you're simply outside the coverage of your home carrier, or because you're in another country where there isn't even a network that is run by your home carrier or the carrier it's a part of. The former approach is among others applied by Viag Interkom (now O2), which doesn't offer coverage in all of Germany. Viag Interkom users that are outside the carrier's coverage area will be able to use the T-Mobile network instead, which amounts to so-called national roaming. The more common perception of roaming is the latter, though, involving roaming across country borders. If you have a contract with Vodafone in the UK and then take a trip to Germany, your phone will log in to an available german GSM network and do a bit of chatting on its own to find out whether it's supposed to just pick a network randomly, or use Vodafone networks in foreign countries if available (more on this later).

I have to admit I'm used to roaming, frequently travelling between Germany and Belgium, where I even get Frequent Flyer miles for every minute I roam the Belgian Mobistar network with my German T-Mobile contract. I need roaming. I wouldn&amp;rsquo;t know what to do without it. Going to Egypt, the phone was one of the tech items I took, next to a PDA, digital camera and 6 GB portable MP3 player. I was kind enough to leave the laptop at home (but brought a portable keyboard for my PDA ;). After we arrived at the hotel, I called home to say that we arrived safely, with a view over the Nile.

The hotel in Cairo actually wasn&amp;rsquo;t that impressive in terms of roaming, seeing as how it was mostly populated by Egyptians who were - understandably - chatting away in Egyptian. The fun part began when we moved on to a 7 day stay at the beach in Hurghada, and this is where it hit.

Imagine a hotel full of tourists, all from different countries and everyone - as far as you can see - has a mobile phone and are using it to its fullest extent. There are people at the pool playing games or sending SMS messages, people walking on the beach talking on their phone, lots of phones on tables and frequent ringing to be heard. Thankfully, the place was huge, so fortunately all the bleeping and ringing wasn't too prominent, but I think you get the idea. Mobile phones were everywhere, and they were all from different countries. You heard russian, german, french, italian, dutch, english, and several other languages I'd break my tongue trying to imitate the pronounciation of.

These people, roaming like crazy on the Egyptian network of their preference (or their home carrier's preference) are spending an enormous amount of money, divided amongst both the carrier on whose network the mobile phone is operating and the home carrier.

Imagine being in Egypt, sending an SMS to your friend while he or she is currently in Marocco - and you both have a German contract. Now how cool is that if you really think about it? We are taking it for granted here but really; this rocks.

It not only rocks, it also prompted me to look deeper into how this stuff works. Bear with me, this'll be a wild and abbreviation-ridden ride, and particularly so once we get to the part that has to do with GPRS roaming.

For the basic GSM roaming, the invaluable website [ title=&quot;How Stuff Works&quot;&gt;How Stuff Works](http://www.howstuffworks.com/) helped a lot in terms of gaining insight - as it always does.

First a few definitions. Each carrier has a so called System Identification Code (SID) - a unique 5-digit number that is assigned to the carrier by the authorative agency in the country. When your phone powers up, it listens for the SIDs that are available over something called a control channel, and compares them to the SID of the home carrier, which is stored in the SIM (Subscriber Identity Model) card of the phone. If the home carrier SID can't be found, it will presume that it is roaming. Each carrier also has a, or rather several, Mobile Telephone Switching Offices (MTSO), which handle the base stations and calls. The MTSO keeps track of where your phone is, and negotiates the frequency pair (up and down) for your phone to use if you are placing or getting a call (each base station has several, see our Lexicon section for more info on how GSM works). Once your phone starts talking to an MTSO while roaming, the local MTSO contacts the MTSO in your home network and attempts to find out whether the SID your phone says is the home SID matches the rest of your information to find out whether you really belong in that far away network. Your home system then tells the local MTSO that everything is fine (if you're allowed to roam with your contract) and the local MTSO proceeds with its duties, handling assignment to a cell within seconds. Happy roaming.

While this seems simple enough (Editor's note: Yeah, right.), things grow quite a bit more complicated when we move on to using GPRS in a foreign network. This is also the reason for why carriers are quick to brag about their GPRS roaming capabilities, an area where Vodafone currently is in the lead due to their numerous local networks.

GPRS is an overlay to GSM networks and needs a bit more hardware, namely a Gateway GPRS Service Node (GGSN) and a Servicing GPRS Service Node (SGSN), present for routing purposes. The GGSN works as a gateway between the GPRS network and the underlying IP (or similar) network and it connects to other GPRS networks for roaming purposes. Once you attempt to access GPRS in a foreign network, it needs to conduct what is called a 'GPRS attach' to the local SGSN. However, as you're not in your own PLMN (Public Land Mobile Network), the SGSN talks to the HLR (Home Location Register) in the PLMN of your home carrier to validate you and see whether you are allowed to roam or not (now read that again ;). From here, there are two scenarios.

Scenario 1: Your phone (called Mobile Station, or MS for short) talks to the SGSN in the visited network (also called VSGSN) and then tries to connect to the GGSN in your home network (also called HGGSN) with signaling going over an Inter GPRS Backbone. For this backbone, a method gaining ground is the so called GPRS Roaming eXchange (GRX) which, in the above case, will need to handle such things as address management between the networks because the address assigned to your MS will be from your home network and needs to be routed in your visited network (think mail forwarding). The GRX connects to two (or more) networks and takes care of routing, interconnection, IP services, network operation and maintenance. In voice connections, this takes place over standard fixed lines.

Scenario 2: You are registering with the VSGSN and then with the VGGSN. In this case your address is local, but the network will need to somehow authenticate you to the GGSN and let you allow to use all your services with your standard settings, which might or might not be available.

Now we move on (yes, there's more :) to another fun piece of the puzzle, which is the so-callled APN, or Access Point Name. The APN is made up of things the user entered, the user&amp;rsquo;s subscription record and some defaults by the SGSN. The VSGSN will need to somehow get you an address of a GGSN to connect you to, which, just as a reminder, takes care of your connection. At this time our two senarios come into play again.

In scenario one, the VSGSN talks to the HPLMN, which understands your APN and can provide the VSGSN with the address of the HGGSN (the GGSN in your home network). It might be that the VSGSN tries to talk to the VPLMN to get you the VGGSN IP address to connect to, again with the help of your APN, but the VPLMN just doesn&amp;rsquo;t know what to do with your APN since the correct information simply isn't there. This would then be where the VSGSN connects to the HPLMN - see above.

In scenario two, the VPLMN is able to understand your APN and connects you to a VGGSN.

The APN still provides for some interesting options such as forcing the SGSN to use the HGGSN, but to fully explain this as well would be too in-depth for this general introduction, so I'll leave it at that.

Now, if you did not fully understand everything you just read, I suggest you give it another go - or more. You'll be happy to know that I myself had to read through it numerous times and talk to several people to get it all sorted out, so it's in no way an easy matter to delve into.

As studies have shown, up to 80% of roaming calls are placed to the home country, which in relation to GPRS means that you want the services that you are used to from your home network to be available in the network you are roaming in. For this, the GRX approach is crucial because it will let several networks inter-connect to allow roaming users to use their local services (Scenario 1).

To end this with a slightly amusing anecdote, there was a huge catamaran motorboat at the pier next to the hotel where we stayed. It was lovely, and from what I was told it belonged to the founder of Egy Click GSM, one of the local GSM networks in Egypt. Obviously, there's a bit of money to be made in the carrier business, and with roaming being responsible for 15-20 % of some carriers' revenue I'll (not) go out on a limb and guess GPRS roaming is a high priority to the owner of that catamaran as well. I for one volunteer to babysit his boat while he's working on it.


