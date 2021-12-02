---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimal Placement of Stream Processing Operators in the Fog"
authors:
- Thomas Hiessl
- Vasileios Karagiannis
- Christoph Hochreiner
- schulte_s
- Matteo Nardelli
date: 2019-05-14
doi: "10.1109/CFEC.2019.8733147"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[2019 IEEE 3rd International Conference on Fog and Edge Computing (ICFEC)](https://ieeexplore.ieee.org/xpl/conhome/1821484/all-proceedings)"
publication_short: "[2019 IEEE 3rd International Conference on Fog and Edge Computing (ICFEC)](https://ieeexplore.ieee.org/xpl/conhome/1821484/all-proceedings)"

abstract: "Elastic data stream processing enables applications to query and analyze streams of real time data. This is commonly facilitated by processing the flow of the data streams using a collection of stream processing operators which are placed in the cloud. However, the cloud follows a centralized approach which is prone to high latency delay. For avoiding this delay, we leverage on the fog computing paradigm which extends the cloud to the edge of the network.


In order to design a stream processing solution for the fog, we first formulate an optimization problem for the placement of stream processing operators, which is tailored to fog computing environments. Then, we build a plugin (for stream processing frameworks) which solves the optimization problem periodically in order to support the dynamic resources of the fog. We evaluate this approach by performing experiments on an OpenStack testbed. The results show that our plugin reduces the response time and the cost by 31.5% and 8.8% respectively, compared to optimizing the placement of operators only upon initialization."

# Summary. An optional shortened abstract.
summary: ""

tags: [Edge Computing, Stream Processing, Internet of Things]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://dsg.tuwien.ac.at/team/vkaragiannis/publications/ICFEC2019_ODR.pdf
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

