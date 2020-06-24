---
title: Zuverlässigkeit von Systemen beim Einsatz von Machine Learning
summary: Wird Machine Learning in der Praxis eingesetzt, können Fehlfunktionen in der zugrunde liegenden Recheninfrastruktur die Korrektheit gefährden. Im Projekt wird dieser Zusammenhang analysiert.
authors:
- fey
- bahnsen
tags:
- Eingebettete Systeme
- Fehlfunktion
- Zuverlässigkeit
date: "2020-06-24T00:00:00Z"

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
# slides:
---

Beim Einsatz von Machine Learning ist außer der Genauigkeit der gelernten Information auch das darunter liegende Rechensystem von zentraler Bedeutung für die Zuverlässigkeit. Treten Fehler in der Recheninfrastruktur auf, wird die Korrektheit der Anwendung gefährdet.

Im vorliegenden Projekt wird genau dieser Zusammenhang untersucht. In einer ersten Analyse wurde eine konkrete Hardware-Architektur modelliert und es wurden Fehler in das Rechensystem injiziert. Dafür wurden zunächst Künstliche Neuronale Netze mittels der Frameworks Keras und Tensorflow trainiert. Diese Neuronalen Netze werden dann exportiert und in die zugrunde liegenden Operationen zerlegt. Die anschließende Ausführung von Klassifikationen auf der simulierten Hardware-Architektur erlaubt es, Fehler zu injizieren und deren Auswirkung auf Ebene der Anwendung zu bestimmen.

{{< figure src="faultInjection_architecture.png" title="Einfache Hardware Architektur zur Beschleunigung von Machine Learning Anwendungen" lightbox="true" >}}

{{< figure src="featured.png" title="Resultate der Fehlerinjektion - je nach Ort der Fehlerinjektion resultiert eine andere Fehlerrate auf Anwendungsebene" lightbox="true" >}}