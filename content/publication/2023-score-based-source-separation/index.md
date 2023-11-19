---
title: "Score-based Source Separation with Applications to Digital Communication Signals"
date: 2023-06-26
publishDate: 2023-06-26
authors: ["**Tejas Jayashankar**", "Gary C.F. Lee", "Alejandro Lancho", "Amir Weiss", "Yury Polyanksiy", "Gregory Wornell"]
publication_types: ["1"]
abstract: "We propose a new method for separating superimposed sources using diffusion-based generative models. Our method relies only on separately trained statistical priors of independent sources to establish a new objective function guided by maximum a posteriori estimation with an \\alpha-posterior, across multiple levels of Gaussian smoothing. Motivated by applications in radio-frequency (RF) systems, we are interested in sources with underlying discrete nature and the recovery of encoded bits from a signal of interest, as measured by the bit error rate (BER). Experimental results with RF mixtures demonstrate that our method results in a BER reduction of 95% over classical and existing learning-based methods. Our analysis demonstrates that our proposed method yields solutions that asymptotically approach the modes of an underlying discrete distribution. Furthermore, our method can be viewed as a multi-source extension to the recently proposed score distillation sampling scheme, shedding additional light on its use beyond conditional sampling."
featured: true
publication: "37th Conference on Neural Information Processing Systems (NeurIPS 2023)"
links:
  - icon_pack: fas
    icon: scroll
    name: arXiv Link
    url: 'https://arxiv.org/pdf/2306.14411.pdf'
  - icon_pack: fas
    icon: scroll
    name: Openreview Link
    url: 'https://openreview.net/pdf?id=BFGQQKicuu'
  - icon_pack: fab
    icon: browser
    name: Project Webpage
    url: 'https://github.com/tkj516/score_based_source_separation'
  - icon_pack: fab
    icon: github
    name: Code
    url: 'https://github.com/tkj516/score_based_source_separation'
---