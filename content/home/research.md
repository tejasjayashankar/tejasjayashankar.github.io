---
active: false
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# This file represents a page section.
headless: false

# Order that this section appears on the page.
weight: 25

title: Research Interests
subtitle:

content:
  # Filter on criteria
  filters:
    folders:
      - blog
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 3
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  view: compact
  columns: '2'
---

One of my current interests is the theoretical and applied study of diffusion
models.  I am currently working on improved techniques for score estimation to improve
the quality (sample quality and likelihood) of diffusion models and implicit models.  I am
also interested in new methods for one-step generative modeling using novel diffusion 
distillation techniques based on maximum mean discrepancy (MMD). I am also interested and 
have applied diffusion models for solving inverse problems, such as those based on structured additive 
noise forward processes. I am also working on efforts that involve the distributed training
of large scale transformer architectures across multiple H100 GPUs for signal source
separation. 

At the same time, I have also been doing research on new representation learning
techniques that can leverage spectral decomposition techniques for applications to
progressive image decoding and variable bitrate compression. Another application of such
representation learning techniques is data attribution in neural network architectures such
as transformer-based LLMs or CNNs. During my Masters, I developed 
a new architecture for lossless and lossy image compression by designing a novel algorithm 
for compression with model-code separated compression 
architectures (i.e., source-agnostic encoding and source augmentable decoding). During my
time at UIUC, I worked on developing new video frame interpolation technology by leveraging 
the Local All-Pass (LAP) optical flow estimation algorithm.