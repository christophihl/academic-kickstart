---
title: Learning Conversational Action Repair for Intelligent Robots (LeCAREbot)
summary: Lernen von konversationaller Aktionsreparatur für intelligente Roboter
authors:
- eppe
tags:
- Natural Language Processing
- Reinforcement Learning
- Human-Robot Interaction
date: "2023-09-11T00:00:00Z"

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

Konversationelle natürliche Sprache unterliegt Rauschen, Unvollständigkeiten und grammatikalisch mehrdeutigen Formulierungen. Um die Robustheit der Kommunikation zu erhöhen, nutzen Gesprächspartner typischerweise Konversationelle Reparatur (KR) um iterativ und interaktiv Missverständnisse aufzulösen. Im Kontext der Mensch-Roboter Interaktion bietet KR vor allem die Möglichkeit, eine sich bereits in Ausführung befindliche falsch verstandene Instruktion zu unterbrechen und zu korrigieren. Aktuelle Forschungsansätze berücksichtigen die konversationelle Reparatur von Missverständnissen im Mensch-Roboter-Dialog nicht, obwohl dies die Robustheit der Mensch-Roboter Interaktion erheblich erhöhen würde. Ziel dieses Projekts ist es, diese Lücke zu schließen, indem zwei Kernprobleme behoben werden, die bisherige Ansätze bei der erfolgreichen Behebung von Konversationsmaßnahmen für die Mensch-Roboter-Interaktion behindert haben. Das erste Problem ist die Realisierung eines adaptiven kontextspezifischen Zustandsmodells, das Sprache und Handlung integriert. Die meisten Dialogsysteme betrachten nur verbale Kommunikation und ignorieren, dass menschliche Kommunikation ein körperlicher multimodaler Prozess ist, der stark auf physischer Interaktion beruht. Wie können wir also ein skalierbares Modell realisieren, das körperlich-konzeptuelle Zustandsdarstellungen für eine gemischte verbal-physikalische Interaktion berücksichtigt? Um dieses erste Problem zu adressieren, baut dieses Projekt auf einem neuro-symbolischen Ansatz auf, der unsere bisherigen Arbeiten zum verkörperten semantischen Parsen mit unserer Expertise in tiefem Reinforcement Learning integriert. Auf dieser Grundlage werden wir ein hybrides daten- und wissensbasiertes Modell für kompositionale Interaktionszustände untersuchen, das den physischen Weltzustand mit der Semantik in Sprache und Dialog verbindet.Das zweite Problem betrifft das Rauschen, die Unregelmäßigkeiten und die Polysemie der gesprochenen natürlichen Sprache. Bestehende lernbasierte Parser sind robust genug, um gesprochene Sprache zu analysieren, erfordern jedoch große Mengen an Trainingsdaten. Wie können wir also einen robusten semantischen Parser realisieren, der dateneffizient ist und gleichzeitig die gemischte verbal-physikalische Interaktion berücksichtigt? Um dieses zweite Problem zu adressieren, ergänzt dieses Projekt unsere bisherigen semantischen Parsing-Methoden mit Reinforcement Learning. Hierbei werden wir unter anderem das Belohnungssignal im Reinforcement Learning als zusätzliche Datenquelle nutzen, um den neuronalen Parser dateneffizienter zu trainieren. Wir erwarten, dass das Projekt neue Möglichkeiten in der Mensch-Roboter-Interaktion erzeugt, und neuartige Methoden für das Lernen von Repräsentation für die wissenschaftlichen Communities auf den Gebieten der computationellen Sprachverarbeitung, des maschinellen Lernens und der intelligenten Robotik bereitstellt. 
