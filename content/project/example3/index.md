---
title: Semester research project - Optimal Time Window for Time-Stamped Interactions
summary: Prof. **Schweitzer** at **Systems Design ETH** - As part of a **semester research project** I developed a mathematical framework to identify the optimal time window to aggregate time stamped interactions into a sequence of static networks.

tags:
- Time Series
date: "2021-03-01T00:00:00Z"

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

In this semester research project, we followed a two-fold approach. First, time-stamped interactions are aggregated according to a specified **time window** size, leading to a sequence of static aggregated networks. Second, **relations** are extracted from each aggregated network. The main challenge is that relations between system elements may change over time and the choice of the time window size is crucial to distinguish meaningful topological changes from **random fluctuations**. We overcome this problem by identifying **regularities** in the sequence of aggregated networks at different time windows, specifically by measuring the **similarity** between consecutive networks. This allows us not only to find the optimal time window size but also to identify precisely the **timescales** at which relations between agents change. This project has been particularly rewarding as we are currently continuing our collaboration to publish my work, which will be likely submitted to **Nature Communications**.
