---
title: "Edge-exchangeable graphs and sparsity"
authors:
- admin
- Trevor Campbell
- Tamara Broderick
date: "2016-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Advances in Neural Information Processing Systems (NeurIPS)
#publication_short: Advances in Neural Information Processing Systems, 2016

abstract: Many popular network models rely on the assumption of (vertex) exchangeability, in which the distribution of the graph is invariant to relabelings of the vertices. However, the Aldous-Hoover theorem guarantees that these graphs are dense or empty with probability one, whereas many real-world graphs are sparse. We present an alternative notion of exchangeability for random graphs, which we call edge exchangeability, in which the distribution of a graph sequence is invariant to the order of the edges. We demonstrate that edge-exchangeable models, unlike models that are traditionally vertex exchangeable, can exhibit sparsity. To do so, we outline a general framework for graph generative models; by contrast to the pioneering work of Caron and Fox [12], models within our framework are stationary across steps of the graph sequence. In particular, our model grows the graph by instantiating more latent atoms of a single random measure as the dataset size increases, rather than adding new atoms to the measure.

# Summary. An optional shortened abstract.
summary: In NeurIPS 2016

tags:
- publication

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/1612.05519
url_pdf: http://papers.nips.cc/paper/6586-edge-exchangeable-graphs-and-sparsity.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: http://www.dianacai.com/pdf/edge_exch_main.pdf
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: http://www.tamarabroderick.com/nips_2016_spotlight_graphs.html

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
- structured
- graphs

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

Preliminary versions appeared as:
<ul>
<li>
Completely random measures for modeling power laws in sparse graphs.
NIPS workshop on Networks in the Social and Information Sciences, 2015.
</li>
<li>
Edge-exchangeable graphs and sparsity.
NIPS workshop on Networks in the Social and Information Sciences, 2015.
</li>
<li>
Edge-exchangeable graphs, sparsity, and power laws.
NIPS Workshop on Bayesian Nonparametrics: The Next Generation, 2015.
</li>
</ul>

