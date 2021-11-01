---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Neural network surgery: Combining training with topology optimization"
authors:
- schiessler
- Roland Aydin
- Kevin Linka
- cyron
date: 2021-08-30T00:00:00+01:00
doi: "10.1016/j.neunet.2021.08.034"

# Schedule page publish date (NOT publication's date).
#publishDate: 2021-10-28T13:53:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "[Neural Networks 144 (2021) 384–393](https://www.sciencedirect.com/journal/neural-networks/vol/144)"
publication_short: "[Neural Networks 144 (2021) 384–393](https://www.sciencedirect.com/journal/neural-networks/vol/144)"

abstract: "With ever increasing computational capacities, neural networks become more and more proficient at solving complex tasks. However, picking a sufficiently good network topology usually relies on expert human knowledge. Neural architecture search aims to reduce the extent of expertise that is needed. Modern architecture search techniques often rely on immense computational power, or apply trained meta-controllers for decision making. We develop a framework for a genetic algorithm that is both computationally cheap and makes decisions based on mathematical criteria rather than trained parameters. It is a hybrid approach that fuses training and topology optimization together into one process. Structural modifications that are performed include adding or removing layers of neurons, with some re-training applied to make up for any incurred change in input–output behaviour. Our ansatz is tested on several benchmark datasets with limited computational overhead compared to training only the baseline. This algorithm can achieve a significant increase in accuracy (as compared to a fully trained baseline), rescue insufficient topologies that in their current state are only able to learn to a limited extent, and dynamically reduce network size without loss in achieved accuracy. On standard ML datasets, accuracy improvements compared to baseline performance can range from 20% for well performing starting topologies to more than 40% in case of insufficient baselines, or reduce network size by almost 15%."

# Summary. An optional shortened abstract.
summary: ""

tags: [Neural Architecture Search, Topology Optimization, Singular Value Decomposition, Genetic Algorithm]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.sciencedirect.com/science/article/pii/S0893608021003476/pdfft?md5=1dce44420ba8555dfd82879710de0b0f&pid=1-s2.0-S0893608021003476-main.pdf
url_code: https://github.com/ElisabethJS/neural-network-surgery
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
  caption: "© 2021 E.J. Schiessler et al., [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)"
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
