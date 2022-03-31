---
title: MSc Thesis - "Meta-learning richer priors for VAEs"
summary: Prof. **Rätsch** at **Biomedical Informatics ETH** - In my MSc thesis I worked at the interface between **variational auto-encoders** and **meta-learning** with the aim of find better and richer priors.

tags:
- Deep Learning
date: "2021-11-23T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Pseudo-inputs prior
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

I developed my MSc thesis at the ETH at the department of Biomedical Informatics supervised by Prof. G. Rätsch and co-supervised by Dr. V. Fortuin and Dr. J. Stühmer. In my project I studied on **image datasets** how meta-learning can be beneficial to variational auto-encoders and I proposed two priors that allow to achieve better performances. Specifically, I showed that the two priors lead to better bounds for VAEs and to **richer latent representations**, even more so when the model is trained in **meta-learning** fashion with the MAML algorithm. In addition, meta-learning allows to
achieve higher accuracy in unsupervised **few-shots classification**, evaluated as a downstream task of prototypical networks. Lastly, I studied the behaviour of the proposed priors in **transfer and continual learning** settings. This experience has been particularly rewarding as the **paper** I wrote from my thesis has been **accepted** at the Advances in Approximate Bayesian Inference (AABI) 2022 symposium.
