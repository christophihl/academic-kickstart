---
title: 'Open Access Artikel zu Maschinellem Lernen für die Schätzung der Einfallsrichtung in Automobilradarsystemen veröffentlicht'
#subtitle: 'Bündelung der Kompetenzen und Austausch mit der Praxis'
summary:
authors:
- lurz
tags:
categories:
date: "2022-01-19T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 1
  caption: '© 2022 J. Fuchs et al., [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Wissenschaftler des MLE-Konsortiums der Technischen Universität Hamburg (TUHH) haben gemeinsam mit der FAU Erlangen-Nürnberg und der BTU Cottbus einen Artikel in der multidisziplinären Open-Access-Zeitschrift IEEE Access vorgestellt, bei dem sie die Einsatzmöglichkeiten von maschinellem Lernen zur Schätzung der Einfallsrichtung in Automobilradarsystemen untersuchen.

Radarsensorik ist eine Schlüsseltechnologie um im Straßenverkehr zuverlässig Hindernisse und andere Verkehrsteilnehmer, selbst unter schwierigen Umgebungsbedingungen, zu erkennen. Sie findet aktuell schon breite Anwendung in fortschrittlichen Fahrerassistenzsystemen (ADAS) und wird zukünftig als eine der wichtigsten Sensortechnologien für das autonome Fahren betrachtet. Neben einer Abstands- und (relativen) Geschwindigkeitsmessung führen moderne KFZ-Radarsysteme noch eine zweidimensionale Schätzung der Einfallsrichtung durch, um alle Ziele möglichst exakt zu lokalisieren. Eine große technische Herausforderung besteht aktuell noch darin die dafür notwendig Winkelauflösung durch intelligente Konzepte zu erhöhen. Um beispielsweise zwei Autos, die auf der Autobahn im Abstand von 200 m vor dem eigenen Fahrzeug und mit einem seitlichen Abstand zwischen zwei Fahrspuren von etwa 3,75 m fahren, zuverlässig als zwei einzelne Ziele erkennen zu können ist eine Winkelauflösung bei der Schätzung der Einfallsrichtung von etwa 1,1° erforderlich.

Der Artikel mit dem Titel [“A Machine Learning Perspective on Automotive Radar Direction of Arrival Estimation”](/publication/lurz_pub_2) gibt einen Überblick über die neuesten Fortschritte und Arbeiten auf dem Gebiet der auf Deep Learning basierenden Richtungsschätzung bei automobilen Radarsystemen. Darüber hinaus werden verschiedene Deep-Learning-Modelle verglichen und auf ihre Eignung für die Einfallswinkelschätzung im Automobilbereich hin untersucht. Die Modelle werden mit modell- und datenbasierten Ansätzen trainiert, wobei sowohl simulierte Szenarien als auch reale Messdaten von über 400 Kfz-Radarsensoren verwendet werden. Darüber hinaus wird ihre Leistung mit verschiedenen grundlegenden Winkelschätzungsalgorithmen wie dem Maximum-Likelihood-Schätzer verglichen.

Die Ergebnisse zeigen, dass mit Maschinellem Lernen eine sogenannte Super-resolution erreicht werden kann. Kurze Inferenzzeiten und ausreichende Generalisierung auf verschiedene Szenarien gehören zu den wichtigsten Vorteilen, z. B. im Vergleich mit dem deterministischen Maximum-Likelihood-Schätzer.
