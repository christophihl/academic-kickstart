---
title: Machine Learning für die Detektion von "weak-bonds" in Klebeverbindungen von Faserverbunden
summary: Auswertung von Messdaten für die Detektion von Klebefehlern in Strukturbauteilen mit Neuralen Netzen
authors:
- meissner
- boll
tags:
- Faserverbunde
- Klebefehler
- Zerstörungsfreie Prüfung
- Vibroakustische Modulation
- Neuronale Netze
- TensorFlow

date: "2021-11-22T00:00:00Z"

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

Im Rahmen dieses Projekts werden modernste Machine Learning und Deep Learning Methoden angewandt, um die Güte von geklebten Faserverbund-Proben zu analysieren.

Ein wichtiger Aspekt hierbei ist das Auftreten von sogenannte "weak-bonds", also Bereichen in denen eine Adhäsion besteht, diese jedoch deutlich reduziert ist. Diese Bereiche sind mit den traditionell angewendeten Messmethoden wie Puls-Echo Ultraschall nicht zu detektieren. Sie führen jedoch zu einer deutlichen Reduktion der Festigkeit. Daher müssen Klebeverbindungen, beispielsweise in der Luftfahrt, stets durch einen zweiten Lastpfad oder eine zusätzliche mechanische Verbindung abgesichert werden.

In diesem Projekt wird mit zwei modulierenden Schwingungen nach dem Prinzip der Vibroakustischen Modulation (VAM) eine Evaluation der Proben vorgenommen. Hierbei wird eine nieder frequente Schwingung mit hoher Spannungsamplitude und eine hochfrequente Schwingung im Ultraschallbereich eingebracht und die Änderung der Modulation beider Schwingungen betrachtet.

Durch die Auswertung er Messdaten mit neuronalen Netzen hat sich gezeigt, dass Muster in den Daten existieren, die eine Detektion der "weak-bonds" mit einer Präzision von über 90% ermöglichen.
Die ersten Ergebnisse sind in dem bereits veröffentlichten Paper dargestellt.
