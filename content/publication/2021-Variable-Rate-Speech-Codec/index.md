---
title: "Architecture for Variable Bitrate Neural Speech Codec with Configurable Computation Complexity"
date: 2022-05-23
publishDate: 2022-05-23
authors: ["**Tejas Jayashankar**", "Thilo Koehler", "Kaustubh Kalgaonkar", "Zhiping Xiu", "Jilong Wu", "Ju Lin", "Prabhav Agrawal", "Qing He"]
publication_types: ["1"]
abstract: "Low bitrate speech codecs have become an area of intense research. Traditional speech codecs, which use signal processing methods to encode and decode speech, often suffer from quality issues at low bitrates. A neural speech codec, which uses a deep neural network in the compression pipeline, can help alleviate this issue. In this paper we present a new neural speech codec that: 1) supports variable bitrates 2) supports packet losses of up to 120 ms and 3) can operate at low-compute and high-compute modes. Our codec uses a hierarchical VQ-VAE (HVQVAE) for encoding and decoding spectral features at different bitrates. The decoded features are fed to a vocoder for speech synthesis. Depending upon the end user’s computing resources, the decoder either uses a powerful WaveRNN or a parametric vocoder for speech synthesis. Our experiments demonstrate that our HVQVAE + WaveRNN setup achieves high audio quality."
featured: true
publication: "2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)"
links:
  - icon_pack: fas
    icon: scroll
    name: Paper
    url: 'https://ieeexplore.ieee.org/abstract/document/9747419'
---