---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Unsupervised Source Separation via Bayesian Inference in the Latent Domain'
subtitle: 'arXiv'
summary: 'arXiv'
authors:
- admin
- Emilian Postolache
- Giorgio Mariani
- Marco Fumero
- Andrea Santilli
- Luca Cosmo
- Emanuele Rodolà
tags: []
categories: []
date: '2021-10-11'
lastmod: 2021-10-11T:26:44
featured: false
draft: false
publication_short: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-10-11T:26:44'
publication_types:
- '3'
abstract: |
  State of the art audio source separation models rely on supervised data-driven approaches, which can be expensive in terms of labeling resources. On the other hand, approaches for training these models without any direct supervision are typically high-demanding in terms of memory and time requirements, and remain impractical to be used at inference time. We aim to tackle these limitations by proposing a simple yet effective unsupervised separation algorithm, which operates directly on a latent representation of time-domain signals. Our algorithm relies on deep Bayesian priors in the form of pre-trained autoregressive networks to model the probability distributions of each source. We leverage the low cardinality of the discrete latent space, trained with a novel loss term imposing a precise arithmetic structure on it, to perform exact Bayesian inference without relying on an approximation strategy. We validate our approach on the Slakh dataset arXiv:1909.08494, demonstrating results in line with state of the art supervised approaches while requiring fewer resources with respect to other unsupervised methods.
publication: 'arXiv'
links:
- name: URL
  url : https://arxiv.org/abs/2110.05313
  
---
