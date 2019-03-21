---
layout: post
share: true
title: 'WESPE: Weakly Supervised Photo Enhancer for Digital Cameras'
author:
  name: Suvigya VIjay
  email: f2015606@pilani.bits-pilani.ac.in
categories:
- CNN
tags:
- Medium
date: 2019-03-21 13:47:49 +0000

---
**Abstract:** Low-end and compact mobile cameras demonstrate limited photo quality mainly due to space, hardware and budget constraints. In this work, we propose a deep learning solution that translates photos taken by cameras with limited capabilities into DSLR-quality photos automatically. We tackle this problem by introducing a weakly supervised photo enhancer (WESPE) – a novel image-to-image Generative Adversarial Network-based architecture. The proposed model is trained by under weak supervision: unlike previous works, there is no need for strong supervision in the form of a large annotated dataset of aligned original/enhanced photo pairs. The sole requirement is two distinct datasets: one from the source camera, and one composed of arbitrary high-quality images that can be generally crawled from the Internet – the visual content they exhibit may be unrelated. Hence, our solution is repeatable for any camera: collecting the data and training can be achieved in a couple of hours. In this work, we emphasize on extensive evaluation of obtained results. Besides standard objective metrics and subjective user study, we train a virtual rater in the form of a separate CNN that mimics human raters on Flickr data and use this network to get reference scores for both original and enhanced photos. Our experiments on the DPED, KITTI and Cityscapes datasets as well as pictures from several generations of smartphones demonstrate that WESPE produces comparable or improved qualitative results with state-of-the-art strongly supervised methods.

**Paper Link:** [https://arxiv.org/pdf/1709.01118.pdf](https://arxiv.org/pdf/1709.01118.pdf "https://arxiv.org/pdf/1709.01118.pdf")

1. Implement the architecture given in the paper using Keras with Tensorflow as backend.
2. Use MobileNetV2 as feature extractor rather than VGG19 as prescribed.
3. Conduct the Flickr Faves Score on Cityscapes dataset.

**ID:** 94