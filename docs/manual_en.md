Manual for Developer Version
============================

Author: Själe
Translator: Matthew Forrester

Foreword

Please always have in the back of your mind that this is a developer version. It's also far from perfect and many things are still missing. But we try to make sure that you always have playable software.

For this we're dependent on your help. Tell us about mistakes, make suggestions, discuss with us whether the game makes sense or not, and lend a hand, if you have the skills to contribute. It's also great to motivate ourselves by chatting in the forum:

http://www.gamezworld.de/phpforum/

At the moment the game is playable as an endless game. The AI works, but it's not yet in it's final state.

At the end of the manual there's a list of keyboard shortcuts for this developer version.


Contents
========

* Loading and Saving
* Spielgeschwindigkeit
* Bewegung der Spielfigur
* Funktionsfähige Features:
    * Programme Planning
    * Archive
    * Movie Agency
    * Werbemakler
    * News Studio
    * Senderkauf
    * Drehbuchagentur
    * Studio
    * Supermarket
    * Chef-Kredit-Bettelei
    * Terrorist
    * Immobilien-Makler
    * FSK 18 und Gerichtsvollzieher
* Interface
* Chat und Cheaten
* Abläufe im Hintergrund
* Veränderungen durch den Spieler
* Keyboard Shortcuts for the Developer Version

Loading and Saving
==================

There are two ways to save and load the game. On the one hand, you can open up the appropriate menu by pressing the "Escape" key. By left-clicking on the respective menu entries you can get to the corresponding sub-menu. When saving, enter a name; when loading find a savegame and select the appropriate entry.

On the other hand, there's also the possibility of quick-saving and -loading. Simply press these keys:

* Quick Save - "F5" key
* Quick Load - "F8" key

Game Speed
==========

You can change the game's speed with the "up" and "down" arrow keys. There are also preset speeds. For this, see the end of the "Keyboard Shortcuts for the Developer Version". The "left" and "right" arrow keys alter the game speed and the movement speed of the in-game characters.

Movement of In-Game Characters
==============================

Basically your avatar will always go wherever you left-click with the mouse pointer. Obviously that depends on whether it's possible. If you click on a door or another interaction object, then the in-game character will try to move there. If a room is occupied, then the avatar will stop in front of it.

Inside the rooms, actions are usually triggered by left-clicking. Clicking on the right mouse button leaves the current menu or the room in which you are located.

The "Esc" key will call up a menu that allows you to save the game, to terminate it or to reload.

Before you really get started it is recommended to save the game at the beginning and wander through the building. You may discover the noticeboard with the names of all those who laboured to make this free gaming experience possible for you.


Functionality and Features
==========================

The basic things are explained in a video:

https://www.youtube.com/watch?v=9reFu18PIJg

Tom.io introduces the game with an (almost) complete explanation:

https://www.youtube.com/watch?v=LaXdh_o3HA4

For those who like to read the full story, or who have used up their data allowance, it will be briefly described below.

Programme Schedule
------------------

To get to the Programme Schedule, you must first enter the player's office. Left-click on the door or select it in the elevator plan and your in-game character will move there. In the office, there's a computer. Left-clicking on this will present you with the Programme Schedule.

You will see the furst day. At the beginning of the game the Opening Ceremony and three advertisements are already in place. In addition, an advertisement has been scheduled as an infomercial. This is only the case at the beginning of the game and should give you enough time to explore the game in peace.

As long as the programme or advertisement blocks are coloured grey, then you can move them to other broadcast slots. Other colours mean that they are already being or have been  broadcast. Red fill on a advertising block that has been broadcast means that it did not reach the required viewership.

Moving the mouse pointer over a programme or an advertisement displays a tooltip containing information about the selected programme.

To move a programme/advertisement simply left-click on it, then the programme hangs on the mouse pointer. To drop it in, left-click again.

If you want to place your (even already broadcast) programmes/advertisements in another slot, press the "Ctrl"-key and then left click. The existing broadcast stays where it is; the duplicate hangs on your cursor and can be placed in the current location with a fresh left-click.

If you want to place individual episodes of a series in sequence, press the "Shift"-key and left-click on it. As long as the "Shift"-key is pressed, then every left-click will place an episode.

If you place an advertisement in a schedule slot, then it becomes an infomercial. These receive a certain amount of money per viewer. But they also damage your image with the viewers.

By contrast, if you set a programme in an advertising slot, then a trailer for the appropriate programme is created. This trailer ensures that more viewers will watch the programme. However, the number of additional viewers depends on how many viewers saw the programme before the trailer. Multiple broadcasts strengthen this effect, though only up to an upper limit. Every further trailer then draws no additional viewership.

If youwant to see or change the schedule for the following, next-but-one or next-but-two day, or even further in the future, then use the the little arrow in the top right. Obviously you can also go back again.

Available advertisements and programmes can be seen in the respective menu options on the right. There are also more tooltips here when you move the mouse pointer over the programme/advertisement. Left-click to drag the programmes. Left-click to put them down again. "Shift" and left-click retains the programme as long as you have the "Shift"-key pressed. If necessary, a right-click will give you a free hand again.

You will also find the "Finance", "Statistics" and "Achievements" items on the right of the Programme Schedule. Left-clicking on them opens the corresponding screens, which will show you more detailed information.

Archive
-------

In the archive you meet the archivist. You needs him, if you want to sell the film that you own. Click on the archivist and you will be shown a list of the genres. If you own films of a certain genre, then it is coloured black, with green lines next to it, which indicate the number of films under ths genre. So click on a genre and select the film that you want to move to the film rental shop, click on it and place it in the suitcase.

But beware! If you put a film which is currently set in the Programme Schedule into the suitcase and leave the room with it, then it will be deleted from the Programme Schedule. So you will have to fill that gap again later.

Movie Agency
------------

This is used for the acquisition and sale of films. On the left you can see the agent behind his desk. On the right there's a bookcase. In the centre is your suitcase. If you have come straight from the archive, it may contain the films that you've selected to sell. If you want to sell them, left-click on them and click on the movie agent with the film. Then the film is gone. But whether it will turn up in the bookcase again is uncertain.

Turning to acquisition, there are two methods. The first one is the films in the bookcase. Move the mouse pointer over the slipcases and it will bring up information about the respective film. The price, course. It states whether or not you can afford it. More important for the audience ratings, however, are the bars for Speed, Box Office and Critics. And also the Topicality. This descreases with every broadcast. And with it the monetary value of the film. If the film isn't broadcast for a while, the Topicality will return to a certain level.

How the films' attributes are to be assessed, described by STARSCRazy:

"Speed: How interesting the film is to Joe Bloggs (affects viewer ratings).

Criticism: How interesting the film is to critics (affects critic ratings).

Box Office: How successful the film was at the box office.

For all three values: the higher the better.

But each has some values that are more important than others, according to their genre:

* Criticism is especially important when it comes to Culture, Live, Music, and Shows.
* Speed is important in Erotic, Sport, Gossip, pay-TV
* Box Office matters for Action, Sci-Fi, Fantasy, Comedy, Romance"

Click on a film, move it over the suitcase and click once more, then it will land in the suitcase. That's only a pre-selection though. Although the money is immediately deducted, if you click on the film again and move it to the bookcase, and click there again, it's placed in the bookcase and the money is back in your account. But if you leave the room with the film in the suitcase, then the film unavoidably ends up in the archive and is automatically available for your programme planning. Should the suitcase be full of films, then leave the room, re-enter it and you will have enough space to go shopping again. By the way: the gaps opened by your purchases will have been filled by the agent in the meantime.

The second way to acquire films here is by auction. For this, click on the auctioneer's hammer on the agent's desk. This displays a menu with films and their respective minimum bids. Mouse over it to display the information about the film again. Click on it and you have made an offer. The money is immediately deducted from your account. If no other player has bid by midnight, then the film automatically lands in your archive and stands ready for programme planning.


Ad Agency
---------

This is the good fellow who keeps the wolf from the door. Now he actually wants to flog us the stuff which ruins the film for the viewers or gives them a chance to get crisps. In a nutshell: here are the commercials which are carefully broadcast each hour and keep the cash rolling in. You can see folders on the table and by the wall and another suitcase in the top right corner. There are usually folders in this case. Those are the previously agreed advertising contracts. The game donates the three there at the start of the game. That the three folders are placed only in the suitcase and not anywhere in the archive should let you know that the spaces in the suitcase are limited. If the suitcase is full, then you can't sign new advertising contracts. You can only free up space once your adverts have finished broadcasting. Or if they pass the time limit, which, however, results in a penalty.

Move the mouse point over over the folders and you'll see information about the relevant advert. I don't need to explain the payout any further. The penalty is due if you don't broadcast the required commercials in the specified time with the required viewers. The tooltip also shows you how many times the advert has already been scheduled and broadcast.

Here, too, the gaps that have been torn will be filled again after leaving the room. So head straight back in to see if something cheap has come up.

There is a separate icon on the bottom left of the window. Move the mouse pointer over it and a menu pops up where the advertising contracts can be sorted by viewing figures or payout.

Please don't complain too much that the advertising payments are not yet balanced correctly. This is an open field and not so finished either. But we're working on it.

News Studio
-----------

In the News Studio is produced, as you'd expect, the news. You can see the newsreader's booth on the right. That's just there to look good.

On the left are five coloured boards with different symbols attached. You can adjust the subscription levels there. The tooltip shows you which symbol belongs to which genre. The subscription levels differ in the time delay with which you receive the news. At 0 you don't receive any news in this genre. At 3 you receive it immediately, as soon as it's released. Likewise, subscription level 0 costs nothing, 3 costs the most.

The game will also add news bit by bit, as allowed by the predetermined level of delay. The news can entice viewers from other stations, who can then also watch the other programmes on your channel. Something to watch out for is that the billing level is always based on the highest one which was set that day. So it's worth switching down just before midnight. 
You don't need to worry if you switch through the levels. The financial change takes effect after a few seconds.

If you click on the pinboard, then you come to the actual centrepiece: the supply of news - on the left - and those selected for transmission - on the right.

Wie üblich auf die zu platzierende Sendung linksklicken und sie an den Platz bewegen, wo sie hin soll. Die zuvor dort gelegene habt Ihr dann an der Hand. Legt sie per Linksklick in der Auswahlliste, an einem anderen Sendeplatz ab oder entsorgt sie per Rechtsklick. In letzterem Fall steht sie dann aber nicht mehr zur Verfügung.

Da die Nachrichten eine eigene Einschaltquotenberechnung besitzen, könnte es schon interessant sein, da einige Kombinationen auszuprobieren. Es ist durchaus möglich, die Nachrichteneinschaltquote höherzupushen als die der vorangegangenen Sendung. Was der nachfolgenden Sendung dann wiederum mehr Zuschauer bescheren kann. Zudem reagieren die verschiedenen Zuschauergruppen verschieden auf verschiedene Nachrichten. Aber das findet selbst heraus. Auch die Reihenfolge der gesendeten Nachrichten hat einen Einfluss.

Senderkauf
----------
Da sind wir freilich bei einem der strategisch wichtigsten Features. Nutze ich das Geld erstmal für den Senderausbau oder für bessere Filme? Zu finden ist das Menü für den Senderkauf per Linksklick auf die Landkarte ganz rechts am Rand.

Wenn Ihr dann auf ?�Sendemast kaufen?? klickt, erscheint an der Maushand ein Sendemastsymbol, das Ihr über die Karte bewegen könnt. Dabei wird Euch angezeigt, wieviele Zuschauer Ihr an der jeweiligen Stelle erreichen könnt. Dazu wird auch immer ausgewiesen, wieviele neue Zuschauer Ihr im Einzugsbereich habt. Das wird wichtig, wenn in Ballungszentren mehrere Sendemasten stehen, die sich gegebenenfalls überschneiden könnten. Da zählt dann freilich jeder mögliche Zuschauer nur einmal. Nicht zu vergessen in der untersten Zeile der Information: Der zu erwartende Kaufpreis.

Habt Ihr eine passende Stelle für den Masten gefunden, fixiert ihn per Linksklick und bestätigt mit dem Button ?�Sendemast kaufen??. Wollt Ihr nach dem Platzieren doch lieber nochmal gucken, dann könnt Ihr den Sendemast per Rechtsklick wieder entfernen. Habt Ihr den Button ?�kaufen?? schon angeklickt, ist es dafür freilich zu spät. Ihr könntet jetzt den Sendemast wieder verkaufen. Wählt Ihn dazu in der Liste rechts unten aus. Und dann auf den Button ?�Sendemast verkaufen??. Gemeinerweise erhaltet Ihr weniger Geld zurück, als er gekostet hat.

Die Menüpunkte am unteren Rand ?�Kabelnetzanbindung?? und ?�Satellitenanbindung?? geben den möglichen Zugriff auf vorhandene Kabelnetze und Satelliten an. Während die vorhandenen Satelliten aufgelistet werden, werden die verfügbaren Kabelnetze durch Überfahren der Landkarte angezeigt. Wenn Ihr die angegebenen Bedingungen erfüllt, könnt Ihr die Anbindungen mieten. Vorgesehen ist jeweils eine einjährige Vertragslaufzeit. Die Abdeckung von Kabel oder Satellit ist an die realen Daten angelehnt. Es ist also nur eine teilweise Abdeckung der Gebiete zu erwarten. Diese steigt jedoch im Laufe des Spiels.

Für alle drei Sendearten wird die Zuschaltung der Reichweite zur nächsten vollen Stunde ermöglicht.

Drehbuchagentur
---------------

Hier könnt Ihr Drehbücher für die Eigenproduktion kaufen. Die stehen auf und neben dem kleinen Schrank an der Tür. Drüberfahren mit dem Mauszeiger lässt Datenblätter erscheinen, auf dem die entsprechenden Informationen nachgelesen werden können. Klickt auf das gewünschte Drehbuch und legt es im Koffer durch Loslassen der linken Maustaste ab. Sobald der Raum verlassen wird, nennt sich das gewählte Drehbuch Euer Eigen.

Studio
------

Mit dem ausgewählten Drehbuch geht es ins Studio. Klickt dort auf das gewünschte Drehbuch im Koffer und legt es rechts auf dem Schränkchen ab. Links steht der Studioleiter. Linksklickt auf ihn und es erscheint ein Dialog, in dem Ihr eine Einkaufsliste fordern könnt. Diese erscheint nach Linksklick auf ?�ich brauche eine Einkaufsliste...?? mittig am unteren Rand. Die kann dann da hängen bleiben. Und ab geht's zum Supermarkt.

Vom Supermarkt zurück, könnt Ihr einen Film mit vollständiger Einkaufsliste zur Produktion freigeben. Wählt dazu den gewünschten Film und klickt auf den Studioleiter.

Supermarkt
----------

Betretet den Supermarkt und es wird ein Dialog angeboten, der zum Einkauf eines Betty-Geschenks oder dem Prozedere der Filmproduktionsvorbereitung führt.

Betty-Geschenke interessieren nur Betty oder eben nicht. Probiert selber aus, ob Eure Einschätzung ihres Charakters der Spielrealität entspricht. Hier kommt weiter nix dazu.

Wählt also die Filmproduktion. Im nächsten Bildschirm stehen links oben die Drehbüchertitel für die schon Einkaufslisten angefordert wurden. Klickt den gewünscht an.

Mittig erscheinen jetzt die verschiedenen zu besetzenden Akteursanforderungen (Regisseur, Darstellerin usw.). Klickt diese jeweils an und eine Liste möglicher Personen erscheint. Der blaue Balken symbolisiert grob den zugehörigen Erfahrungsstand. Dieser ändert sich mit weiteren Produktionen. Fahrt mit dem Mauszeigefinger über die Personen und es erscheint für die jeweilige Person ein Tooltip mit den individuellen Eigenschaften. Die eingegrünten Eigenschaften sind besonders nützlich für die zu besetzende Produktion, die eingegrauten eher uninteressant. Wählt für jeden geforderten Akteurstyp eine Person.

Falls die Wahl rückgängig gemacht werden soll, ist dies per Rechtsklick auf die entsprechende Person möglich.

Als nächstes muss im rechten Bildschirmteil noch eine Produktionsfirma gewählt werden. Die gibt es in drei Leveln. Wobei jedes Level seinen Preis und eine Anzahl Produktionspunkte mit sich bringt. Ersterer muss gezahlt werden, letztere können auf die Produktionsschwerpunkte vergeben werden. Oder aber auf das Produktionstempo.

Die Produktionsschwerpunkte sind je nach Genre unterschiedlich gewichtet. Freilich brauch ein Actionfilm eher Stunts, als ein Liebesfilm. Aber das soll nicht im Einzelnen ausgeplaudert werden. Wenn alle Punkte vergeben sind, kann links unterhalb der Gesamtkosten und der Produktionszeit die Planung abgeschlossen werden.

Zehn Prozent der Gesamtkosten werden sofort fällig. Der Rest dann bei Fertigstellung. Über diese wird per Ingame-Nachricht berichtet. Die Sendung ist dann im Programmplaner verfügbar. Für die Zeit der Produktion ist das Studio übrigens nicht betretbar. Per Tooltip an der Studiotür wird über den Zeitpunkt informiert.

Chef-Kredit-Bettelei
--------------------

Das Chef-Zimmer ist rechts neben dem Fahrstuhl auf Eurer Etage. Der ist ein Chef der alten Schule, achtet bitte auf den vorzüglich animierten Zigarrenqualm. Der tut allerdings nicht zur Sache.

Was es hier zu tun oder zu lassen gibt, wird in der Sprechblase angezeigt. Klickt einfach auf das Eurem Anliegen Entsprechende, wobei es sich derzeit ausschließlich um geldwerte Optionen handelt. Zahlt zurück oder nehmt neuen Kredit auf.

Die Kreditvergabe hängt von verschiedenen Faktoren ab. So veränderen nicht eingehaltene Werbeverträge oder Sendeausfälle Chefs Laune, was momentan aber nur Auswirkungen auf den Kreditrahmen hat.

Von Zeit zu Zeit erscheint eine Meldung, daß Euch der Chef sehen will. Er läßt Euch dafür 2 Spielstunden Zeit. Laßt Ihr die Zeit verstreichen, bewegt sich die Spielfigur selbsttätig ins Direktionsbüro. Sie weiß halt, was sich gehört. Durch Linksklick auf die Meldung könnt Ihr den Besuch sofort ausführen.

Desweiteren informiert Euch der Chef über anstehende Sammy-Verleihungen. Wenn Ihr den Wettbewerb gewinnt, winken kleine Preis in Geld oder Boni auf die Einschaltquoten.

Terrorist
---------

Das ist der Mann für's Grobe. Nicht unumstritten sorgt er dafür, daß immer genügend freie Räume im Haus zu Verfügung stehen. Denn freie Räume sind knapp und im späteren Spielverlauf braucht es größere Studios. Das erste, das Euer Eigen ist, hat nur die Größe eins.

Der Terrorist ist eigentlich ein Handlanger der beiden dubanischen Botschaften, die in ständigem Zwist miteinander liegen. Die jeweils andere Seite ist das eigentliche Ziel. Die Terrorgefahr wird im späteren Verlauf mit einer Nachricht angekündigt.

Kurz darauf betritt der Terrorist das Gebäude und geht zur Informationstafel. Da wird Euer Mittun möglich. Denn Ihr könnt die Schilder auf der Informationstafel vertauschen. Hängt nun das Schild der Botschaft des Landes, das als Ziel für einen möglichen Angriff in den Nachrichten erwähnt wurde, an eine beliebige Stelle und der Terrorist wird seine Schritte dorthin lenken. Wenn Ihr sehen wollt, was passiert, fahrt einfach mit.

Die KI könnte übrigens das jeweilige Botschaftsschild auch auf Eure Büros oder Studios platzieren.

Immobilien-Makler
-----------------

Dieser nette Mensch ermöglicht Euch die Anmietung neuer und eventuell größerer Studios. Auf die Pinwand links geklickt und es erscheint der im Haus belegten Räume. Etwas hervorgehoben sind die potentiell anmietbaren. Ein Tooltip enthält die jeweiligen derzeitigen Mieter und die Studiogröße. Letztere hat im Moment noch keinen Einfluss auf die Eigenproduktion.

Wie Ihr die Mieter überzeugen könnt, ihre Räume aufzugeben, lernen wir später.

FSK 18 und Gerichtsvollzieher
-----------------------------

Filme mit dem Hinweis FSK 18 dürfen laut den Jugendschutzgesetzen im TVTower-Land nicht zwischen 6 und 22 Uhr gesendet werden. Es bleibt Euch jedoch überlassen, ob Ihr Euch daran haltet. Allerdings hat die Sache einen Haken. Oder besser zwei. Die Behörden können schon in der Programmplanung erkennen, daß Ihr vorhabt ein Gesetz zu unterlaufen. Daraufhin wird eine Strafzahlung fällig und der Film wird aus dem Programmplaner entfernt. Die Lücke müßt Ihr dann wieder füllen.

Habt Ihr es geschafft, den Film unbemerkt an der Zensur vorbeizuschmuggeln, gibt es nach der Ausstrahlung immer noch eine 25%ige Chance, daß einer der beiden Gerichtsvollzieher (Mr. Czwink und Mr. Czwank) erscheint. Da sie sich nicht so gut auskennen im TVTower, informieren sie sich ganz wie der Herr Terrorist an der Informationstafel. Vertauscht die Archivschilder zweckdienlich und ein Film der Konkurrenz könnte beschlagnahmt werden. Wurde ein Film beschlagnahmt, so erhaltet Ihr eine Meldung darüber.

Wie im wirklichen Leben verringern die FSK18-Ausstrahlungen zur falschen Zeit das Image. Derzeit um 0.5 Prozentpunkte.

Interface
=========

Das meint hier den unteren Teil des Spielbildschirms, der Euch durch das gesamte Spiel begleiten wird. Links ist der Fernseher, der das laufende Programm der einzelnen Sender anzeigt. Den könnt Ihr ausschalten. Desweiteren könnt Ihr über die farbigen Tasten auswählen, welchem Sender Ihr ins laufende Programm schauen wollt.

Bewegt Ihr den Mauszeiger über den Bildschirm oder die Tasten der anderen Sender, erscheint ein Tooltip mit Informationen zum laufenden Programm. Wenn Ihr die Maushand auf dem Bildschirm platziert, wird angezeigt, welcher Film mit welcher Einschaltquote läuft. Zusätzlich bei Eurem eigenen Sender ein Hinweis, ob ein passender Werbeblock gesetzt ist.

Die anderen Anzeigen sind zu Eurer Information gedacht.

Der rechte Bildschirm zeigt die jeweiligen Zielgruppen, die vom Programm bevorzugt erreicht werden. Die Anzeigen in der Mitte sind ja dank der Tooltips selbsterklärend.

Chat und Cheaten
================

Der InGame-Chat wird mit der ?�Enter??-Taste aufgerufen. Der Chat kann in der Entwicklerversion verschiedene Kommandos entgegennehmen. Der Befehl ??/dev help?? listet die verfuegbaren Befehle auf. So würde zum Beispiel ein ??/dev money 1 1000?? dem ersten Spieler 1000 Euro aufs Konto gutschreiben.

Abläufe im Hintergrund
======================

Zu den Abläufen im Hintergrund gehört zum Beispiel die Einschaltquotenberechnung. Hier soll im Moment noch nicht viel erklärt werden. So ist es sicher leichter, daß Ihr auf Ungereimtheiten aufmerksam werdet und sie uns gegebenenfalls mitteilt. Da die meisten, die uns in den Weiten des Netzes finden, erfahrene Spieler und Spielerinnen sein dürften, ist die Intuition ein nicht zu unterschätzender Faktor zur Verbesserung des Spiels.

Und wir wollen die Ungereimtheiten nicht durch schlaue Wichtigkeiten schon im Vorhinein wegreden.

Veränderungen durch den Spieler
===============================

Im Spieleverzeichnis liegt ein config-Ordner. In diesem wiederum gibt es eine Datei ?�settings.xml??. Diese enthält eine Menge Sachen, die per Editor verändert werden können. Wenn Ihr in den ?�Einstellungen?? etwas verändert, was von den Vorgaben abweicht, wird eine ?�settings.user.xml?? angelegt - in dieser können auch händische Abaenderungen stattfinden, die vormals in der ?�settings.xml?? zu hinterlegen waren.

Kurz: die settings.user.xml enthält die  Abweichungen zu den vorgesehenen Einstellungen aus settings.xml

Tastenkürzel für die Entwicklerversion
======================================


Spielgeschwindigkeit
--------------------
* Cursor Hoch/Runter : Spielgeschwindigkeit +/-
* Cursor Links/Rechts : Laufgeschwindigkeit und Spielgeschwindigkeit +/-
* Strg Links + Cursor Rechts: Schnellvorlauf Stufe 1
* Strg Rechts + Cursor Rechts: Schnellvorlauf Stufe 2
* 5 : Spielgeschwindigkeit 60 Spielminuten/s
* 6 : Spielgeschwindigkeit 120 Spielminuten/s
* 7 : Spielgeschwindigkeit 180 Spielminuten/s
* 8 : Spielgeschwindigkeit 240 Spielminuten/s
* 9 : Spielgeschwindigkeit 1 Spielminute/s (Standard)

Raeume
------
* W: Werbemakler
* A: Archiv
* B: Betty
* F: Filmagentur
* O: Buero/Office
* C: Chef
* N: Nachrichtenstudio
* R: Raumvermietung / Makler
* Strg + R: Roomboard / Raumplan
* L: Supermark / Laden
* S: Studio (erstes gefundenes)
* Strg Links + S: Supermarkt
* Strg Rechts + S: Drehbuchagentur (Scripts)
* E: Credits (employees :-))

Laden/Speichern
---------------
* F5: Spielstand speichern (Quicksave)
* F8: Spielstand laden (Quickload)

Sonstiges
---------
* 1-4: Spieler wechseln (mit Observermodus nur Spieler beobachten)
* Strg Links + O: Observermodus an/aus
* G: Geister-Modus (frei mit Maus durch Hochhaus scrollen) an/aus

* TAB: Dev-/Debugpanel ein-/ausblenden
* Strg Links + TAB: Raumspezifische-Debug-Ansicht an/aus
* Q: Quoten-Debugbildschirm an/aus
* K: ALLE Figuren werden aus den Raeumen gekickt
* T: Terroristen losschicken

* F1: Spielanleitung oder wenn verfügbar Raum-/Bildschirmspezifischen
Hilfe anzeigen
* F6: Musik spielen
* F10: Alle Fremdfiguren de-/aktivieren (Bewegungen)
* F11: KI an/aus

* M: Musik/Soundausgabe an/aus
* Shift+M: Soundeffekte an/aus
* Strg+M: Musik an/aus
