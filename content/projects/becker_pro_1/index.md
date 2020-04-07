---
title: Machine Learning for Online Monitoring of Electric Power System Stability
summary:
authors:
- becker
tags:
- Neuronale Netze
- Elektrotechnik
- Signal Stabilität
- Stabile Spannungsversorgung

date: "2020-04-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

links: ""
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

Due to an ever increasing penetration of the electrical power system with power electronics coupled generation and transmission devices as well as loads, their dynamic behaviour will dominate the overall system dynamics in the future. In contrast to the dynamic behaviour of synchronous machines which still make up for most of the power generation today, this scheme does not supply any inertia and corresponding frequency response characteristics. Inverters equipped with novel control schemes like the virtual synchronous machine that seek to improve system dynamics are yet to gain any significance in the power generation portfolio. It is thus suspected that the system dynamics in general might develop negatively if plant controllers are not properly co-ordinated, and that the small signal stability in particular could deteriorate.

A monitoring setup for a power system’s small signal stability must work efficiently in terms of computational resources to operate in real time. They also need to suffice with sets of  input data limited by the measurement and communication setup in the entire system. Finally, they must cope with a strongly nonlinear behavior of the power system. Given these  requirements, computational intelligence is a viable approach. This project proposes a power system small signal stability monitoring method using artificial neural networks (ANNs). Once trained they can cope with nonlinearities and function computationally efficiently. 