---
title: Bestärktes Lernen im industriellen Internet der Dinge
summary: Anwendung von Techniken des bestärkten Lernens im MAC-Protkoll IEEE 802.15.4 DSME
authors:
- turau
- meyer
tags:
- Internet der Dinge
- Eingebettete Systeme
- Kommunikationsnetze
- TensorFlow
date: "2020-06-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---
Im Verlauf der letzten Jahre erfreuten sich drahtlose Übertragungstechnologien zunehmender Beliebtheit in industriellen Anwendungen und ersetzen vermehrt kabelgebundene Kommunikationsnetze, da sie kostengünstiger und häufig einfacher einzusetzen sind. Diese Entwicklung bezeichnet man gemeinhin als industrielles Internet der Dinge (IIoT). Anwendungsszenarien reichen von der simplen Erfassung von Sensordaten bis zur Echtzeitsteuerung von Aktuatoren über das Netzwerk. Ein MAC-Protokoll, dass speziell für den Einsatz in diesen industriellen Anwendungen mit tausenden von Sensorknoten entwickelt wurde ist IEEE 802.15.4 DSME. Es bietet ein Zeit- (TDMA) und Frequenzmultiplexverfahren (FDMA) um eine energieeffiziente und skalierbare Übertragung zu gewährleisten.

In diesem Projekt soll untersucht werden, wie maschinelles Lernen genutzt werden kann um verschiedene Aspekte der Datenübertragung mittels IEEE 802.15.4 DSME zu optimieren. Besonders interessant sind dabei unter anderem die Auswahl geeigneter Übertragungskanäle unter dem Einfluss von externen Störungen als auch die Zuweisung von Zeitschlitzen für die Übertragung von Datenpaketen. Die Allokation dieser Zeitschlitze erfolgt in DSME verteilt, wird also nicht von einem einzigen Rechner koordiniert, weshalb die optimale Zuordnung von Zeitschlitzen zu Sensorknoten, z.B. zur Minimierung der Übertragungslatenz, ein kompliziertes Problem darstellt.

Bestärktes Lernen stellt eine attraktive Herangehensweise an diese Art von Problemen dar, da hier - z.B. von einem künstlichen Neuronalen Netz (KNN) - automatisch Lösungen generiert werden, die dann lediglich bewertet werden müssen. Die Bewertung einer Zuweisung von Zeitschlitzen wird dabei einfach durch die Messung der relevanten Metriken, z.B. der Übertragungslatenz, in einem realen Versuchsaufbau oder im Netzwerksimulator OMNeT++ erhalten. Basierend auf der Bewertung lernt das KNN, ob die generierte Zuweisung von Zeitschlitzen gut oder schlecht war und generiert über die Zeit immer bessere Zuweisungen.

Ein weiterer Aspekt des Projekts ist die Anwendbarkeit von maschinellem Lernen auf Ressourcen-beschränkten Geräten. Geräte im IIoT operieren häufig batteriebetrieben und verfügen über wenige kB RAM. Die meisten Geräte basieren auf einer 8/16-Bit-Architektur ohne Fließkomma-Arithmetik, was die Anwendung von maschinellem Lernen erschwert. Ziel ist daher Algorithmen zu finden, die möglichst zeit-, energie- und speichereffizient sind. Dies ist z.B. durch die Kompression von KNNs aber auch durch die Auswahl von leichtgewichtigeren Algorithmen wie Entscheidungsbäumen oder Support Vektor Maschinen möglich.

