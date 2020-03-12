---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parareal with a Learned Coarse Model for Robotic Manipulation"
authors: [Wisdom Agboh, Oliver Grainger, Daniel Ruprecht, Mehmet Dogar]
date: 2020-03-12T09:04:22+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:1912.05958 [cs.RO]"
publication_short: "arXiv:1912.05958 [cs.RO]"

abstract: "A key component of many robotics model-based planning and control algorithms is physics predictions, that is, forecasting a sequence of states given an initial state and a sequence of controls. This process is slow and a major computational bottleneck for robotics planning algorithms. Parallel-in-time integration methods can help to leverage parallel computing to accelerate physics predictions and thus planning. The Parareal algorithm iterates between a coarse serial integrator and a fine parallel integrator. A key challenge is to devise a coarse level model that is computationally cheap but accurate enough for Parareal to converge quickly. Here, we investigate the use of a deep neural network physics model as a coarse model for Parareal in the context of robotic manipulation. In simulated experiments using the physics engine Mujoco as fine propagator we show that the learned coarse model leads to faster Parareal convergence than a coarse physics-based model. We further show that the learned coarse model allows to apply Parareal to scenarios with multiple objects, where the physics-based coarse model is not applicable. Finally, We conduct experiments on a real robot and show that Parareal predictions are close to real-world physics predictions for robotic pushing of multiple objects."

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

url_pdf: https://arxiv.org/abs/1912.05958
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=wCh2o1rf-gA

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
