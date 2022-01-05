---
abstract: Supervised deep learning has swiftly become a workhorse for
  accelerated MRI in recent years, offering state-of-the-art performance in
  image reconstruction from undersampled acquisitions. Training deep supervised
  models requires large datasets of undersampled and fully-sampled acquisitions
  typically from a matching set of subjects. Given scarce access to large
  medical datasets, this limitation has sparked interest in unsupervised methods
  that reduce reliance on fully-sampled ground-truth data. A common framework is
  based on the deep image prior, where network-driven regularization is enforced
  directly during inference on undersampled acquisitions. Yet, canonical
  convolutional architectures are suboptimal in capturing long-range
  relationships, and randomly initialized networks may hamper convergence. To
  address these limitations, here we introduce a novel unsupervised MRI
  reconstruction method based on zero-Shot Learned Adversarial TransformERs
  (SLATER). SLATER embodies a deep adversarial network with cross-attention
  transformer blocks to map noise and latent variables onto MR images. This
  unconditional network learns a high-quality MRI prior in a self-supervised
  encoding task. A zero-shot reconstruction is performed on undersampled test
  data, where inference is performed by optimizing network parameters, latent
  and noise variables to ensure maximal consistency to multi-coil MRI data.
  Comprehensive experiments on brain MRI datasets clearly demonstrate the
  superior performance of SLATER against several state-of-the-art unsupervised
  methods.
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - admin
author_notes: []
publication: preprint at arXiv, under second round review at IEEE Transactions
  on Medical Imaging
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Unsupervised MRI Reconstruction via Zero-Shot Learned Adversarial Transformers
doi: ""
featured: true
tags: []
projects:
  - Unsupervised MRI Reconstruction
image:
  caption: Model architecture
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2013-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
