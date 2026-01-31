---
date: 2025-04-01
publishDate: 2025-04-01
external_link: ""
summary: Our new paper on one-step generative modeling from scratch using Score-of-Mixture 
  Training (SMT) accepted as a Spotlight Poster (top 2%) at ICML 2025!
tags:
- Research
title: Score-of-Mixture Training accepted as Spotlight Poster (top 2%) at ICML 2025
links:
  - icon_pack: fas
    icon: file-pdf
    name: Poster
    url: 'icml2025-smt-poster.pdf'
  - icon_pack: fas
    icon: scroll
    name: arXiv Link
    url: 'https://arxiv.org/pdf/2502.09609'
  - icon_pack: fas
    icon: scroll
    name: Openreview Link
    url: 'https://openreview.net/forum?id=zk5k2NQcEA'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/tkj516/score-of-mixture-training'
---
Our new paper "Score-of-Mixture Training: One-Step Generative Model Training Made Simple via Score Estimation of Mixture Distributions" has been accepted as a **Spotlight Poster (top 2%)** at the 42nd International Conference on Machine Learning (ICML 2025). This is joint work with Jongha (Jon) Ryu and Gregory W. Wornell. Please refer to the links above for more information.  In this work we propose a new 
distribution matching framework grounded in minimizing the skewed Jensen-Shannon divergence between interpolated distributions that we show allows for a simple framework for training generative models from scratch (without expensive pre-training and distillation), with minimal architectural design changes and outperforms existing methods for image generative modeling from scratch.

**Abstract**

We propose Score-of-Mixture Training (SMT), a novel framework for training one-step generative models by minimizing a class of divergences called the $\alpha$-skew Jensen--Shannon divergence. At its core, SMT estimates the score of mixture distributions between real and fake samples across multiple noise levels. Similar to consistency models, our approach supports both training from scratch (SMT) and distillation using a pretrained diffusion model, which we call Score-of-Mixture Distillation (SMD). It is simple to implement, requires minimal hyperparameter tuning, and ensures stable training. Experiments on CIFAR-10 and ImageNet 64x64 show that SMT/SMD are competitive with and can even outperform existing methods.
