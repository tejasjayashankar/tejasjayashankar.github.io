---
title: "Lifted Residual Score Estimation"
date: 2024-07-01
publishDate: 2024-07-01
authors: ["**Tejas Jayashankar**", "Jongha J. Ryu", "Xiangxiang Xu", "Gregory W. Wornell"]
publication_types: ["1"]
abstract: "This paper proposes two new techniques to im-
prove the accuracy of score estimation. The first
proposal is a new objective function called the
lifted score estimation objective, which serves as
a replacement for the score matching (SM) ob-
jective. Instead of minimizing the expected l2 distance between the learned and true score mod-
els, the proposed objective operates in the lifted
space of the outer-product of a vector-valued func-
tion with itself. The distance is defined as the ex-
pected squared Frobenius norm of the difference
between such matrix-valued objects induced by
the learned and true score functions. The second
idea is to model and learn the residual approxi-
mation error of the learned score estimator, given
a base score model architecture. We empirically
demonstrate that the combination of the two ideas
called lifted residual score estimation outperforms
sliced SM in training VAE and WAE with implicit
encoders, and denoising SM in training diffusion
models, as evaluated by downstream metrics of
sample quality such as the FID score."
featured: true
publication: "2024 ICML SPIGM Workshop"
links:
  - icon_pack: fas
    icon: scroll
    name: Paper
    url: 'https://openreview.net/pdf?id=zX27NDlfcu'
---