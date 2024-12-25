---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'High-Resolution Speech Restoration with Latent Diffusion Model'
subtitle: 'ICASSP 2025'
summary: 'ICASSP 2025'
authors:
- Tushar Dhyani
- Florian Lux
- admin
- Giorgio Fabbro
- Fritz Hohl
- Ngoc Thang Vu

tags: []
categories: []
date: 
lastmod: 2024-09-17T:26:44
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
- '3'
abstract: |
  Traditional speech enhancement methods often oversimplify the task of restoration by focusing on a single type of distortion. Generative models that handle multiple distortions frequently struggle with phone reconstruction and high-frequency harmonics, leading to breathing and gasping artifacts that reduce the intelligibility of reconstructed speech. These models are also computationally demanding, and many solutions are restricted to producing outputs in the wide-band frequency range, which limits their suitability for professional applications. To address these challenges, we propose Hi-ResLDM, a novel generative model based on latent diffusion designed to remove multiple distortions and restore speech recordings to studio quality, sampled at 48kHz. We benchmark Hi-ResLDM against state-of-the-art methods that leverage GAN and Conditional Flow Matching (CFM) components, demonstrating superior performance in regenerating high-frequency-band details. Hi-ResLDM not only excels in non-instrusive metrics but is also consistently preferred in human evaluation and performs competitively on intrusive evaluations, making it ideal for high-resolution speech restoration.
publication: 'ICASSP 2025'
links:
- name: URL
  url : https://arxiv.org/abs/2409.11145
  
---
