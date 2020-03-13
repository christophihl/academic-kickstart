---
title: Machine Learning für ressourcenbeschränkte eingebettete Systeme
summary: Künstliche neuronale Netze auf kleinen Microcontrollern zur Gestenerkennung.
authors:
- turau
- venzke
tags:
- Eingebettete Systeme
- Objekterkennung
- Künstliche neuronale Netze
- TensorFlow
date: "2020-03-13T00:00:00Z"

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

Nach Jahrzehnten intensiver Forschung hält Machine Learning (ML) zunehmend Einzug in reale Anwendungen. Wegbereiter sind der Fortschritt von Rechensystemen mit enormer Rechenleistung und die Verfügbarkeit großer Mengen von Daten. ML hat ein enormes Potenzial, die Leistungsfähigkeit von Geräten und Maschinen unterschiedlichster Anwendungsbereiche zu steigern. In den nächsten fünf bis zehn Jahren wird ML auch in eingebettete Systeme Einzug halten. Schon heute können solche Anwendungen für Maschinen mit leistungsfähigen Verarbeitungseinheiten (z. B. Industrie-PCs) erstellt werden. Aber kleinere Geräte haben meist nur preiswerte, energiesparende kleine Mikrocontroller. Zwar haben einige Mikrocontroller bereits eine 32-Bit-Architektur, Fließkomma-Arithmetik und Instruktionen für die Vektorverarbeitung. Aber auch 8-Bit-Architekturen ohne Fließkomma-Arithmetik sind noch weit verbreitet. Als RAM-Größen sind zwischen 2 kB und 512 kB typisch. Außerdem werden viele Geräte mit Batterien versorgt. Daher gibt für den Einsatz von ML auf kleinen Mikrocontrollern die große Herausforderung, den Verbrauch von Energie-, Rechen- und Speicherressourcen an die Realität solcher Systeme anzupassen. 

Im Projekt soll daher untersucht werden, wie maschinelles Lernen hauptsächlich in Form künstlicher neuronaler Netze (KNN) effizient auf leistungsschwachen Mikrocontrollern verwendet werden kann. Dabei wird ML für typische Anwendungen eingebetteter Systeme eingesetzt, wie die Auswertung von Sensorsignalen oder die Optimierung der Kommunikation in Sensornetzen. Es wird betrachtet, welche Problemgrößen auf ressourcenbeschränkten Mikrocontrollern welcher Leistungsfähigkeit umsetzbar sind. 

Der Ressourcenbedarf wird durch Kombination unterschiedlicher Ansätze reduziert. So muss das ML-Problem auf das für die Anwendung absolut Notwendige reduziert werden, also z. B. Eingaben vorverarbeitet oder unnötige Eingaben entfernt werden. Verwendete KNNs dürfen nicht zu groß (Anzahl Ebenen, Neuronen, Verbindungen zwischen Neuronen) gewählt werden. Alternativ wird zunächst ein großes KNN trainiert und danach komprimiert. Für Gewichte und Zwischenergebnisse können Bit-Breiten reduziert werden (z. B. Festkomma, binäre- oder ternäre Werte, hierarchische Quantisierung). Teilprobleme, die nicht im eingebetteten System ausgeführt werden müssen (wie Training, Optimierungsläufe, Vorverarbeitung), sollten so weit wie möglich auf ein leistungsfähiges System verschoben werden.

Als erste Anwendung dient ein eingebettetes System, das Handgesten (z. B. Handbewegung von links nach rechts oder von oben nach unten) mit einem KNN erkennt. Es soll in Massenproduktion für einen Preis unter einem Euro produzierbar sein und als Komponente in Geräten verbaut werden. Lichtsensoren in einer 3x3-Matrix dienen als eine Art Facettenauge. Ihre Signale werden im Prototyp von einem Mikrocontroller ATmega328P (8-Bit, 16 MHz, 2 kB RAM, 32 kB Flash-Speicher) verarbeitet. Dazu wird ein KNN ausgeführt, das erkannte Bewegungen in Gesten klassifiziert.
