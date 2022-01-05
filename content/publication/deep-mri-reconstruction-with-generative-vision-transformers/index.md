---
title: Deep MRI Reconstruction with Generative Vision Transformers
publication_types:
  - "1"
authors:
  - Yilmaz Korkmaz
  - Mahmut Yurt
  - Salman Ul Hassan Dar
  - Muzaffer Ozbey
  - Tolga Cukur
publication: International Workshop on Machine Learning for Medical Image Reconstruction
abstract: Supervised training of deep network models for MRI reconstruction
  requires access to large databases of fully-sampled MRI acquisitions. To
  alleviate dependency on costly databases, unsupervised learning strategies
  have received interest. A powerful framework that eliminates the need for
  training data altogether is the deep image prior (DIP). To do this, DIP
  inverts randomly-initialized models to infer network parameters most
  consistent with the undersampled test data. However, existing DIP methods
  leverage convolutional backbones, suffering from limited sensitivity to
  long-range spatial dependencies and thereby poor model invertibility. To
  address these limitations, here we propose an unsupervised MRI reconstruction
  based on a novel generative vision transformer (GVTrans). GVTrans
  progressively maps low-dimensional noise and latent variables onto MR images
  via cascaded blocks of cross-attention vision transformers. Cross-attention
  mechanism between latents and image features serve to enhance representational
  learning of local and global context. Meanwhile, latent and noise injections
  at each network layer permit fine control of generated image features,
  improving model invertibility. Demonstrations are performed for scan-specific
  reconstruction of brain MRI data at multiple contrasts and acceleration
  factors. GVTrans yields superior performance to state-of-the-art generative
  models based on convolutional neural networks (CNNs).
draft: false
featured: false
image:
  filename: transformer.png
  focal_point: Smart
  preview_only: false
date: 2021-10-01T17:11:20.246Z
---
