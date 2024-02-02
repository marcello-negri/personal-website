---
title: "Mesh-free Eulerian Physics-Informed Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Fabricio Arend Torres
- admin
- Monika Nagy-Huber
- Maxim Samarin
- Volker Roth

# Author notes (optional)
#author_notes:
#- 
#- 
#- 

date: "2022-09-28T00:00:00Z"
doi: ""


# Publication type.
# Legend: 0 = Uncategorised; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: *Arxiv*
#publication_short: In *AABI*

abstract: Physics-informed Neural Networks (PINNs) have recently emerged as a principled way to include prior physical knowledge in form of partial differential equations (PDEs) into neural networks. Although PINNs are generally viewed as mesh-free, current approaches still rely on collocation points within a bounded region, even in settings with spatially sparse signals. Furthermore, if the boundaries are not known, the selection of such a region is difficult and often results in a large proportion of collocation points being selected in areas of low relevance. To resolve this severe drawback of current methods, we present a mesh-free and adaptive approach termed particle-density PINN (pdPINN), which is inspired by the microscopic viewpoint of fluid dynamics. The method is based on the Eulerian formulation and, different from classical mesh-free method, does not require the introduction of Lagrangian updates. We propose to sample directly from the distribution over the particle positions, eliminating the need to introduce boundaries while adaptively focusing on the most relevant regions. This is achieved by interpreting a non-negative physical quantity (such as the density or temperature) as an unnormalized probability distribution from which we sample with dynamic Monte Carlo methods. The proposed method leads to higher sample efficiency and improved performance of PINNs. These advantages are demonstrated on various experiments based on the continuity equations, Fokker-Planck equations, and the heat equation.

# Summary. An optional shortened abstract.
summary: We propose a truly mesh free approach for PINNs by sampling directly from the modelled density that is applicable in unbounded or unknown domains and scales to high dimensional setting

tags: [PINNs, MCMC, mesh-free, PDEs, fluid-dynamics]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2206.01545'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: temperature predictions for heat equation (a) Ground truth (b) uniform sampling, and (c) proposed pdPINN
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
