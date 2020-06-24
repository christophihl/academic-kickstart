---
title: Anomaliedetektion in eingebetteten Systeme
summary: Detektion von unerwartetem Verhalten in eingebetten Systemen - zum Beispiel durch Fehler zur Laufzeit. Maschinelles Lernen dient zunächst dazu, das nominale Verhalten automatisch zu bestimmen. 
authors:
- fey
- bahnsen
tags:
- Eingebettete Systeme
- Anomalie Detektion
- Monitoring
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

Eingebettete Systeme werden in unterschiedlichsten, so auch sicherheitsrelevanten Bereichen (sowohl Saftey als auch Security) eingesetzt. In diesen Fällen ist nicht nur der Entwurf eines korrekten Systems entscheidend. Zusätzlich muss auch zur Laufzeit garantiert werden, dass kein Fehlverhalten auftritt, welches durch Einwirkungen von Außen durch "bösartige Angriffe" oder interne Fehlfunktionen verursacht werden kann. Eine Lösung hierfür ist die automatische Detektion von Anomalien, die während des Einsatzes auftreten. 
Eine klassische Methode dafür ist ein "Monitoring" des Systems, d.h. eine Beobachtung des Systems durch eine unabhängige Einheit. Diese unabhängige Einheit entscheidet, ob das beobachtete Verhalten nominal oder unerwartet ist. Im letzteren Fall wird eine aktive Problembehandlung ausgelöst werden.

Je nach Einsatzbereich ist der Entwurf eines Monitors jedoch zeitaufwändig, da zunächst das nominale Verhalten gut verstanden, dann formalisiert und danach der Monitor selbst entworfen werden muss.

Im Projekt wird daher untersucht, wie gut sich Methdoden des Maschinellen Lernens eigenen, zunächst nominales Verhalten automatisiert zu lernen und dann zur Fehlerdetektion einzusetzen. In ersten Experimenten wurde der Ansatz zum Beispiel auf einen simulierten Staubsaugerroboter angewandt. Es konnten erfolgreich verschiedene Arten von internen Fehlern detektiert werden.

{{< figure src="featured.png" title="Simulierter Staubsaugerroboter" lightbox="true" >}}

{{< figure src="monitoring_data.png" title="Lernen und Fehlerdetektion" lightbox="true" >}}