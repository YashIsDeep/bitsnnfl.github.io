---
layout: post
share: true
title: Deep Learning-Based Crack Damage Detection Using Convolutional Neural Networks
date: 2018-08-24 12:30:34 +0530
author:
  name: Anmol Singhal
  email: f2015069@pilani.bits-pilani.ac.in
categories:
- Computer Vision
- Deep Learning
tags:
- Easy

---
A number of image processing techniques IPTs have been implemented for detecting civil infrastructure defects to partially replace human-conducted onsite inspections. These IPTs are primarily used to manipulate images to extract defect features, such as cracks in concrete and steel surfaces. However, the extensively varying real-world situations e.g., lighting and shadow changes can lead to challenges to the wide adoption of IPTs. To overcome these challenges, this article proposes a vision-based method using a deep architecture of convolutional neural networks CNNs for detecting concrete cracks without calculating the defect features. As CNNs are capable of learning image features automatically, the proposed method works without the conjugation of IPTs for extracting features. The designed CNN is trained on 40 K images of 256 × 256 pixel resolutions and, consequently, records with about 98% accuracy. The trained CNN is combined with a sliding window technique to scan any image size larger than 256 × 256 pixel resolutions. The robustness and adaptability of the proposed approach are tested on 55 images of 5,888 × 3,584 pixel resolutions taken from a different structure which is not used for training and validation processes under various conditions e.g., strong light spot, shadows, and very thin cracks. Comparative studies are conducted to examine the performance of the proposed CNN using traditional Canny and Sobel edge detection methods. The results show that the proposed method shows quite better performances and can indeed find concrete cracks in realistic situations.