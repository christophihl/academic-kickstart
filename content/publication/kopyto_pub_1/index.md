---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Learning-Based Dynamic Spectrum Access for Coexistence of Aeronautical Communication Systems"
authors:
- kopyto
- lindner_s
- Leonard Schulz
- stolpmann
- bauch
- timmgiel
date: 2022-09-26T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-01-10T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[2022 IEEE 96th Vehicular Technology Conference (VTC2022-Fall)](https://ieeexplore.ieee.org/xpl/conhome/10012685/proceeding)"
publication_short: "[2022 IEEE 96th Vehicular Technology Conference (VTC2022-Fall)](https://ieeexplore.ieee.org/xpl/conhome/10012685/proceeding)"

abstract: "In aeronautical communications, legacy systems often only use a small fraction of their historically assigned frequency spectra sparsely over time. Novel systems such as L-band Digital Aeronautical Communications System (LDACS) Air-Air (A/A) need to coexist with legacy systems, and must ensure not to cause excessive interference. The Distance Measuring Equipment (DME) is the most critical legacy system in this case. To analyze the potential number of idle communication resources in LDACS A/A and DME coexistence, we propose a statistical model, which reveals a substantial number of opportunities. Motivated by the statistical properties of the co-existence scenario, we propose a Recurrent Neural Network (RNN) to predict DME patterns reliably. Our architecture is based on a combination of Long Short-Term Memory (LSTM) and dense layers and was found with the help of hyperparameter optimization techniques. The predictor is trained and evaluated on a synthetic data set using realistic DME parameters. Furthermore, we introduce a baseline algorithm for comparison, which makes perfect predictions on a simplified periodic data set but breaks down for realistic scenarios. We argue that our Deep Learning approach can be used in realistic scenarios to detect idle resources given a strict constraint on correctly predicted busy resources."

# Summary. An optional shortened abstract.
summary: ""

tags: [Cognitive Radio, Coexistence, Aeronautical Communications, Dynamic Spectrum Access]
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
