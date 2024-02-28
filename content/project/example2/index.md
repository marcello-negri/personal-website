---
title: Deep Learning for Gravitational Wave Physics
summary: As a **research assistant** I developed deep learning models to emulate complex cosmological simulations and an inverse regression model to constrain the formation of binary black holes generating **gravitational waves**.

tags:
- Deep Learning
date: "2021-05-31T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: binary black holes
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

Within this project I worked as a research assistant at the **Data Analytics Lab** (ETH) in collaboration with physicists from the **University of Geneve**.
We developed two deep learning models to better understand and simulate the complex physics behind gravitational waves produced by binary black holes. 
Specifically, we developed two models: (i) an **emulator** of cosmological simulations which makes stars evolve, eventually ending up in binary black holes, and (ii) an **inverse-regression** model to constrain the origin of gravitational waves in terms of black holes channel formation. 
As a first step, we pre-processed the available data and defined **appropriate metrics** in order to accurately account for the underlying physics. 
Then we investigated the complexity of the problem by studying the contributions of **non-linear mappings** and we optimized ad-hoc mlp regressors and classifiers. 
The emulator allowed to obtain accurate simulations orders of magnitude faster while the inverse-model allowed us to develop a pipeline for experimental data (e.g. LIGO). 
Lastly, we exploited the **LIME framework** and **shapley values** to provide physical insights on the results, specifically explaining the role of each feature towards the predictions. 
This allowed us to confirm what was expected from theory but also to build new useful intuitions.
