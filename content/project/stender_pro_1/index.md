---
title: Machine Learning für Automobil-Bremsen und deren Emissionen
authors:
- Merten Stender
- hoffmann
tags:
- Mechanische Systeme
- Objekterkennung
- Neuronale Netze
date: "2021-11-09T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Emission von Bremsgeräuschen als Folge eines Lastkollektivs und Abbildung der multivariaten Zusammenhänge per tiefen rekurrenten neuronalen Netzwerken."
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

Im Rahmen dieses Projekts werden modernste Machine Learning (ML) und Deep Learning Methoden angewandt, um die Emissionen von Bremsstaub und Bremsgeräuschen zu verstehen (Entstehungsmechanismen, Sensitivitäten). Feinste Bremsstäube tragen in urbanen maßgeblich zur gesundheitsschädlichen Belastung der Umwelt bei, während Bremsgeräusche, wie z.B. das Quietschen von Auto- oder Zugbremsen, einen großen Anteil an der Lärmverschmutzung und Stress-induzierter Belastung von Menschen hat.

Bremsen in Fahrzeugen aller Art basieren zumeist auf mechanischer Reibung zwischen einem Bremsbelag und einer Reibfläche. Durch Anpressen beider Körper entsteht eine tangential wirkende Reibkraft, welche ein Bremsmoment für das Fahrzeug stellt, und somit final zur Verzögerung führt. Kinetische Energie wird also in diesen (recht kleinen) Reibflächen in andere Energieformen umgewandelt, was insbesondere Verschleiß und Reibgeräusche zur Folge hat.

ML wird genutzt, um die Emissionen unter verschiedensten Betriebsbedingungen (Außentemperaturen, Lastprofil, Lasthistorie, ...) zu modellieren, was klassische Verfahren bisher nur ungenügend können. Anhand dieser datengetriebenen Modelle können dann virtuelle Zwillinge abgeleitet werden, um Sensitivitäten der mechanischen Systeme gegenüber bestimmten Lastfällen zu erkennen. Anhand dieser Ergebnisse können dann die mechanischen Bremsen optimiert werden, z.B. über die Wahl eines anderen Belagmaterials.

Zur Anwendung kommen ML Methoden aus der Bildverarbeitung und Objekterkennung zur Detektion von Bremsgeräuschen in experimentellen Messdaten, tiefe rekurrente Netzwerke zur Vorhersage von Emissionen aus Lastkollektiven, Clustering-Methoden zur Erkennung von Sensitivitäten sowie Ansätze des interpretierbaren ML zur Ableitung von multivariaten Mustern in den hochdimensionalen Daten.
