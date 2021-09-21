---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Data-Driven Radar Processing Using a Parametric Convolutional Neural Network for Human Activity Classification"
authors:
- Thomas Stadelmayer
- Avik Santra
- Robert Weigel
- lurz
date: 2021-09-01T00:00:00+02:00
doi: "10.1109/JSEN.2021.3092002"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "[IEEE Sensors Journal (Volume: 21, Issue: 17, Sept.1, 1 2021)](https://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=9525468)"
publication_short: "[IEEE Sensors Journal (Volume: 21, Issue: 17, Sept.1, 1 2021)](https://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=9525468)"

abstract: "The paper proposes a data-driven pre-processing optimization for radar data using a parametric convolutional neural network. The proposed method is applied on human activity classification as a use case. Present radar-based activity recognition system exploit micro-Doppler signature by generating Doppler spectrograms or a temporal series of range-Doppler maps, followed by deep neural networks or machine learning approaches for classification. Those radar data representations are typically generated on the basis of short-time Fourier transformations. A Fourier transformation equally resolves the frequency space, which may be sub-optimal in some applications. Although deep convolutional neural networks (DCNN) have been shown to implicitly learn features from raw sensor data in other fields, such as speech recognition, yet, for the case of radar-based DCNNs, pre-processing is required to develop a scalable and robust classification or regression application. In this paper, we propose a parametric convolutional neural network that mimics the radar pre-processing across fast-time and slow-time radar data through 2D sinc filter or 2D wavelet filter kernels to extract features for classification of various human activities. During training only the filter parameters of the 2D sinc filters or 2D wavelets are learned, leading to optimized feature representation for the classification task. It is demonstrated that our proposed solution shows improved results compared to equivalent DCNN architectures that rely on Doppler spectrograms or radar data cubes as input data."

# Summary. An optional shortened abstract.
summary: ""

tags: [2D Sinc Filters, 2D Wavelets, Parametric CNN, Deep Learning, Human Activity Classification]
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
