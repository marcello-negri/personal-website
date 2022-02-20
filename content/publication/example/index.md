---
title: "An example conference paper"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Vincent Fortuin
- Jan Stühmer

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-11-22T00:00:00Z"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: In *Advances in Approximate Bayesian Inference*
publication_short: In *AABI*

abstract: Variational auto-encoders have proven to capture complicated data distributions and useful latent representations, while advances in meta-learning have made it possible to extract prior knowledge from data. We incorporate these two approaches and propose a novel flexible prior, namely the Pseudo-inputs prior, to obtain a richer latent space. We train VAEs using the Model-Agnostic Meta-Learning (MAML) algorithm and show that it achieves comparable reconstruction performance with standard training. However, we show that this MAML-VAE model learns richer latent representations, which we evaluate in terms of unsupervised few-shot classification as a downstream task. Moreover, we show that our proposed Pseudo-inputs prior outperforms baseline priors, including the VampPrior, in both models, while also encouraging high-level representations through its pseudo-inputs.

# Summary. An optional shortened abstract.
summary: We employ MAML to obtain richer priors for VAEs and propose a prior that encourages high-level representations

tags: [VAE, VAEs, MAML, meta-learning, VampPrior]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=y7zFbVdkP7E'
url_code: ''
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1uSB4vRZ9x1rhHzv7bHdzJR4DbCtm6TQV/view'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
