---
title: Modellierung von Schwingungssystemen mit Machine Learning Unterstützung
summary: Neuronale Netze zur Zeitreihenprädiktion in Bezug auf mechanische Schwingungssysteme
authors:
- dostal
- grossert
- duecker
- seifried
tags:
- Modellierung
- Schwingungen
- Neuronale Netze
- Zeitreihenprädiktion
- TensorFlow/Keras
date: "2020-04-20T00:00:00Z"

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

Die Auslegung schwingungsfähiger mechanischer Systeme erfordert Dauerfestigkeitsbetrachtungen, für die sowohl Belastungsamplituden als auch Belastungsfrequenzen relevant sind. Die Erstellung von Simulationsmodellen, die entsprechende Lastfälle abbilden können, ist daher im Auslegungsprozess solcher Systeme essenziell und wird im Rahmen dieses Projektes untersucht.

Ein Beispiel für die bestehende Problematik ist durch das Aufkommen elektrisch betriebener Autos gegeben. In diesen Fahrzeugen stellt die Batterie, im Vergleich zu Fahrzeugen mit Verbrennungsmotor, eine neue Komponente dar. Diese hat aufgrund ihres im Verhältnis zur Fahrzeugmasse hohen Eigengewichts einen erheblichen Einfluss auf das fahrdynamische Verhalten von E-Autos. Das wird besonders bei der Betrachtung der Vertikaldynamik solcher Fahrzeuge deutlich. So treten bei periodischer Anregung des Fahrzeugs durch Überfahren einer Waschbrettstrecke Schwingungsfrequenzen auf, die weit über der eigentlichen Anregungsfrequenz liegen, welche sich aus der Fahrzeuggeschwindigkeit und der Streckenbeschaffenheit ergibt. Eine solche Charakteristik ist mit herkömmlichen Fahrzeugmodellen meist nicht ausreichend abzubilden.

Dieses Projekt fokussiert sich auf die Synthese von Modellen zur Abbildung des beschriebenen Systemverhaltens aus gemessenen Daten. Dabei werden künstliche Neuronale Netze genutzt, insbesondere sogenannte LSTMs. LSTM steht für "Long Short Term Memory" und bezeichnet eine Klasse neuronaler Netze, die sich durch zusätzliche innere Zustände von herkömmlichen neuronalen Netzen unterscheiden. Aufgrund ihrer Struktur sind sie gut für die Prädiktion von Zeitreihen geeignet, bei denen ein neuer Wert auf Basis der vorangegangenen Werte berechnet wird.

LSTMs können sowohl alleinstehend als sogenannte Black-Box-Modelle als auch in Kombination mit anderen Modellen verwendet werden. Der Vorteil bei der zweiten Variante liegt darin, dass sich für das ergänzende Modell eine Struktur vorgeben lässt, welche weiterführende Betrachtungen erlaubt. Denkbar sind in genanntem Beispiel vor allem Mehrkörpermodelle, welche die Berechnung von Lagerkräften oder Beschleunigungen an beliebigen Orten der modellierten Körper erlauben. In Kombination mit neuronalen Netzen sollten sich solche Werte durch Interpolation besser den Werten am realen System annähern.

Einen anderen Ansatz zur Lösung des beschriebenen Problems stellt die direkte Integration von Neuronalen Netzen in gegebene mechanische Modellstrukturen dar. Hierbei lassen sich theoretisch kleinere Neuronale Netze verwenden, welche als Funktionsapproximatoren nur Teile der Gesamtdynamik des betrachteten Systems abbilden. Ein solcher Ansatz führt zu Parameteroptimierungsproblemen von dynamischen Systemen, welche mit herkömmlichen Methoden gelöst werden können.
