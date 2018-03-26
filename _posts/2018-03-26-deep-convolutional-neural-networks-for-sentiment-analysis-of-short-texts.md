---
layout: post
share: true
title: Deep Convolutional Neural Networks for Sentiment Analysis of Short Texts
date: 2018-03-26 16:52:58 +0000
author:
  name: Jai Agarwal
  email: f2014428@pilani.bits-pilani.ac.in
categories:
- Natural Language Processing
tags:
- Medium
---
**Abstract:** Sentiment analysis of short texts such as single sentences and Twitter messages is challenging because of the limited contextual information that they normally contain. Effectively solving this task requires strategies that combine the small text content with prior knowledge and use more than just bag-of-words. In this work we propose a new deep convolutional neural network that exploits from character- to sentence-level information to perform sentiment analysis of short texts. We apply our approach for two corpora of two different domains: the Stanford Sentiment Treebank (SSTb), which contains sentences from movie reviews; and the Stanford Twitter Sentiment corpus (STS), which contains Twitter messages. For the SSTb corpus, our approach achieves state-of-the-art results for single sentence sentiment prediction in both binary positive/negative classification, with 85.7% accuracy, and fine-grained classification, with 48.3% accuracy. 

**Paper Link**: [https://pdfs.semanticscholar.org/b0ac/a3e7877c3c20958b0fae5cbf2dd602104859.pdf](https://pdfs.semanticscholar.org/b0ac/a3e7877c3c20958b0fae5cbf2dd602104859.pdf "https://pdfs.semanticscholar.org/b0ac/a3e7877c3c20958b0fae5cbf2dd602104859.pdf")

**Task:** Implement the CharSCNN architecture in Python using Tensorflow, Pytorch, Theano, MXNet or NumPy. Train the network on SSTb dataset.