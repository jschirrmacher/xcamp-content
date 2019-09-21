---
title:      DevOps - was soll das?
authorPage: joachim-schirrmacher
published:  17.07.2018
image:      media/Universal_Tile_XCamp18_Kali_Dev_Ops-1.png
tags:       XCamp2018, Sessions
---

In Entwicklungsprojekten höre ich in letzter Zeit immer wieder von “DevOps”. Was ist das eigentlich und wem nützt es?

Im Aufzug meinte ein Kollege neulich, “die wollen, dass wir jetzt nicht nur die Software entwickeln. Nun sollen wir auch noch rund um die Uhr Support leisten. Wie soll das überhaupt gehen? Da geht doch spätestens der Betriebsrat auf die Barrikaden”.

Was genau soll DevOps eigentlich heißen? Der Begriff setzt sich zusammen aus dem “Development”, das sich auf die Entwicklung von Software bezieht und “Operations”, das für den Betrieb dieser Software steht und bisher in der Regel von einem separaten Team übernommen wird.

Werden die Kollegen, die sich bisher um den Betrieb der Software gekümmert haben, arbeitslos? Nein, so wird es wohl nicht kommen. Wir sprechen statt dessen von “Cross-funktionalen Teams”. Die Ops sollen also mit den Devs zusammen arbeiten und schon früh im Entwicklungsprozess dabei sein. Lernen, was überhaupt schief gehen kann und darauf hin arbeiten, dass es nicht dazu kommt. Oder dass sich die Software im Idealfall selbst heilt. “Resilienz” ist das entsprechende Wort dafür.

##Sicherheit durch Automation und Entkopplung
Und ja, tatsächlich, die modernen Architekturen mit Micro-Services und entkoppelten Komponenten helfen dabei; sie unterhalten sich über definierte Schnittstellen miteinander.  Auch die Cloud mit ihrer mehr oder weniger inhärenten Ausfallsicherheit sorgt dafür, dass nicht unbedingt jemand manuell eingreifen muss, wenn mal was schief läuft. Wichtig ist natürlich, dass das gleich bei der Entwicklung berücksichtigt wird.

Continuous Integration mit automatisierten Tests geben dem gesamten Team die Sicherheit, dass neue Features keine bestehenden stören. Sie führen dazu, dass sehr kurzfristig, im Extremfall jederzeit eine neue Version ausgeliefert werden kann (Continuous Deployment). Da die Änderungen im Vergleich zu früheren Software-Releases nur sehr klein sind, ist für die Nutzer beim Versionswechsel kein Umlernen notwendig, eine kurze Information reicht in der Regel aus, um das neue Feature verwenden zu können. So wird nicht nur die Geschwindigkeit erhöht, mit dem Nutzen geschaffen wird, es gibt auch schnelleres Feedback, von dem die Weiterentwicklung profitiert.

Das alles passt ja von den Ideen sehr gut mit den agilen Prinzipien zusammen, mit denen wir uns unter Anderem auch beim XCamp beschäftigen. Aber es gibt noch mehr hier diskutierte Themen, die DevOps miteinander verbindet und in Einklang bringt.

##DevOps ist mehr als das
DevOps ist auch eine Sichtweise. Sie hängt sehr stark mit dem Blick auf Produkte zusammen. Im Gegensatz zu Projekten, die ja per Definition zeitlich begrenzt sind: ein Kick-Off, bei dem die Ziele und Anforderungen definiert und kommuniziert werden, ein Abschluss, bei dem die fertige Software (an den Betrieb) übergeben wird, dann noch eine hübsche Abschlussfeier (sofern alles geklappt hat) und dann auf zum nächsten Projekt.

DevOps geht da weiter: Von Anfang an wird die erstellte Software als Produkt verstanden, das es im Laufe seines gesamten Lebens zu warten gilt, zu dem Nutzer geschult und bei Problemen unterstützt werden. Und das auch weiter entwickelt wird, denn es kommen ja – wenn die Software wirklich benutzt wird – kontinuierlich neue Anforderungen und Ideen auf, die es umzusetzen gilt. Wir brauchen auch die Entwickler auf Dauer, sie können nicht einfach zum nächsten Projekt weiter ziehen.

##DevOps erfordert Umdenken
Das passt ganz gut zusammen mit dem Gedanken, dass es in der Produktentwicklung ja darum geht, dem Nutzer möglichst großen Nutzwert und Bedienkomfort zu liefern. Was das im Detail ist, wissen wir nur meist noch nicht vor dem Start des Projekts (wenn bisher meist die Anforderungen aufgenommen, das Projekt ausgeschrieben und ein Anbieter ausgewählt wurde). Wir lernen statt dessen während der Entwicklung und wir lernen weiter während die Nutzer tatsächlich mit dem Produkt arbeiten.

Insofern umfasst DevOps auch Dinge wie User Experience, bei dem es darum geht, den Nutzer genau zu beobachten. Es greift aber sogar in die vorherrschende Vertragsgestaltung ein. Es wird mit DevOps nicht mehr sinnvoll möglich sein, Werkverträge zu schließen. Aber auch Dienstverträge im Sinne von “leih’ mir mal ein paar Entwickler für soundsoviele Wochen” sind damit kontraproduktiv.

Die Beziehung von Auftraggeber und Software-Entwickler muss für erfolgreiches DevOps enger werden: Es muss gemeinsam ein Produkt definiert, entwickelt, weiterentwickelt und betrieben werden. Eine Zusammenarbeit über Jahre, wenn es gut läuft. Wenn alle Beteiligten sich mit ihrer Aufgabe, ihrem Produkt identifizieren und ein Interesse daran haben, dass es nicht nur fertig wird, sondern dauerhaft funktioniert und den Nutzern Werte bringt, kann das gelingen. Ein Joint-Venture.

##Conclusio
DevOps versteht Software also als ein Produkt mit einem Lebenszyklus. Das cross-funktionale Team begleitet dieses Produkt von seiner Entstehung, führt mithilfe von kreativen und agilen Methoden größtmöglichen Nutzen für die Anwender herbei. Dabei ermöglicht, aber fordert auch kontinuierliches Lernen des Teams, was den tatsächlichen Nutzen ausmacht. Es fördert darüber hinaus, dass das Produkt mit möglichst geringem Aufwand betrieben werden kann und nur ein geringer Wartungs-, Migrations- und Schulungsaufwand entsteht, indem es alle Beteiligten ins gleiche Boot holt, da alle am Erfolg und Misserfolg beteiligt sind.

In gewisser Weise führt DevOps damit alle hier beim XCamp diskutierten Methoden und Prinzipien zusammen. Wer über meine praktischen Erfahrungen mit DevOps bei der DB Systel mehr wissen oder seine eigenen Erfahrungen teilen will, lade ich in meine Session beim diesjährigen XCamp ein.
