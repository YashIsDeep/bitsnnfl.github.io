---
layout: post
share: true
title: Sentiment Analysis Using Convolutional Neural Network
date: 2018-03-27 16:36:56 +0000
author:
  name: Shrikant Sharda
  email: f2014046@pilani.bits-pilani.ac.in
categories: []
tags: []
---
**Abstract:**

Sentiment analysis of text content is important for many natural language processing tasks. Especially, as the development of the social media, there is a big need in dig meaningful information from the big data on Internet through the sentiment analysis. Inspired by the successes of deep learning, we are interested in handling the sentiment analysis task using deep learning models. In this paper, we propose a framework called Word2vec + Convolutional Neural Network (CNN). Firstly, we use the word2vec proposed by Google to compute vector representations of words, which will be the input for the CNN. The purpose of using word2vec is to gain the vector representation of word and reflect the distance of words. That will lead to initialize the parameters at a good point of CNN, which can efficiently improve the performance of the nets in this problem. Secondly, we design a suitable CNN architecture for the sentiment analysis task. We use 3 pairs of convolutional layers and pooling layers in this architecture. To the best of our knowledge, this is the first time that a 7-layers architecture model is applied using word2vec and CNN to analyze sentences' sentiment. We also use the Parametric Rectified Linear Unit (PReLU), Normalization and Dropout technology to improve the accuracy and generalizability of our model. We test our framework in a public dataset which is the corpus of movie review excerpts that includes fives labels: negative, somewhat negative, neural, somewhat positive and positive. Our network achieves test accuracy of 45.4% in this dataset, which is a better performance than some other neural network model like Recursive Neural Network (RNN) and Matrix-Vector Recursive Neural Network (MV-RNN).

**Deliverables**: Focus on implementing the CNN. You can use pre-trained word2vec by google as done in the paper itself. Report both the graphs obtained in the paper as obtained by your code.

**Paper Link**: [http://ieeexplore.ieee.org/document/7363395/](http://ieeexplore.ieee.org/document/7363395/ "http://ieeexplore.ieee.org/document/7363395/")