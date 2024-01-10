---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hidden Node-Aware Dynamic Spectrum Access using Deep Learning for Coexisting Aeronautical Communication Systems"
authors:
- Leonard Schulz
- kopyto
- stolpmann
- lindner_s
- bauch
- timmgiel
date: 2023-10-10T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-01-10T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[2023 IEEE 98th Vehicular Technology Conference (VTC2023-Fall)](https://ieeexplore.ieee.org/xpl/conhome/10333258/proceeding)"
publication_short: "[2023 IEEE 98th Vehicular Technology Conference (VTC2023-Fall)](https://ieeexplore.ieee.org/xpl/conhome/10333258/proceeding)"

abstract: "We propose a novel approach based on deep learning to address the hidden node problem which occurs in the coexistence of aeronautical communication standards. The modern aeronautical communication standard L-band Digital Aeronautical Communications System (LDACS) in Air-Air (A/A) mode needs to share spectrum with the Distance Measuring Equipment (DME), which is a legacy system. As DME is safety-critical, causing interference on it must be avoided for all newly proposed aeronautical systems spectrally coexisting with it. Recently, cognitive radio techniques have been proposed for LDACS A/A to access spectrum dynamically and to overcome the limitations of static approaches. For this, a Recurrent Neural Network (RNN) was trained to predict idle time slots on those frequency bands, where both systems operate. By exploiting patterns in the spectrum access of DME, a promising amount of idle resources could be predicted. However, previous approaches would perform poorly in a real-world deployment, as they did not take the hidden node problem into account.


This paper formulates the hidden node problem for the case that an LDACS A/A user is within communication range of a DME ground station, but not within range of all airborne DME users connected to it. Through statistical analysis, we underline the problem’s significance in practical cases. We simulate the coexistence of the two systems from a channel access perspective, taking signal propagation and the behavior of the ground station into account. Further, we present an RNN that is able to predict the channel access of hidden nodes. The key idea of our algorithm is to exploit the fact that while DME request pulses from airborne users may appear as hidden, response pulses from the ground station will be visible. Our results show that by inferring DME request channel activity from the response channel, the hidden node problem can be overcome effectively. By using our approach, nearly the same performance can be achieved as in the idealized case where all nodes are visible."

# Summary. An optional shortened abstract.
summary: ""

tags: [Cognitive Radio, Coexistence, Aeronautical Communications, Dynamic Spectrum Access, Hidden Node Problem]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
