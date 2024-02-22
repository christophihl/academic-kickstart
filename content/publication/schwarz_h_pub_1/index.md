---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Machine Learning based Prediction of Ditching Loads"
authors:
- schwarz_h
- Micha Überrück
- zemke
- rung
date: 2024-02-16T14:30:46+00:00
doi: "10.48550/arXiv.2402.10724"

# Schedule page publish date (NOT publication's date).
publishDate: 2024-02-22T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "[arXiv:2402.10724](https://arxiv.org/abs/2402.10724)"
publication_short: "[arXiv:2402.10724](https://arxiv.org/abs/2402.10724)"

abstract: "We present approaches to predict dynamic ditching loads on aircraft fuselages using machine learning. The employed learning procedure is structured into two parts, the reconstruction of the spatial loads using a convolutional autoencoder (CAE) and the transient evolution of these loads in a subsequent part. Different CAE strategies are assessed and combined with either long short-term memory (LSTM) networks or Koopman-operator based methods to predict the transient behaviour. The training data is compiled by an extension of the momentum method of von-Karman and Wagner and the rationale of the training approach is briefly summarised. The application included refers to a full-scale fuselage of a DLR-D150 aircraft for a range of horizontal and vertical approach velocities at 6° incidence. Results indicate a satisfactory level of predictive agreement for all four investigated surrogate models examined, with the combination of an LSTM and a deep decoder CAE showing the best performance."

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
