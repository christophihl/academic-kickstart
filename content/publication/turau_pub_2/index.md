---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "QMA: A Resource-efficient, Q-learning-based Multiple Access Scheme for the IIoT"
authors:
- meyer
- turau
date: 2021-07-07
doi: "10.1109/ICDCS51616.2021.00087"

# Schedule page publish date (NOT publication's date).
# publishDate:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[2021 IEEE 41st International Conference on Distributed Computing Systems (ICDCS)](https://icdcs2021.us/)"
#publication_short: "arXiv"

abstract: "Many MAC protocols for the Industrial Internet of Things, such as IEEE 802.15.4 and its extensions, require contention-based channel access for management traffic, e.g., for slot (de)allocations and broadcasts. In many cases, subtle but hidden patterns characterize this secondary traffic, but present contention-based protocols are unaware of these patterns and therefore cannot exploit them. Especially in dense networks, these protocols often do not provide sufficient throughput and reliability for primary traffic, i.e., they cannot allocate transmission slots in time. In this paper, we propose QMA, a contention-based multiple access scheme based on Q-learning. It dynamically adjusts transmission times to avoid collisions by learning patterns in contention-based traffic. We show that QMA solves the hidden node problem without the overhead for RTS/CTS messages and, for example, increases throughput from 10 packets/s to 50 packets/s in a hidden three-node scenario without sacrificing reliability. Additionally, QMA's scalability is evaluated in a realistic scenario for slot (de)allocation in IEEE 802.15.4 DSME, where it achieves up to twice more slot (de)allocations per second."

# Summary. An optional shortened abstract.
summary: ""

tags: [Machine Learning, Reinforcement Learning, Cooperative Q-learning, Contention-based Multiple Access, CSMA, IEEE 802.15.4 DSME]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: Preprint
   url: https://arxiv.org/abs/2101.04003
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://media.tuhh.de/ti5/icdcs/

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
projects: ['turau_pro_2']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
