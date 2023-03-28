---
title: Structural Optimization for Fail-Safe Designs by Machine Learning
summary:
authors:
- kriegesmann
tags:
- Neuronale Netze
date: "2023-03-28T00:00:00Z"

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
url_project: "https://www.tuhh.de/sml/forschung/sof-ml"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

The overall objective of the current proposal is the development of a process for efficient topology optimization of fail-safe structures. The basic idea for this process is summarized in the figure above. For any new optimization problem, a “plain” topology optimization without consideration of fail-safety is carried out. Then, a convolutional neural network (CNN) derives a redundant version of the optimized topology. In a final step, the design suggested by the CNN is fine-tuned by a shape optimization in the density field.

Before the process can be applied, it is of course necessary to train the CNN for the task. Therefore, in the proposed project numerous combinations of design spaces, boundary conditions and loads will be considered, and for each combination both, a plain topology optimization and an expansive fail-safe topology optimization will be conducted. The CNN will be trained to map the density field originating from the plain topology optimization to the fail-safe topology.
