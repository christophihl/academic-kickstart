---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hybrid Modelling by Machine Learning Corrections of Analytical Model Predictions towards High-Fidelity Simulation Solutions"
authors:
- bock
- Sören Keller
- Norbert Huber
- Benjamin Klusemann
date: 2021-04-10T09:04:22+01:00
doi: "10.3390/ma14081883"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-10T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "[Materials 2021, 14, 1883](https://www.mdpi.com/1996-1944/14/8/1883)"
publication_short: "[Materials 2021, 14, 1883](https://www.mdpi.com/1996-1944/14/8/1883)"

abstract: "Within the fields of materials mechanics, the consideration of physical laws in machine learning predictions besides the use of data can enable low prediction errors and robustness as opposed to predictions only based on data. On the one hand, exclusive utilization of fundamental physical relationships might show significant deviations in their predictions compared to reality, due to simplifications and assumptions. On the other hand, using only data and neglecting well-established physical laws can create the need for unreasonably large data sets that are required to exhibit low bias and are usually expensive to collect. However, fundamental but simplified physics in combination with a corrective model that compensates for possible deviations, e.g., to experimental data, can lead to physics-based predictions with low prediction errors, also despite scarce data. In this article, it is demonstrated that a hybrid model approach consisting of a physics-based model that is corrected via an artificial neural network represents an efficient prediction tool as opposed to a purely data-driven model. In particular, a semi-analytical model serves as an efficient low-fidelity model with noticeable prediction errors outside its calibration domain. An artificial neural network is used to correct the semi-analytical solution towards a desired reference solution provided by high-fidelity finite element simulations, while the efficiency of the semi-analytical model is maintained and the applicability range enhanced. We utilize residual stresses that are induced by laser shock peening as a use-case example. In addition, it is shown that non-unique relationships between model inputs and outputs lead to high prediction errors and the identification of salient input features via dimensionality analysis is highly beneficial to achieve low prediction errors. In a generalization task, predictions are also outside the process parameter space of the training region while remaining in the trained range of corrections. The corrective model predictions show substantially smaller errors than purely data-driven model predictions, which illustrates one of the benefits of the hybrid modelling approach. Ultimately, when the amount of samples in the data set is reduced, the generalization of the physics-related corrective model outperforms the purely data-driven model, which also demonstrates efficient applicability of the proposed hybrid modelling approach to problems where data is scarce."

# Summary. An optional shortened abstract.
summary: ""

tags: [Machine Learning, Analytical Model, Finite Element Model, Artificial Neural Networks, Model Correction, Feature Engineering, Physics based, Data driven, Laser Shock Peening, Residual Stresses]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.mdpi.com/1996-1944/14/8/1883/pdf
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
