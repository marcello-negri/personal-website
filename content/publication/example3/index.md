---
title: "Conditional Matrix Flows for Gaussian Graphical Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Fabricio Arend Torres
- Volker Roth

# Author notes (optional)
#author_notes:
#- 
#- 
#- 

date: "2023-09-30T00:00:00Z"
doi: ""


# Publication type.
# Legend: 0 = Uncategorised; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2023*
#publication_short: In *AABI*

abstract: Studying conditional independence among many variables with few observations is a challenging task. Gaussian Graphical Models (GGMs) tackle this problem by encouraging sparsity in the precision matrix through lq regularization with q < 1. However, most GMMs rely on the l1 norm because the objective is highly non-convex for sub-l1 pseudo-norms. In the frequentist formulation, the l1 norm relaxation provides the solution path as a function of the shrinkage parameter λ. In the Bayesian formulation, sparsity is instead encouraged through a Laplace prior, but posterior inference for different λ requires repeated runs of expensive Gibbs samplers. Here we propose a general framework for variational inference with matrix-variate Normalizing Flow in GGMs, which unifies the benefits of frequentist and Bayesian frameworks. As a key improvement on previous work, we train with one flow a continuum of sparse regression models jointly for all regularization parameters λ and all lq norms, including non-convex sub-l1 pseudo-norms. Within one model we thus have access to (i) the evolution of the posterior for any λ and any lq (pseudo-) norm, (ii) the marginal log-likelihood for model selection, and (iii) the frequentist solution paths through simulated annealing in the MAP limit.
# Summary. An optional shortened abstract.
summary: We propose a general variational inference framework for Gaussian Graphical Models through matrix-variate Normalizing Flows 

tags: [Normalizing Flows, Gaussian Graphical Models, sparsity, variational inference]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=GYnbubCXhE'
url_code: 'https://github.com/marcello-negri/CMF'
url_dataset: ''
url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202023/72206.png?t=1701263669.496748'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: the proposed CMF is defined on the space of symmetric positive definite matrices by construction
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
