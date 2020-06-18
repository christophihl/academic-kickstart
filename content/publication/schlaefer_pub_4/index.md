---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Left Ventricle Quantification Using Direct Regression with Segmentation Regularization and Ensembles of Pretrained 2D and 3D CNNs"
authors:
- schlaefer
date: 2019-12-08T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-08T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "[arXiv:1908.04181v12](https://arxiv.org/abs/1908.04181)"
publication_short: "[arXiv:1908.04181v12](https://arxiv.org/abs/1908.04181)"

abstract: "Cardiac left ventricle (LV) quantification provides a tool for diagnosing cardiac diseases. Automatic calculation of all relevant LV indices from cardiac MR images is an intricate task due to large variations among patients and deformation during the cardiac cycle. Typical methods are based on segmentation of the myocardium or direct regression from MR images. To consider cardiac motion and deformation, recurrent neural networks and spatio-temporal convolutional neural networks (CNNs) have been proposed. We study an approach combining state-of-the-art models and emphasizing transfer learning to account for the small dataset provided for the LVQuan19 challenge. We compare 2D spatial and 3D spatio-temporal CNNs for LV indices regression and cardiac phase classification. To incorporate segmentation information, we propose an architecture-independent segmentation-based regularization. To improve the robustness further, we employ a search scheme that identifies the optimal ensemble from a set of architecture variants. Evaluating on the LVQuan19 Challenge training dataset with 5-fold cross-validation, we achieve mean absolute errors of 111 +- 76mm^2, 1.84 +- 0.9mm and 1.22 +- 0.6mm for area, dimension and regional wall thickness regression, respectively. The error rate for cardiac phase classification is 6.7%."

# Summary. An optional shortened abstract.
summary: ""

tags: [Medizintechnik, Bilderkennung, Neuronale Netze]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1908.04181
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
