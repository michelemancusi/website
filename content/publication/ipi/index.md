---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Accelerating transformer inference for translation via parallel decoding'
subtitle: 'ACL 2023'
summary: 'ACL 2023'
authors:
- Andrea Santilli
- Silvio Severino
- Emilian Postolache
- Valentino Maiorca
- admin
- Riccardo Marin
- Emanuele Rodolà

tags: []
categories: []
date: '2023-07-01'
lastmod: '2023-02-06T12:14:05+01:00'
featured: false
draft: false
publication_short: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-02-06T11:14:04.668002Z'
publication_types:
- '1'
abstract: 'Autoregressive decoding limits the efficiency of transformers for Machine Translation (MT). The community proposed specific network architectures and learning-based methods to solve this issue, which are expensive and require changes to the MT model, trading inference speed at the cost of the translation quality. In this paper, we propose to address the problem from the point of view of decoding algorithms, as a less explored but rather compelling direction. We propose to reframe the standard greedy autoregressive decoding of MT with a parallel formulation leveraging Jacobi and Gauss-Seidel fixed-point iteration methods for fast inference. This formulation allows to speed up existing models without training or modifications while retaining translation quality. We present three parallel decoding algorithms and test them on different languages and models showing how the parallelization introduces a speedup up to 38% w.r.t. the standard autoregressive decoding and nearly 2x when scaling the method on parallel resources. Finally, we introduce a decoding dependency graph visualizer (DDGviz) that let us see how the model has learned the conditional dependence between tokens and inspect the decoding procedure.'
publication: 'ACL 2023'
links:
- name: URL
  url : https://aclanthology.org/2023.acl-long.689/
---