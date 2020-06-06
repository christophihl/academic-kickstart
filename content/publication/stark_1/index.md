---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Trainable Communication Systems: Concepts and Prototype"
authors:
- Sebastian Cammerer
- Faycal Ait Aoudia
- Sebastian Dörner
- stark
- Jakob Hoydis
- Stephan ten Brink
date: 2019-11-09
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-09

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "[arXiv:1911.13055](https://arxiv.org/abs/1911.13055)"
publication_short: "[arXiv:1911.13055](https://arxiv.org/abs/1911.13055)"

abstract: "We consider a trainable point-to-point communication system, where both transmitter and receiver are implemented as neural networks (NNs), and demonstrate that training on the bit-wise mutual information (BMI) allows seamless integration with practical bit-metric decoding (BMD) receivers, as well as joint optimization of constellation shaping and labeling. Moreover, we present a fully differentiable neural iterative demapping and decoding (IDD) structure which achieves significant gains on additive white Gaussian noise (AWGN) channels using a standard 802.11n low-density parity-check (LDPC) code. The strength of this approach is that it can be applied to arbitrary channels without any modifications. Going one step further, we show that careful code design can lead to further performance improvements. Lastly, we show the viability of the proposed system through implementation on software-defined radios (SDRs) and training of the end-to-end system on the actual wireless channel. Experimental results reveal that the proposed method enables significant gains compared to conventional techniques."

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

url_pdf: https://arxiv.org/abs/1911.13055
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
