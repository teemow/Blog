---
layout: post
title: "Die Zensursula Diskussion"
date: 2009-06-16 18:34
comments: true
categories: Life in General
author: Oliver Thylmann
---






Info: This post is in German as it is Germany focussed and the english speaking crowd can probably ignore it, even though it is an interesting subject.

So. Eigentlich wollte ich ja gar nichts schreiben, aber auf Twitter ist eine kleine Diskussion &amp;uuml;ber [einen meiner Beitr&amp;auml;ge](http://twitter.com/o/status/2193814860)&amp;nbsp;losgebrochen das ich doch mal was schreiben muss. Diesmal sogar auch deutsch auch wenn ich eigentlich nur auf englisch schreibe. Man verzeihe mir die Rechtschreibfehler.

Zuerst zu mir:&amp;nbsp;


* Ich habe DNS Server administriert
* Ich habe Netzwerke aufgebaut
* Ich habe shared hosting system aufgesetzt und betreut
* Ich habe mal eine Porn Seite entdeckt und vom netz genommen die von Deutschland aus gar nicht zu sehen war (filter in Apache auf deutsche IPs)
* Ich habe load-balanced server systeme entwickelt, betrieben, etc.
* Ich habe mit Leuten gearbeitet die _wirklich_ wissen was Sicherheit in Bezug auf Internetseiten bedeutet


&amp;nbsp;Die Liste lie&amp;szlig;e sich noch weiter f&amp;uuml;hren, aber ich denke der Punkt ist gebraucht. In Bezug auf Internet Infrastruktur, Netzwerke, Sicherheit, und verwandte Themen bin ich nicht ganz auf den Kopf gefallen.

N&amp;auml;chster Punkt. [Ibo](http://ibrahimevsan.de/) hat netter weise mal den relevanten Teil &amp;uuml;ber Zensur auf dem Grundgesetzt ins Netz gestellt. Ich zitiere hier auch mal:


(1) Jeder hat das Recht, seine Meinung in Wort, Schrift und Bild frei zu &amp;auml;u&amp;szlig;ern und zu verbreiten und sich aus allgemein zug&amp;auml;nglichen Quellen ungehindert zu unterrichten. Die Pressefreiheit und die Freiheit der Berichterstattung durch Rundfunk und Film werden gew&amp;auml;hrleistet. Eine Zensur findet nicht statt.
(2) Diese Rechte finden ihre Schranken in den Vorschriften der allgemeinen Gesetze, den gesetzlichen Bestimmungen zum Schutze der Jugend und in dem Recht der pers&amp;ouml;nlichen Ehre.
(3) Kunst und Wissenschaft, Forschung und Lehre sind frei. Die Freiheit der Lehre entbindet nicht von der Treue zur Verfassung.


So nett das gemeint war, damit sollte eigentlich Zensur vom Tisch sein. Wenn ich das richtig verstehe, dann sind illegale Materialien von Zensur nicht gesch&amp;uuml;tzt. Siehe Punkt 2.. Das ist eigentlich auch der gr&amp;ouml;&amp;szlig;te Punkt an der Diskussion der mich st&amp;ouml;rt. H&amp;ouml;rt verdammt nochmal auf von Zensur zu sprechen. Das bringt niemandem etwas. Das die Infrastruktur die da gebaut werden soll eventuel auch f&amp;uuml;r Zensur genutzt werden kann ist absolut klar, aber einfach nicht der Punkt. Wir k&amp;ouml;nnen ja nicht anfangen jedes Gesetz so auszulegen, dass es nur da sein darf wenn es bei Fehlinterpretation und Missbrauch illegal ist. Dann k&amp;ouml;nnen wir ja gleich alles aufgeben. Und nach meinem momentanen Wissensstand soll nun eine Kontrollinstanz da sein. Sollte dies nicht der Fall sein muss das erstmal berichtigt werden und das sollte auch jedem einfach klar sein.

An alle die sich so &amp;uuml;ber Zensur aufregen: warum sehe ich keine lauten Schreie &amp;uuml;ber [Real Time Blackhole Lists](http://en.wikipedia.org/wiki/DNSBL)??? Euer email server provider kann das bei sich einbauen und sollte irgendwer auf der Welt sagen ich spamme von meinem Server (oder genauer gesagt irgendwer der meinen Server irgendwie nutzt) dann kommt der Server auf die RBL und meine Mail kommt bei euch nie an und ihr wisst es nicht. Also fangt da mal bitte an zu k&amp;auml;mpfen. Weil Spam ist ja noch nicht mal illegal! Und das muss auch keine unbedingt pr&amp;uuml;fen, ganz besonders kein Staat.&amp;nbsp;

Der Hauptpunkt ist aber der hier: Dieses vorgeschlagene System ist absoluter Mumpitz und bringt gar nichts. Nochmal: Ich glaube nicht an dieses System. Ich glaube nur das Zensur der falsche Angriffspunkt ist. Das Problem mit dem System muss man an guten Beispielen erkl&amp;auml;ren und einfach klar machen und sich nicht in einem Netz von Diskussionen &amp;uuml;ber eine eventuel m&amp;ouml;gliche Zensur verstricken. Auch das Argument das als n&amp;auml;chstes Deep Packet Inspection kommt z&amp;auml;hlt nicht, weil da hat Phorm in UK gezeigt wie das nach hinten los geht.&amp;nbsp;

Also warum ist das ganze denn nun wirklich bl&amp;ouml;d. Es geht nicht, zumindest nicht wirklich. Das wissen aber eigentlich auch schon alle. Da wir aber auch alle wollen, dass Kinderpornographie, bzw. noch viel weiter gedacht, der Missbrauch von Kindern, aufh&amp;ouml;rt und nie wieder passiert, brauchen wir eine L&amp;ouml;sung. Und die Aussage &quot;wir haben ja Gesetze dagegen&quot; kaufe ich nicht ab. Die Digerati wie ich sie mal nennen will sollte doch mal auf eine sinnvolle und effiziente L&amp;ouml;sung kommen. Zumindest eine Diskussion mit Ziel eine L&amp;ouml;sung w&amp;auml;re echt mal interessant.&amp;nbsp;

Viel filesharing l&amp;auml;uft &amp;uuml;ber P2P, IRC, Newsnet, oder &amp;auml;hnliches. Das ist alles raus. W&amp;uuml;rde man hier Namen von Servern sperren, w&amp;uuml;rden auch ganz viele legale Inhalte geblockt werden, was nicht sein darf. Also nochmal: Das ganze geht nicht f&amp;uuml;r die Infrastruktur wo im Moment jeder Internet Nutzer 90% seiner illegalen Downloads her hat (tut nat&amp;uuml;rlich keiner, nur um das auch klar zu machen ;)). Das gleiche gilt ja auch f&amp;uuml;r Webserver wo nicht nur illegale Materialien sind. Dies exkludiert also alle Webseiten die gehackt worden sind, oder die shared hosts sind, also nicht nur eine Webseite hosten.

Also geht es nur um Webseiten wo wir quasi nur Kinderpornographie finden, unter einer Domain, unter der sonst nichts zu finden ist. Als solches ist das ganze ja schon recht unwahrscheinlich. Dann ist aber noch das Problem das man einfach nur seinen eigenen DNS Server austauschen muss und das ganze ist schon wieder vorbei. Oder einen Anonymous Proxy wenn ich das richtig sehe (wei&amp;szlig; im Moment nicht genau ob mein Rechner zumindest den DNS request durchf&amp;uuml;hrt oder nicht).

Jetzt m&amp;uuml;sste man aber mal ein Beispiel bauen, so das das ganze sehr einfach jedem gezeigt werden kann der f&amp;uuml;r oder gegen dieses Gesetz stimmen kann. So k&amp;ouml;nnte man dann einfach jeden Anrufen oder EMail schicken oder Briefe oder mit LCD Monitoren auf dem Auto neben deren Auto her fahren. Was immer auch. Man k&amp;ouml;nnte etwas tun. Zur Zeit der Versteigerung der UMTS lizenzen hat Nokia mal rausgefunden was die Fahrwege sind von den Entscheidern f&amp;uuml;r Netzwerkinfrastruktur bei den gro&amp;szlig;en Mobilfunkanbietern. Dann haben sie einfach diesen Arbeitsweg zugekleistert. Sehr interessant.

Einfach w&amp;auml;re eine Flash Animation mit einem Besuch einer Seite, einem zweiten Besuch mit STOP schild, ein Durchlauf durch &amp;Auml;nderung der DNS Einstellungen, noch ein Besuch der Webseite. Sch&amp;ouml;ner w&amp;auml;re die M&amp;ouml;glichkeit das Live am Screen zeigen zu k&amp;ouml;nnen, also quasi ein Demo am eigenen Rechner (an dem diese Leute wahrscheinlich gar nix &amp;auml;ndern k&amp;ouml;nnen). Auch interessant w&amp;auml;re verschiedene Seiten von Bundestagsmitgliedern so zu manipulieren das dort ein Bild zu sehen ist das dort nicht hin geh&amp;ouml;rt, muss ja nicht illegal sein, so das klar ist das diese ganze Seite potentiell gesperrt w&amp;uuml;rde. Wie schon erw&amp;auml;hnt, denke ich, dass mit ein wenig Kreativit&amp;auml;t da wirklich was interessantes aufzusetzen ist. Es muss einfach _gezeigt_ werden das dies nicht wirklich funktioniert.

Als zweiten Schritt muss dann noch ein weiteres Konzept gefunden werden wie man das Problem bek&amp;auml;mpft, sowohl Kindesmissbrauch als auch Kinderpornographie im Internet. Das ist ganz besonders wichtig weil ja schon klar geworden ist das ein Gro&amp;szlig;teil dessen &amp;uuml;ber dieses System gar nicht beblockt wird. Ich finde hier grunds&amp;auml;tzlich die Idee eines anonymisierten Crowdsourcing Tools zur Meldung, &amp;Uuml;berpr&amp;uuml;fung, Entfernung, Ermittlung, etc... . An dieser Stelle k&amp;ouml;nnte jeder Anonym Informationen einreichen. Diese Daten werden so aufgeteilt das sie nicht zum Ziel f&amp;uuml;hren aber die einzelnen Teile angereichert werden k&amp;ouml;nnen mit mehr Informationen (z.B. &quot;Kontaktdaten zu Hoster von IP adressse X&quot;). Das ganze wird mit API aufgesetzt das jeder sich andocken kann. Auchtung, das ist auch nur eine Idee.

Ich denke ich habe meinen Punkt klar gemacht. Gesetz ist bl&amp;ouml;d. Zensur der falsche Kampf. Ist auch nur meine Meinung, andere akzeptiere ich gerne. Dachte blos das ich das ganze nicht in 140 Zeichen-St&amp;uuml;cken sagen kann ;)

But we need a constructive give examples call constituients and explain why stupid and that we should work together with hackers, police and porn to solve the problem

&lt;script src=&quot;http://ads.adcloud.net/s/129.js&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;


