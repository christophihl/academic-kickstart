---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Melanoma detection with electrical impedance spectroscopy and dermoscopy using joint deep learning models"
authors:
- Nils Gessert
- Marcel Bengs
- schlaefer
date: 2020-02-05T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-05T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "[arXiv:1911.02322v2](https://arxiv.org/abs/1911.02322v2)"
publication_short: "[arXiv:1911.02322v2](https://arxiv.org/abs/1911.02322v2)"

abstract: "The initial assessment of skin lesions is typically based on dermoscopic images. As this is a difficult and time-consuming task, machine learning methods using dermoscopic images have been proposed to assist human experts. Other approaches have studied electrical impedance spectroscopy (EIS) as a basis for clinical decision support systems. Both methods represent different ways of measuring skin lesion properties as dermoscopy relies on visible light and EIS uses electric currents. Thus, the two methods might carry complementary features for lesion classification. Therefore, we propose joint deep learning models considering both EIS and dermoscopy for melanoma detection. For this purpose, we first study machine learning methods for EIS that incorporate domain knowledge and previously used heuristics into the design process. As a result, we propose a recurrent model with state-max-pooling which automatically learns the relevance of different EIS measurements. Second, we combine this new model with different convolutional neural networks that process dermoscopic images. We study ensembling approaches and also propose a cross-attention module guiding information exchange between the EIS and dermoscopy model. In general, combinations of EIS and dermoscopy clearly outperform models that only use either EIS or dermoscopy. We show that our attention-based, combined model outperforms other models with specificities of 34.4% (CI 31.3-38.4), 34.7% (CI 31.0-38.8) and 53.7% (CI 50.1-57.6) for dermoscopy, EIS and the combined model, respectively, at a clinically relevant sensitivity of 98%."

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

url_pdf: https://arxiv.org/abs/1911.02322v2
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
