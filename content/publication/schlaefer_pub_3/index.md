---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Force Estimation from OCT Volumes using 3D CNNs"
authors:
- Nils Gessert
- Jens Beringhoff
- Christoph Otte
- schlaefer
date: 2018-04-26T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-04-26T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "[arXiv:1804.10002v1](https://arxiv.org/abs/1804.10002)"
publication_short: "[arXiv:1804.10002v1](https://arxiv.org/abs/1804.10002)"

abstract: "Purpose: Estimating the interaction forces of instruments and tissue is of interest, particularly to provide haptic feedback during robot assisted minimally invasive interventions. Different approaches based on external and integrated force sensors have been proposed. These are hampered by friction, sensor size, and sterilizability. We investigate a novel approach to estimate the force vector directly from optical coherence tomography image volumes.

Methods: We introduce a novel Siamese 3D CNN architecture. The network takes an undeformed reference volume and a deformed sample volume as an input and outputs the three components of the force vector. We employ a deep residual architecture with bottlenecks for increased efficiency. We compare the Siamese approach to methods using difference volumes and two-dimensional projections. Data was generated using a robotic setup to obtain ground truth force vectors for silicon tissue phantoms as well as porcine tissue.

Results: Our method achieves a mean average error of 7.7 +- 4.3 mN when estimating the force vector. Our novel Siamese 3D CNN architecture outperforms single-path methods that achieve a mean average error of 11.59 +- 6.7 mN. Moreover, the use of volume data leads to significantly higher performance compared to processing only surface information which achieves a mean average error of 24.38 +- 22.0 mN. Based on the tissue dataset, our methods shows good generalization in between different subjects.

Conclusions: We propose a novel image-based force estimation method using optical coherence tomography. We illustrate that capturing the deformation of subsurface structures substantially improves force estimation. Our approach can provide accurate force estimates in surgical setups when using intraoperative optical coherence tomography."

# Summary. An optional shortened abstract.
summary: ""

tags: [Medizintechnik, Kräftemessung, Neuronale Netze]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1804.10002
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
