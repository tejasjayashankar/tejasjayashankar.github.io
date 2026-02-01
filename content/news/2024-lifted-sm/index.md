---
date: 2024-07-01
publishDate: 2024-07-01
external_link: ""
# image:
#   caption: MAICoS logo
#   focal_point: Smart
# slides: example  https://hugoblox.com/blocks/slider/
summary: Recent work on improved score-estimation for diffusion models and implicit models presented at ICML SPIGM Workshop 2024
title: Recent work on improved score-estimation for diffusion models and implicit models accepted at ICML SPIGM Workshop 2024!
#url_code: "https://gitlab.com/maicos-devel/maicos/-/tree/release-0-7"
links:
  - icon_pack: fas
    icon: scroll
    name: Openreview Link
    url: 'https://openreview.net/pdf?id=zX27NDlfcu'
---
Score estimators lie at the heart of modern generative models, enabling the design and
training of the latest generation of diffusion models based on Gaussian noise corruption
processes.  In this work we propose a new technique for learning the score of an 
underlying probability measure by defining a new objective in the lifted space of matrix
valued objects.  We show that this new objective can be optimized without any additional
computational or memory overhead than existing score matching objectives.  Moreover, we
empirically demonstrate that the resulting method can lead to improvements in FID for
generative modeling using diffusion models on the CIFAR-10 dataset and for implicit
models trained on the CelebA dataset. 

**Abstract**

This paper proposes two new techniques to improve the accuracy of score estimation. The first
proposal is a new objective function called the lifted score estimation objective, which serves as
a replacement for the score matching (SM) objective. Instead of minimizing the expected l2-distance 
between the learned and true score models, the proposed objective operates in the lifted
space of the outer-product of a vector-valued function with itself. The distance is defined as the expected squared Frobenius norm of the difference between such matrix-valued objects induced by the learned and true score functions. The second
idea is to model and learn the residual approximation error of the learned score estimator, given
a base score model architecture. We empirically demonstrate that the combination of the two ideas
called lifted residual score estimation outperforms sliced SM in training VAE and WAE with implicit
encoders, and denoising SM in training diffusion models, as evaluated by downstream metrics of
sample quality such as the FID score.