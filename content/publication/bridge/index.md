---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Latent Diffusion Bridges for Unsupervised Musical Audio Timbre Transfer'
subtitle: 'ICASSP 2025'
summary: 'ICASSP 2025'
authors:
- admin
- Yurii Halychanskyi
- Kin Wai Cheuk
- Eloi Moliner
- Chieh-Hsin Lai
- Stefan Uhlich
- Junghyun Koo
- Marco A. Martinez-Ramirez
- Wei-Hsiang Liao
- Giorgio Fabbro
- Yuki Mitsufuji

tags: []
categories: []
date: 
lastmod: 2024-12-25T:26:44
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
publishDate: '2024-10-09T:26:44'
publication_types:
- '3'
abstract: |
  Music timbre transfer is a challenging task that involves modifying the timbral characteristics of an audio signal while preserving its melodic structure. In this paper, we propose a novel method based on dual diffusion bridges, trained using the CocoChorales Dataset, which consists of unpaired monophonic single-instrument audio data. Each diffusion model is trained on a specific instrument with a Gaussian prior. During inference, a model is designated as the source model to map the input audio to its corresponding Gaussian prior, and another model is designated as the target model to reconstruct the target audio from this Gaussian prior, thereby facilitating timbre transfer. We compare our approach against existing unsupervised timbre transfer models such as VAEGAN and Gaussian Flow Bridges (GFB). Experimental results demonstrate that our method achieves both better Fréchet Audio Distance (FAD) and melody preservation, as reflected by lower pitch distances (DPD) compared to VAEGAN and GFB. Additionally, we discover that the noise level from the Gaussian prior, σ, can be adjusted to control the degree of melody preservation and amount of timbre transferred.
publication: 'ICASSP 2025'
links:
- name: URL
  url : https://arxiv.org/abs/2409.06096
  
---
