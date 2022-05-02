---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Active learning of potential-energy surfaces of weakly bound complexes with regression-tree ensembles"
authors:
- saleh
- Vishnu Sanjay
- Armin Iske
- Andrey Yachmenev
- Jochen Küpper
date: 2021-10-13
doi: "10.1063/5.0057051"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-02T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "[J. Chem. Phys. 155, 144109 (2021)](https://aip.scitation.org/journal/jcp)"
publication_short: "[J. Chem. Phys. 155, 144109 (2021)](https://aip.scitation.org/journal/jcp)"

abstract: "Several pool-based active learning (AL) algorithms were employed to model potential-energy surfaces (PESs) with a minimum number of electronic structure calculations. Theoretical and empirical results suggest that superior strategies can be obtained by sampling molecular structures corresponding to large uncertainties in their predictions while at the same time not deviating much from the true distribution of the data. To model PESs in an AL framework, we propose to use a regression version of stochastic query by forest, a hybrid method that samples points corresponding to large uncertainties while avoiding collecting too many points from sparse regions of space. The algorithm is implemented with decision trees that come with relatively small computational costs. We empirically show that this algorithm requires around half the data to converge to the same accuracy in comparison to the uncertainty-based query-by-committee algorithm. Moreover, the algorithm is fully automatic and does not require any prior knowledge of the PES. Simulations on a 6D PES of pyrrole(H<sub>2</sub>O) show that <15 000 configurations are enough to build a PES with a generalization error of 16 cm<sup>-1</sup>, whereas the final model with around 50 000 configurations has a generalization error of 11 cm<sup>-1</sup>."

# Summary. An optional shortened abstract.
summary: ""

tags: [Molecular Physics, Active Learning, Neural Networks]
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
