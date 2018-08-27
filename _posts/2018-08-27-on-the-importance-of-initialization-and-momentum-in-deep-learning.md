---
layout: post
share: true
title: On the importance of initialization and momentum in deep learning
date: 2018-08-27 17:56:09 +0530
author:
  name: Sahaj Srivastava
  email: f2015091@pilani.bits-pilani.ac.in
categories:
- Deep Learning
tags:
- Easy

---
Deep and recurrent neural networks (DNNs and RNNs respectively) are powerful models that were considered to be almost impossible to train using stochastic gradient descent with momentum.  In this paper, we show that when stochastic gradient descent with momentum uses a well-designed random initialization and a particular type of slowly increasing schedule for the momentum parameter, it can train both DNNs and RNNs (on datasets with long-term dependencies) to levels of performance that were previously achievable only with Hessian-Free optimization.  We find that both the initialization and the momentum are crucial since poorly initialized networks cannot be trained with momentum and well-initialized networks perform markedly worse when the momentum is absent or poorly tuned.

Our success training these models suggests that previous attempts to train deep and recurrent neural networks from random initializations have likely failed due to poor initialization schemes.  Furthermore, carefully tuned momentum methods suce for dealing with the curvature issues in deep and recurrent network training objectives without the need for sophisticated second-order methods.

Link : [http://proceedings.mlr.press/v28/sutskever13.pdf](http://proceedings.mlr.press/v28/sutskever13.pdf "http://proceedings.mlr.press/v28/sutskever13.pdf")

ID : 83