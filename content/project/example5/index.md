---
title: Bipartite Quantum Systems
summary: Dr. **Reiter** at **Trapped Ion Quantum Information ETH** - As part of a **semester research project** I studied how to obtain an exponential reduction of complexity for simulating bipartite quantum systems coupled to a bosonic mode.

tags:
- Computational Physics
date: "2021-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: time stamped interactions aggregated into static networks (credit A. Funel, 2021)
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
In this semester research project we study computational methods for analysing ensembles of two level systems coupled to a bosonic mode in an open system setting, which is highly relevant for simulating such systems and verifying hypothesis. When all two level systems are assumed to be identical the permutational symmetry allows to exponentially reduce the computational resources needed and lead to efficient computational solutions, implemented in the library Permutational Invariant Quantum Solver (PIQS). However, as soon as a one two level system can be distinguished from the others, the permutational symmetry is broken and the exponential complexity is recovered. In this project we showed that, in the case of bipartite system composed of two level systems belonging to two different species, the speedup is still exponential and gives a way to estimate the complexity for a more general mixed-species scenario, which is of great scientific interest.
