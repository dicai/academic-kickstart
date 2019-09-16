---
title: "Finite mixture models are typically inconsistent for the number of components"
authors:
- admin
- Trevor Campbell
- Tamara Broderick
date: "2019-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Preprint, 2019
#publication_short: NeurIPS, 2018

abstract: Scientists and engineers are often interested in learning the number of subpopulations (or clusters) present in a data set. It is common to use a Dirichlet process mixture model (DPMM) for this purpose. But Miller and Harrison (2013) warn that the DPMM posterior is severely inconsistent for the number of clusters when the data are truly generated from a finite mixture; that is, the posterior probability of the true number of clusters goes to zero in the limit of infinite data. A potential alternative is to use a finite mixture model (FMM) with a prior on the number of clusters. Past work has shown the resulting posterior in this case is consistent. But these results crucially depend on the assumption that the cluster likelihoods are perfectly specified. In practice, this assumption is unrealistic, and empirical evidence (Miller and Dunson, 2018) suggests that the posterior on the number of clusters is sensitive to the likelihood choice. In this paper, we prove that under even the slightest model misspecification, the FMM posterior on the number of components is also severely inconsistent. We support our theory with empirical results on simulated and real data sets.

# Summary. An optional shortened abstract.
summary:

tags:
- probmodeling
featured: false

links:
- name: arXiv
  url: http://example.org
url_pdf: www.example.com/asdf.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

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
- probmodeling

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<i>Preliminary version in NeurIPS Workshop on Advances in Approximate Bayesian Inference (AABI).</i>

