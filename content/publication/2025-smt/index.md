---
title: "Score-of-Mixture Training: One-Step Generative Model Training Made Simple via Score Estimation of Mixture Distributions"
date: 2025-07-23
publishDate: 2025-07-23
authors: ["**Tejas Jayashankar**", "Jongha J. Ryu", "Gregory W. Wornell"]
author_notes: ["Equal contribution", "Equal contribution", ""]
publication_types: ["1"]
spotlight: true
abstract: "We propose Score-of-Mixture Training (SMT),
a novel framework for training one-step generative models by minimizing a class of divergences
called the α-skew Jensen–Shannon divergence.
At its core, SMT estimates the score of mixture
distributions between real and fake samples across
multiple noise levels. Similar to consistency models, our approach supports both training from
scratch (SMT) and distillation using a pretrained
diffusion model, which we call Score-of-Mixture
Distillation (SMD). It is simple to implement, requires minimal hyperparameter tuning, and ensures stable training. Experiments on CIFAR-10
and ImageNet 64×64 show that SMT/SMD are
competitive with and can even outperform existing methods."
featured: true
publication: "Proceedings of the 42nd International Conference on Machine Learning (ICML 2025)"
links:
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