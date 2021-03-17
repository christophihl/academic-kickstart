---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Deep Learning Approach for Pose Estimation from Volumetric OCT Data"
authors:
- Nils Gessert
- Matthias Schlüter
- schlaefer
date: 2020-03-10T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-10T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "[arXiv:1803.03852v1](https://arxiv.org/abs/1803.03852)"
publication_short: "[arXiv:1803.03852v1](https://arxiv.org/abs/1803.03852)"

abstract: "Tracking the pose of instruments is a central problem in image-guided surgery. For microscopic scenarios, optical coherence tomography (OCT) is increasingly used as an imaging modality. OCT is suitable for accurate pose estimation due to its micrometer range resolution and volumetric field of view. However, OCT image processing is challenging due to speckle noise and reflection artifacts in addition to the images' 3D nature. We address pose estimation from OCT volume data with a new deep learning-based tracking framework. For this purpose, we design a new 3D convolutional neural network (CNN) architecture to directly predict the 6D pose of a small marker geometry from OCT volumes. We use a hexapod robot to automatically acquire labeled data points which we use to train 3D CNN architectures for multi-output regression. We use this setup to provide an in-depth analysis on deep learning-based pose estimation from volumes. Specifically, we demonstrate that exploiting volume information for pose estimation yields higher accuracy than relying on 2D representations with depth information. Supporting this observation, we provide quantitative and qualitative results that 3D CNNs effectively exploit the depth structure of marker objects. Regarding the deep learning aspect, we present efficient design principles for 3D CNNs, making use of insights from the 2D deep learning community. In particular, we present Inception3D as a new architecture which performs best for our application. We show that our deep learning approach reaches errors at our ground-truth label's resolution."

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

url_pdf: https://arxiv.org/abs/1803.03852
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
