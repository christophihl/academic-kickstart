---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Minimizing cost by reducing scaling operations in distributed stream processing"
authors:
- Michael Borkowski
- Christoph Hochreiner
- schulte_s
date: 2019-03-01
doi: "10.14778/3317315.3317316"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[Proceedings of the VLDB Endowment, Volume 12, Issue 7](https://dl.acm.org/journal/pvldb)"
publication_short: "[Proceedings of the VLDB Endowment, Volume 12, Issue 7](https://dl.acm.org/journal/pvldb)"

abstract: "Elastic distributed stream processing systems are able to dynamically adapt to changes in the workload. Often, these systems react to the rate of incoming data, or to the level of resource utilization, by scaling up or down. The goal is to optimize the system's resource usage, thereby reducing its operational cost. However, such scaling operations consume resources on their own, introducing a certain overhead of resource usage, and therefore cost, for every scaling operation. In addition, migrations caused by scaling operations inevitably lead to brief processing gaps. Therefore, an excessive number of scaling operations should be avoided.


We approach this problem by preventing unnecessary scaling operations and over-compensating reactions to short-term changes in the workload. This allows to maintain elasticity, while also minimizing the incurred overhead cost of scaling operations. To achieve this, we use advanced filtering techniques from the field of signal processing to pre-process raw system measurements, thus mitigating superfluous scaling operations. We perform a real-world testbed evaluation verifying the effects, and provide a break-even cost analysis to show the economic feasibility of our approach."

# Summary. An optional shortened abstract.
summary: ""

tags: []
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

