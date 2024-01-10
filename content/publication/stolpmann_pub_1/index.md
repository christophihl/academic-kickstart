---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "In-Network Round-Trip Time Estimation for TCP Flows"
authors:
- stolpmann
- timmgiel
date: 2023-09-04T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-01-10T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2nd Workshop \"Machine Learning & Networking\" (MaLeNe)"
publication_short: "2nd Workshop \"Machine Learning & Networking\" (MaLeNe)"

abstract: "Transmission Control Protocol (TCP)'s tendency to fill up buffers in the network results in long standing queues. Active Queue Management (AQM) tries to solve this issue but typically requires manual tuning as the optimal parameters depend on the Round-Trip Time (RTT) of the flow, which is unknown to the AQM. In this paper, we use network simulation and supervised learning to train a neural network to infer the RTT of a TCP flow from its queuing behavior. We transfer our model into a real-time network emulator and show that it is able to estimate the RTT with an error of only a few milliseconds."

# Summary. An optional shortened abstract.
summary: ""

tags: [Active Queue Management, Dataset Generation, Supervised Learning, Network Emulation]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://opus.bibliothek.uni-augsburg.de/opus4/files/109653/109653.pdf
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
