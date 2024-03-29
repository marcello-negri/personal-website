---
title: Vital signs and disease progression
summary: As part of **Introduction to Machine Learning** we developed a deep learning model to forecast vital signs and disease progression for hospitalized patients.

tags:
- Deep Learning
- Time Series
date: "2021-04-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: vital signs of patients
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
**Challenge**
We were given a dataset of about 17'000 patients in hospital whose vital signs, e.g. body temperature, insulin levels, blood sugar level etc, were measured over a period of 12h. In this time span, these measures led doctors to prescribe further exams (boolean variables) and further other vital signs, e.g. oxygen saturation, blood pressure and heartrate. The following 12h hours were held-out as test set and the task consisted in training a neural network with the data of the first 12h in order to predict which exams will be prescribed by doctors on the following 12h based, together with oxygen saturation, blood pressure and heartrate, based on the standard vital signs only.

**Solution**
We trained ElasticNet and MLPRegressor to forecast real-valued and boolean variables. Other important challenges were represented by **missing data** (patients' vital values are not recorded continuously while other values are not recorded at all), **importance sampling** (the proportion of patients who are prescribed with certain exams can vary greatly), **feature engineering** (some very relevant quantities are missing in the dataset, for example the temperature is given, but its difference over the 12h, which is clearly relevant to the evolution of the patient's conditions of the next 12h, is not).

Along with technical skills, I learned together with my group how to approach complicated problems as we had to visualize data, test different models such as linear regression and neural nets, make extensive use of cross-validation, perform **feature engineering** and data pre-processing to solve it. We tackled this task exploiting many techniques, **PCA**, **up-sampling**, **down-sampling**.
