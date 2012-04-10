---
layout: post
title: "Mobile IP explained"
date: 2002-02-09 08:14
comments: true
categories: Wireless
author: Oliver Thylmann
---


(Originally published on infoSync) First of all, we need to take a look at how all this IP mumbo jumbo really works - or the basics of it, at least. IP stands for Internet Protocol, and the interesting part for us is the general routing of data packets it's responsible for. When I send you a direct instant message (e.g. ICQ) from my computer, this message is instantly split up into several data packets which are numbered, and sent via my network card (or modem) into the network I'm connected to. Just for argument's sake, we'll now presume you are sitting far far away in another country.





What happens next is that my packet gets sent to my so-called default gateway, whose address was provided to me (automatically) by my network provider. That computer looks in its routing table to see where to send all the packets, and then does just that. Each and every one of those packets include your address, and suddenly - the packet arrives somewhere where a router/switch knows roughly where that address is located, and all the packets are sent in that direction. Then, another one of these boxes responsible for routing the packets knows the exact network that your computer is in, sends the packets there for your computer to get them. Finally, the packets are put back together and the message pops up on your screen - and everyone's happy.

Now, lets change that scenario slightly. Let's say you're dialed in via your W-CDMA capable laptop, sitting on a train from Cologne (Germany) to Brussels (Belgium). When you entered the train and sat down, you initiated your network connection - and right now, among other things, you have established a secure connection to a web based conferencing system, are online with multiple instant messaging services, and have initiated a gaming session on Everquest. You're a busy guy, or girl for that matter.

Under closer scrutiny, it suddenly becomes clear that many or all of these applications need a continuous connection to the network. Some probably save your current IP address as part of their methods of keeping track of you, and start complaining once that address changes.

Our second look, which is what will bring you the a-ha experience, goes to what part your mobile phone plays. While you are moving along, your phone keeps up a connection to at least one WCDMA base station, and when you've strayed too far changes to another base station that's closer by - which is where the problem arises. It might well be that the traffic sent and received from your second base station is routed totally different than from your first one, possibly because your carrier has different backbone systems throughout the country. If you move over the border, you suddenly find yourself connected to one of the carriers that your carrier has a roaming agreement with, so at the very latest things will really change at this point (different carrier, different network, different backbone, different country, different whateveryoucanthinkof).

Right about here is where everything suddenly becomes a major pain in the emm... butt, because if they want to keep up your connection, then you will absolutely have to use the same IP address the entire time. The problem is that if packets are sent back to your IP address, then under normal circumstances they would end up at your first base station. You are not connected to that one anymore though, are you? This is exactly where MobileIP comes in. The idea is to have a system in place that will let you carry your IP address along wherever you go while you stay connected.

To learn more on how this works, and to be sure to not say anything that is completely rubbish, I got in touch with an engineer at Nokia who also has a bunch of people sitting around him which have written some of the RFCs (Request for Comment), used in the development of several of today's Internet standards in relation to MobileIP. If there's anyone who could provide me with the right answers, he certainly qualifies. He was kind enough to answer some questions for me, and here are the answers straight from the horses' mouth.

Oliver: Could you please first introduce yourself and tell us a bit about what you do at Nokia?

T.J. Kniveton: Sure, Oliver. My name is T.J. Kniveton, and I am a senior research engineer at Nokia in Mountain View, California. We have a small research group here filled with creative experts who are focused on forming new mobility technologies related to Mobile IPv6.

Oliver: The IETF Mobile IP Working Group seems to be behind all this. How many people or companies are those? Will it be a world wide standard to attack the discussed problem?

T.J. Kniveton: The Internet Engineering Task Force (IETF) is a unique organization, which is composed of a very diverse set of people. It is engineering-driven, and made up of a number of focus areas like Security, Routing, and Applications, with many individual working groups (WGs) tackling specific issues. There is no membership criterion to the IETF, per se. Any interested individual can post messages on WG mailing lists or show up at one of the meetings and contribute their engineering ideas to improving the future of the Internet. In this sense, it's very democratic.

Within the IETF, mobility has received a lot of attention lately. The Mobile IP WG meetings are filled with hundreds of people from companies and universities all over the world. It is very representative of the organizations that make up the Internet itself, and the ideas are so diverse and plentiful that it may be challenging for the WG chairs to incorporate everyone's ideas.

The Mobile IP WG has a number of drafts and RFCs which make up the core of its work. These are loosely organized around Mobile IPv4, and Mobile IPv6, which are two standards for enabling mobility in the way you described above. There are dozens of related drafts that describe optimizations and extensions to these protocols for enabling all different types of scenarios.

The great thing about the IETF is that instead of just writing specifications and unleashing them on the world, the engineers that make these recommendations also implement and test their ideas. So before a draft can become an RFC, it has already been tested and interoperability experiments have been done, which gives us more confidence that it is a realistic idea and will work in the real world. The IETF's motto is &quot;Rough consensus and running code,&quot; and you would be surprised how much progress can be made on a technology when the top engineers from all sorts of companies, organizations and schools, put their minds together to hammer out a solution to the Internet's hardest problems.

Oliver: Can you explain in a bit more detailed way, beyond my simple introduction, how MobileIP works, as of currently?

T.J. Kniveton: Actually, Oliver, I think you did a good job of summing up the basic concepts. Like I said, there are two protocols to consider here, MIPv4 and MIPv6. Just like IPv4, MIPv4 has been around for a while, and is well into the standards track process. MIPv6 is also a mature document, having gone through 15 revisions so far (!) and the WG is in the final stages of working out security issues related to address ownership.

To illustrate the address ownership issue, imagine if you were on your train between Cologne and Brussels, busily ICQing your friends and maybe even having a voice-over-IP call to your special someone. Meanwhile, I am sitting in Helsinki, a bit bored, and decide that I want to steal your active connections. After looking up your IP address, I then send a packet to your correspondents' computers, telling them that your attachment point to the network (we call it a Care-Of Address), has actually moved to the IP address of my laptop. All of the sudden, your ICQ sessions go dead, and meanwhile I am listening to your girlfriend whisper sweet nothings over the voice chat which I have stolen.

Well, that would obviously be a bad situation, and besides the frustration of losing all the traffic which has been diverted, you would want to avoid getting in hot water for hanging up on your friends. So there has to be a way for you to prove that you really own the IP address that you are registering at all the base stations between Cologne and Brussels. Even if these access points have never heard of your cell phone before, they have to have a way to trust that it's really you that's moving around. In today's fixed Internet, this is not much of a problem - if a packet destined to you shows up on your network, it's pretty much assumed that you have the right to receive it.

But when devices start moving around, and bringing their little corner of the Internet with them, things get a bit more complicated, and we have to be sure that you're really authorized to carry that address along with you. So that's what we've been working on lately. Once those last few security issues are solved, the draft will be pretty much ready to release out into the wild! 

Perhaps the only other technical comments I would add are simply about terminology, so that your readers will understand the parlance when reading our specifications. In Mobile IP, we call your device (whether it is a laptop, mobile phone, or any other IP-capable communicator) a Mobile Node (MN). The MN has a Home Address (HA), which is the permanent address it uses to communicate with the rest of the world. When the MN roams to a foreign network, it gets a Care-Of Address (CoA), which is a temporary IP address used for sending traffic while at that part of the network. The CoA either comes from a Foreign Agent (in MIPv4), or is assigned through stateless address autoconfiguration (as in MIPv6).

Once the MN has a CoA, it then sends a Binding Update (BU) to its HA and all of the Correspondent Nodes (CNs) it is communicating with, informing them to forward all traffic to the CoA until further notice. At that point, the HA begins intercepting any packets that show up on the home network for the MN's home address, and tunneling them to the MN at its current CoA. That's it- pretty simple, huh? :-)

Oliver: Are there already any live systems that are running something suggested by the Mobile IP WG? Telia, for example, recently announced that they have GPRS roaming operational, but I presume this has nothing much to do with Mobile IP, which goes beyond that.

T.J. Kniveton: Yes, actually there has been quite a bit of commercial interest in Mobile IP. Some of the companies that have been named on the Mobile IP mailing list as having deployments are Cisco, IPunplugged, Netseal, Birdstep, Nextel, Sprint, Lifix, and this is just a partial list with many more companies involved. We also have a number of commercial projects here at Nokia that are using Mobile IP.

In research labs, there are very many Mobile IP implementations, including our own MIPv6 prototype with many extensions such as Fast Handovers, Smooth Handovers, Buffering, Context Transfer, Regional Registration, and GSM/SIM Authentication. I'll let you imagine what all of those things do..

Oliver: If all those mobile devices have their IP address, will IPv4 work at any time or will there be some faked solution on the way to IPv6? This seems to be particularly crucial with things like MMS which requires, as of my current understanding, a fixed IP address to work reliably. (Note: IPv4 is the old IP Address standard that makes X addresses available for use while IPv6 has a pool of Y addresses)

T.J. Kniveton: Wow, this could turn into a whole other interview about IPv6! Well, let's just say this: IPv4 addresses are rapidly being used up, and most of them are allocated to the U.S. and Europe. So, there is a lot of interest in the rest of the world for moving to IPv6. For instance, China has only been allocated about 9 million IPv4 addresses, which is a very small amount considering their population. It is clear that IPv4 can not serve everyone indefinitely. Japan has been a real leader in embracing IPv6, and their government is mandating companies to start using IPv6.

We believe that it is important for mobile devices to be reachable on the Internet, in the same way that your phone can be dialed from anywhere in the world from any other phone, simply by punching in your number, and your desktop computer is probably accessible from any other point on the Internet, at least while you are connected. For true global reachability to happen, it really looks like IPv6 is an important technology. The expanded address space of IPv6 allows everyone in the world the opportunity to have abundant addresses for all their mobile (and fixed) devices. There are some other properties of IPv6 that make it really a great evolutionary step past today's IPv4 networks. And I guess I should insert a plug here for Nokia, since we have some of the foremost experts in IPv6 on our campuses as well.

Oliver: Mobile IP is supposed to work across media types. Does that mean technologies like UMTS and EDGE, which are supposed to be integrated into one seamless network in the long run anyway, or also GPRS and 802.11b? Does there need to be a relationship between the providers of those services in any case, or not?

T.J. Kniveton: This is a really hot topic right now, and we are looking at it carefully. It is our goal to allow seamless mobility between all different types of access technologies. In the end, that is what's going to make the services on these networks most useful. At this very moment, carriers are spending a lot of time thinking about how they can provide all of these access methods in an integrated fashion so that they are straightforward and simple for you, their customer. Without getting into the technical details, I would just say that Mobile IP should prove very important for the model of how the Internet and mobile services will be delivered in the future.

You may not have thought about cell phone companies and providers being very interested in the Internet before. But with the importance of IPv6 in tomorrow's mobility landscape, a tremendous amount of pioneering work is happening today in the research labs and product development workshops of the mobile phone vendors and service providers.

Oliver: Nowadays, when I move across a border and my carrier changes, my normal voice calls are dropped. Is that just a problem of today, or will Mobile IP not work across different carriers either?

T.J. Kniveton: Of course it will! :-)

Oliver: Thanks a lot for answering my questions in such detail, T.J. For those of our readers who want to really dig down on Mobile IP I would suggest going [here](http://www.ietf.org/html.charters/mobileip-charter.html) for a lot of RFCs on different subjects.


