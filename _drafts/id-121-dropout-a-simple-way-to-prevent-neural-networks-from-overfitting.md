---
layout: post
author:
  name: Team NNFL
  email: bitsnnfl@gmail.com
share: true
title: "[ID:121]-Dropout: A Simple Way to Prevent Neural Networks from Overfitting"
categories:
- CNN
- Overfitting
- Classification
- 'Image Recognition '
tags: []

---
**Abstract :** Deep neural nets with a large number of parameters are very powerful machine learning systems. However, overfitting is a serious problem in such networks. Large networks are also slow to use, making it difficult to deal with overfitting by combining the predictions of many different large neural nets at test time. Dropout is a technique for addressing this problem. The key idea is to randomly drop units (along with their connections) from the neural network during training. This prevents units from co-adapting too much. During training, dropout samples from an exponential number of different “thinned” networks. At test time, it is easy to approximate the effect of averaging the predictions of all these thinned networks by simply using a single unthinned network that has smaller weights. This significantly reduces overfitting and gives major improvements over other regularization methods. We show that dropout improves the performance of neural networks on supervised learning tasks in vision, speech recognition, document classification and computational biology, obtaining state-of-the-art results on many benchmark data sets

Paper Link : [https://www.cs.toronto.edu/\~hinton/absps/JMLRdropout.pdf](https://www.cs.toronto.edu/\~hinton/absps/JMLRdropout.pdf "https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf")

Conference : ICML 2014

**Tasks:**

1. Implement the proper dataloader with any 2 data augmentation techniques.