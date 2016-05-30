---
layout: post
title: "Alles neu: Gateway, Fimware, Protokoll, Karte"
---

Der Freifunk Ostholstein hat seit wenigen Wochen einen weiteren Server.
Der ist schön, kostet allerdings auch soviel wie alle anderen Server zuvor zusammen.
Wir gehen davon aus, dass dessen erhöhte Leistungsfähigkeit uns erlaubt, zwei der älteren
zu ersetzen. Daher wird es (hoffentlich bald) nicht mehr gar soviel teurer, da
auch die Kosten für die Anonymisierung weniger werden.

Die Umstellung war motiviert durch die nun nahende Hauptsaison. Es bereits jetzt
doppelt soviele Teilnehmer wie noch vor zwei Monaten, an Wochenenden noch mehr.
Zudem soll es zu einem Update des in Ostholstein bislang
genutzten B.A.T.M.A.N. Protokolls kommen. Dieses regelt die Kommunikation der
Router und Gateways untereinander, damit beim Spazierengehen die Verbindung
dem Spaziergänger folgen kann. Leider ist der nun anstehende Versionssprung
von 14 auf 15 nicht miteinander verträglich. Dies erschwert das automatische
Update, da nicht alle Knoten direkt am Netz sind. Wenn dann der Knoten am Netz
zuerst auf das neue Protokoll wechselt, so wirkt das auf die Knoten dahinter
wie ein Netzausfall. Für die Teilnehmer ändert sich aber nichts.

Wir wurden gewisserweise bereits auf dieses Szenario vorbereitet: Der Rechner
mit der Karte läuft mit dem noch aktuellen Protkoll kann die Knoten mit dem neuen Protokoll nicht sehen.
Daher gibt es nun als Zwischenlösung eine zweite Karte auf <http://gw6.ffoh.de/meshviewer>. Man 
kann gut erkennen, wie leer es dort noch ist. Man teilt sich damit daher auch
die Bandbreite mit kaum jemanden. Und die Bandbreite ist auch noch größer als
die im bisherigen System. Wer Interesse hat, spreche uns bitte an und update
mit einer Firmware auf <http://gw6.ffoh.de/firmware/v15all_6.1.5/images/sysupgrade/>.
Es scheint, als können die Einstellungen beim Flashen erhalten bleiben. Aber solche Dinge möchten
wir erst noch vermehrt testen, bevor wir das Update für alle vorbereiten können.
