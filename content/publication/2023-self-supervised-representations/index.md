---
title: "Self-Supervised Representations for Singing Voice Conversion"
date: 2023-06-04
publishDate: 2023-06-04
authors: ["**Tejas Jayashankar**", "Jilong Wu", "Leda Sari", "David Kant", "Vimal Manohar", "Qing He"]
publication_types: ["1"]
abstract: "A singing voice conversion model converts a song in the voice of
an arbitrary source singer to the voice of a target singer. Recently,
methods that leverage self-supervised audio representations such
as HuBERT and Wav2Vec 2.0 have helped further the state-ofthe-art. Though these methods produce more natural and melodic
singing outputs, they often rely on confusion and disentanglement losses to render the self-supervised representations speaker
and pitch-invariant. In this paper, we circumvent disentanglement
training and propose a new model that leverages ASR fine-tuned
self-supervised representations as inputs to a HiFi-GAN neural
vocoder for singing voice conversion. We experiment with different f0 encoding schemes and show that an f0 harmonic generation
module that uses a parallel bank of transposed convolutions (PBTC)
alongside ASR fine-tuned Wav2Vec 2.0 features results in the best
singing voice conversion quality. Additionally, the model is capable
of making a spoken voice sing. We also show that a simple f0
shifting scheme during inference helps retain singer identity and
bolsters the performance of our singing voice conversion model.
Our results are backed up by extensive MOS studies that compare
different ablations and baselines."
featured: true
publication: "2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)"
links:
  - icon_pack: fas
    icon: scroll
    name: Paper
    url: 'https://ieeexplore.ieee.org/abstract/document/10097147'
  - icon_pack: fab
    icon: github
    name: Audio Samples
    url: 'https://github.com/tkj516/Self-Supervised-Singing-Voice-Conversion'
---