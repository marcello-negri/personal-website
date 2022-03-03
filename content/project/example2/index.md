---
title: Deep Learning for Gravitational Wave Physics
summary: (Prof. Hofmann - Data Analytics Lab ETH) As a research assistant I developed deep learning models to emulate a complex cosmological simulation and an inverse regression model to constrain the formation of gravitational waves.

tags:
- Deep Learning
date: "2021-05-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
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

In collaboration with physicists from the University of Geneve, we developed two deep learning models to better undertand and simulate the complex physics behind gravitational waves produced by merging black holes. Specifically, we developed two models: (i) an emulator of cosmological simulations which evolves stars that eventually end up in merging and (ii) an inverse-regression model to constrain the origin of gravitational waves in terms of black holes channel formation. As a first step, we preprocess the available data and define appropirate metrics in order to accurately account for the underlying physics. Then we investigated the complexity of the problem by studying the contributions of non-linear mappings and we optimize ad-hoc mlp regressors and classifiers. The emulator allowed to obtain accurate simulations orders of magnitude faster while the inverse-model allowed us to develope a pipeline for experiemntal data (e.g. LIGO). Lastly, we exploited the LIME framework and shapley values to provide physical insights on the results, specifically explaining the role of each feature towards the predictions. This allowed us to confirm what was expected from theory but also to build new useful intuitions.