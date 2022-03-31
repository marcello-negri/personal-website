---
title: BSc Thesis - "Machine Learning for di-tau invariant mass reconstruction in ATLAS"
summary: Prof. **Andreazza** at **Università Studi Milano** - In my BSc thesis I exploited a Boosted Regreion Tree and a Neural Network to reconstruct the mass of the Higgs boson from its decay into tu leptons.

tags:
- Deep Learning
date: "2019-07-22T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: AUC comparison
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

The existing methods to reconstruct the Higgs boson mass from its tau channel exploit either a partially reconstructed mass or the collinear approximation. Recently, the Missing Mass Calculator technique (MMC) overcame these limitations by minimising an event likelihood. In my thesis I discussed two alternative solutions that exploit machine learning techniques. These techniques are competitive with the MMC in terms of performance, evaluated in terms of the **Area Under the Curve (AUC)**, and have the advantage of being faster to compute. Firstly, I reproduced the results achieved by the Simon Fraser University group with a **Boosted Regression Tree** (BRT) through the Di-TauMassSKL package. Secondly, I enhanced the package capabilities by exploiting a **Deep Neural Network** (DNN), improving on the BRT's results and achieving **state-of-the-art** results compared to the parametric method MMC.
