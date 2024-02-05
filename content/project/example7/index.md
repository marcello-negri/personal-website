---
title: Hack4Good for Human Rights Watch - Remote detection of village burnings in Darfur, Sudan
summary: As part of the project Hack4Good (ETH) we helped Human Rights Watch developing a software to detect and monitor active fires in Darfur, Sudan

tags:
- Time Series
date: "2023-12-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  the solution proposed
  focal_point: Smart

links:
#  icon: twitter
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

**Project motivation**
# On April 15, 2023, fighting in Sudan's capital, Khartoum, between the Sudan Armed Forces (SAF) and the Rapid Support Forces (RSF), rapidly spread throughout the country. SAF leader Gen. Abdelfattah al-Burhan and RSF leader Gen. Mohamed Hamdan Dagalo, known as "Hemedti" had jointly carried out a coup against the country's transitional government in October 2021. Both forces have a history of violating international humanitarian and human rights law, notably in Darfur and during crackdowns against protesters. In 2022, the trial of Ali Kosheib, a former Janjaweed militia leader, charged with 31 counts of war crimes and crimes against humanity, began at the International Criminal Court. Arrest warrants against ex-president Omar al-Bashir and two of his associates remain outstanding.

# More information by Human Rights Watch on the conflict can be found [here](https://www.hrw.org/news/2023/07/11/sudan-darfur-town-destroyed) and [here](https://www.hrw.org/news/2023/08/04/sudan-new-attacks-darfur).

**Data**
We make use of two main datasets: 
# - Satellite data on fire by [NASA FIRMS](https://firms.modaps.eosdis.nasa.gov/), which covers the whole globe roughly every three hours
# - Settlement data by [Grid3](https://data.grid3.org/datasets/GRID3::sudan-settlement-extents-version-02/about) also obtained from satellite images (using semantic segmentation) 

**Telegram Bot**
As part of the project we developed a Telegram Bot that allows to keep track of burning settlements.
We developed an alert score to flag the most relevant ones. 
# The Telegram Bot can be found under `darfur_bot` or [here](https://web.telegram.org/k/#@darfur_bot).
# In order to monitor the Darfur region consistently we created a Telegram channel that provides daily updates on the flagged settlements. 
# At this point the Telegram channel is private and access can be granted individually upon request.
