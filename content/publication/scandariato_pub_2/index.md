---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The Effect of Dimensionality Reduction on Software Vulnerability Prediction Models"
authors:
- Jeffrey Stuckman
- James Walden
- scandariato
date: 2016-12-09
doi: "10.1109/TR.2016.2630503"

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Reliability, 66(1), 2017"
publication_short: "IEEE Transactions on Reliability, 66(1), 2017"

abstract: "Statistical prediction models can be an effective technique to identify vulnerable components in large software projects. Two aspects of vulnerability prediction models have a profound impact on their performance: 1) the features (i.e., the characteristics of the software) that are used as predictors and 2) the way those features are used in the setup of the statistical learning machinery. In a previous work, we compared models based on two different types of features: software metrics and term frequencies (text mining features). In this paper, we broaden the set of models we compare by investigating an array of techniques for the manipulation of said features. These techniques fall under the umbrella of dimensionality reduction and have the potential to improve the ability of a prediction model to localize vulnerabilities. We explore the role of dimensionality reduction through a series of cross-validation and cross-project prediction experiments. Our results show that in the case of software metrics, a dimensionality reduction technique based on confirmatory factor analysis provided an advantage when performing cross-project prediction, yielding the best F-measure for the predictions in five out of six cases. In the case of text mining, feature selection can make the prediction computationally faster, but no dimensionality reduction technique provided any other notable advantage."

# Summary. An optional shortened abstract.
summary: ""

tags: [Vulnerabilities, Security, Attribute Selection, Random Forest]
categories: []
featured: false


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
