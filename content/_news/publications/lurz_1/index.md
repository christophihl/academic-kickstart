---
title: 'Artikel über maschinelles Lernen zur Radar-basierten Personenerkennung und Aktivitätsklassifikation veröffentlicht'
#subtitle: 'Bündelung der Kompetenzen und Austausch mit der Praxis'
summary:
authors:
- lurz
tags:
categories:
date: "2021-09-17T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 1
  caption: '© 2021 IEEE. Reprinted, with permission, from https://doi.org/10.1109/JSEN.2021.3092002'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Forscher des MLE-Konsortiums der Technischen Universität Hamburg (TUHH) haben gemeinsam mit dem Lehrstuhl für Technische Elektronik der FAU Erlangen-Nürnberg und Infineon Technologies AG einen neuen Ansatz des maschinellen Lernens vorgestellt, der zuverlässig Personen erkennen und deren Aktivitäten klassifizieren kann. Mit einem hochintegrierten 60 GHz Radarsystemen (das Frontend selbst ist kleiner als eine 1€-Münze) können verschiedene menschliche Aktivitäten wie z.B. gehen, stehen, Arme bewegen, winken und arbeiten am Laptop berührungslos über mehrere Meter detektiert werden.

Für die Ergebnisse, die in der renommierten Fachzeitschrift „IEEE Sensors Journal“ veröffentlicht wurden ([„Data-Driven Radar Processing Using a Parametric Convolutional Neural Network for Human Activity Classification“](../../../publication/lurz_pub_1/), doi: [10.1109/JSEN.2021.3092002](https://doi.org/10.1109/JSEN.2021.3092002)) gibt es vielfältige Anwendungen, beispielsweise im Smart Home Bereich: Das Wissen über die Anwesenheit und Aktivität von Menschen kann etwa zur intelligenten Steuerung von Licht, Heizung und Belüftung-/Klimatisierungssystemen genutzt werden, die damit energieeffizienter und nachhaltiger arbeiten können. Ebenso lassen sich die Ansätze aber auch zur Verbesserung der automatischen Sturzerkennung von älteren Personen anwenden oder für Mensch-Maschine-Schnittstellen und Sicherheitsanwendungen verwenden.

Das vorgestellte Verfahren erreicht mit einem F1-Score von 99,5% (± 0,3) eine sehr hohe Zuverlässigkeit. Dies wurde unter anderem dadurch erreicht, dass neben der Auswertung der Mikro-Doppler-Signaturen mit maschinellem Lernen zusätzlich die „klassische“ Vorverarbeitung der Radardaten durch adaptive (2D sinc bzw. 2D wavelet) Filter ersetzt wurden, deren ideale Parameter das neuronale Netz während dem Training lernt.

Weitere Informationen:   
Dr.-Ing. Fabian Lurz   
+49 40 42878 – 3119   
fabian.lurz@tuhh.de
