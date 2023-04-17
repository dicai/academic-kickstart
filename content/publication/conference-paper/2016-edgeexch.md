---
title: "Edge-exchangeable graphs and sparsity"
authors:
- Diana Cai
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
summary: Many popular network models rely on the assumption of (vertex) exchangeability, in which the distribution of the graph is invariant to relabelings of the vertices. However, the Aldous-Hoover theorem guarantees that these graphs are dense or empty with probability one, whereas many real-world graphs are sparse ...

publication_detail: ISBA@NeurIPS Award at NeurIPS Workshop on Bayesian Nonparametrics

tags:
- graphs
- exchangeability
- model misspecification
- Bayesian nonparametrics

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/1612.05519
- name: BibTeX
  url: publication/conference-paper/2016-edgeexch/#citation
- name: Poster
  url: https://drive.google.com/file/d/16gkZPLOTfaZhrM4T6FwB741JNbxLBKFv/view?usp=sharing
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
- bnp

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

Preliminary versions appeared as:
1. Completely random measures for modeling power laws in sparse graphs.
_NIPS workshop on Networks in the Social and Information Sciences_, 2015.
2. Edge-exchangeable graphs and sparsity.
_NIPS workshop on Networks in the Social and Information Sciences_, 2015.
3. Edge-exchangeable graphs, sparsity, and power laws.
_NIPS Workshop on Bayesian Nonparametrics: The Next Generation_, 2015.


## Citation

Main publication:
```
@inproceedings{cai2016edge,
  title={Edge-exchangeable graphs and sparsity},
  author={Cai, Diana and Campbell, Trevor and Broderick, Tamara},
  booktitle={Advances in Neural Information Processing Systems 29},
  pages={4249--4257},
  year={2016}
}
```

Workshop papers:

```
@inproceedings{cai2015completely,
  title={Completely random measures for modeling power laws in sparse graphs},
  author={Cai, Diana and Broderick, Tamara},
  booktitle={NIPS 2015 Workshop on Networks in the Social and Information Sciences},
  year={2015}
}
```

```
@inproceedings{broderick2015edge,
  title={Edge-exchangeable graphs and sparsity},
  author={Broderick, Tamara and Cai, Diana},
  booktitle={NIPS 2015 Workshop on Networks in the Social and Information Sciences},
  year={2015}
}
```

```
@inproceedings{broderick2015edge,
  title={Edge-exchangeable graphs, sparsity, and power laws},
  author={Broderick, Tamara and Cai, Diana},
  booktitle={NIPS 2015 Workshop on Bayesian Nonparametrics: The Next Generation},
  year={2015}
}
```
