---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Exploiting Music Source Separation For Singing Voice Detection'
subtitle: 'MLSP 2023'
summary: 'MLSP 2023'
authors:
- admin
- Francesco Bonzi
- Simone Del Deo
- Pierfrancesco Melucci
- Maria Stella Tavella
- Loreto Parisi
- Emanuele Rodolà
tags: []
categories: []
date: '2024-04-16'
lastmod: 2023-09-17T:26:44
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
publishDate: '2024-09-17T:26:44'
publication_types:
- '1'
abstract: |
  Singing voice detection (SVD) is an essential task in many music information retrieval (MIR) applications. Deep learning methods have shown promising results for SVD, but further performance improvements are desirable since it underlies many other tasks. This work proposes a novel SVD system combining a state-of-the-art music source separator (Demucs) with two downstream models: Long-term Recurrent Convolutional Network (LRCN) and a Transformer network. Our work highlights two main aspects: the impact of a music source separation model, such as Demucs, and its zero-shot capabilities for the SVD task; and the potential for deep learning to improve the system’s performance further. We evaluate our approach on three datasets (Jamendo Corpus, MedleyDB, and MIR-IK) and compare the performance of the two models to a baseline root mean square (RMS) algorithm and the current state-of-the-art for the Jamendo Corpus dataset.
publication: 'MLSP 2023'
links:
- name: URL
  url : https://ieeexplore.ieee.org/abstract/document/10285863
  
---
