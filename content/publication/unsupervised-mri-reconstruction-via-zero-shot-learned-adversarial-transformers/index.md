---
title: Unsupervised MRI Reconstruction via Zero-Shot Learned Adversarial Transformers
publication_types:
  - "2"
authors:
  - admin
  - Salman Ul Hassan Dar
  - Mahmut Yurt
  - Muzaffer Ozbey
  - Tolga Cukur
publication: IEEE Transactions
  on Medical Imaging; accepted, in press.
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
draft: false
featured: false
url_pdf: https://arxiv.org/pdf/2105.08059.pdf
url_code: 'https://github.com/icon-lab/SLATER'
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2021-05-21T17:52:49.650Z
---
