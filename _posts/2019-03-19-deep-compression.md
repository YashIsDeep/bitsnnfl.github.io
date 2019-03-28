---
layout: post
share: true
title: 'Deep Compression (Paper ID: 21)'
author:
  name: Aditya Rana
  email: f2016182@pilani.bits-pilani.ac.in
categories:
- Architecture
tags:
- Hard
date: 2019-03-19 06:21:58 +0000

---
**Abstract:** Neural networks are both computationally intensive and memory intensive, making them difficult to deploy on embedded systems with limited hardware resources. To address this limitation, we introduce “deep compression”, a three stage pipeline: pruning, trained quantization and Huffman coding, that work together to reduce the storage requirement of neural networks by 35× to 49× without affecting their accuracy. Our method first prunes the network by learning only the important connections. Next, we quantize the weights to enforce weight sharing, finally, we apply Huffman coding. After the first two steps we retrain the network to fine tune the remaining connections and the quantized centroids. Pruning, reduces the number of connections by 9× to 13×; Quantization then reduces the number of bits that represent each connection from 32 to 5. On the ImageNet dataset, our method reduced the storage required by AlexNet by 35×, from 240MB to 6.9MB, without loss of accuracy. Our method reduced the size of VGG-16 by 49× from 552MB to 11.3MB, again with no loss of accuracy. This allows fitting the model into on-chip SRAM cache rather than off-chip DRAM memory. Our compression method also facilitates the use of complex neural networks in mobile applications where application size and download bandwidth are constrained. Benchmarked on CPU, GPU and mobile GPU, compressed network has 3× to 4× layer-wise speedup and 3× to 7× better energy efficiency.

**Paper Link:** [https://pdfs.semanticscholar.org/5b6c/9dda1d88095fa4aac1507348e498a1f2e863.pdf](https://pdfs.semanticscholar.org/5b6c/9dda1d88095fa4aac1507348e498a1f2e863.pdf)

**Task:**

1. Implement the network architecture (AlexNet or VGG - choose any one) explained in the paper in python using TensorFlow, PyTorch or Keras.
2. The above implementation uses ImageNet dataset but you are to test your implementation on the CIFAR-10 dataset.
3. Compare the size of your model with that of general AlexNet/VGG-Net architecture.

**ID :** 21