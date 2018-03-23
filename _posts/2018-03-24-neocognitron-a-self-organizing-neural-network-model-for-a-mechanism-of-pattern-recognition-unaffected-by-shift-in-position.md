---
layout: post
share: true
title: Neocognitron
date: 2018-03-24 03:00:53 +0000
author:
  name: Amey Agrawal
  email: agrawalamey12@gmail.com
categories:
- Computer Vision
- Antique Architectures
tags:
- Medium
- Theory
---
**Abstract**: A neural network model for a mechanism of visual pattern recognition is proposed in this paper. The network is self-organized by "learning without a teacher", and acquires an ability to recognize stimulus patterns based on the geometrical similarity (Gestalt) of their shapes without affected by their positions. This network is given a nickname "neocognitron". After completion of self-organization, the network has a structure similar to the hierarchy model of the visual nervous system proposed by Hubel and Wiesel. The network consists of an input layer (photoreceptor array) followed by a cascade connection of a number of modular structures, each of which is composed of two layers of cells connected in a cascade. The first layer of each module consists of "S-cells', which show characteristics similar to simple cells or lower order hypercomplex cells, and the second layer consists of "C-cells" similar to complex cells or higher order hypercomplex cells. The afferent synapses to each S-cell have plasticity and are modifiable. The network has an ability of unsupervised learning: We do not need any "teacher" during the process of selforganization, and it is only needed to present a set of stimulus patterns repeatedly to the input layer of the network. The network has been simulated on a digital computer. After repetitive presentation of a set of stimulus patterns, each stimulus pattern has become to elicit an output only from one of the C-cells of the last layer, and conversely, this C-cell has become selectively responsive only to that stimulus pattern. That is, none of the C-cells of the last layer responds to more than one stimulus pattern. The response of the C-cells of the last layer is not affected by the pattern's position at all. Neither is it affected by a small change in shape nor in size of the stimulus pattern. 

**PDF link:** [http://www.rctn.org/bruno/public/papers/Fukushima1980.pdf](http://www.rctn.org/bruno/public/papers/Fukushima1980.pdf "http://www.rctn.org/bruno/public/papers/Fukushima1980.pdf")

**Task:** Implement the architecture in python using Tensorflow, Pytorch, MXNet or NumPy. Train the network on MNIST and FashionMNIST.