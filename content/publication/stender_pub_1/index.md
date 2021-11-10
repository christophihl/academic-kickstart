---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep learning for brake squeal: Brake noise detection, characterization and prediction"
authors:
- stender
- Merten Tiedemann
- Dawid Spieler
- schoepflin
- hoffmann
- Sebastian Oberst
date: 2021-02-15T00:00:00+00:00
doi: "10.1016/j.ymssp.2020.107181"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "[Mechanical Systems and Signal Processing (Volume 149, 15. February 2021, 107181)](https://www.sciencedirect.com/journal/mechanical-systems-and-signal-processing)"
publication_short: "[Mechanical Systems and Signal Processing (Volume 149, 15. February 2021, 107181)](https://www.sciencedirect.com/journal/mechanical-systems-and-signal-processing)"

abstract: "Despite significant advances in modeling of friction-induced vibrations and brake squeal, the majority of industrial research and design is still conducted experimentally, since many aspects of squeal and its mechanisms involved remain unknown. In practice, measurement data is available in large amounts. We report here for the first time on novel strategies for handling data-intensive vibration testings to gain better insights into friction brake system vibrations and noise generation mechanisms. Machine learning-based methods to detect and characterize vibrations, to understand sensitivities and to predict brake squeal are applied with the aim to illustrate how interdisciplinary approaches can leverage the potential of data science techniques for classical mechanical engineering challenges. In the first part, a deep learning brake squeal detector is developed to identify several classes of typical friction noise recordings. The detection method is rooted in recent computer vision techniques for object detection based on convolutional neural networks (CNN). It allows to overcome limitations of classical approaches that solely rely on instantaneous spectral properties of the recorded noise. Results indicate superior detection and characterization quality when compared to a state-of-the-art brake squeal detector. In the second part, a recurrent neural network (RNN) is employed to learn the parametric patterns that determine the dynamic stability of an operating brake system. Given a set of multivariate loading conditions, the RNN learns to predict the noise generation of the structure. The validated RNN represents a virtual twin model for the squeal behavior of a specific brake system. It is found that this model can predict the occurrence and the onset of brake squeal with high accuracy and that it can identify the complicated patterns and temporal dependencies in the loading conditions that drive the dynamical structure into regimes of instability. Large data sets from commercial brake system testing are used to train and validate the models."

# Summary. An optional shortened abstract.
summary: ""

tags: [Bremsen, Reibphysik, Deep Learning, Objekterkennung, Zeitreihen]
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
#   Otherwise, set `projects: [content/project/project_bremsen/index.md]`.
projects: [stender_pro_1]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
