---
layout: post
share: true
title: From Captions to Visual Concepts and Back
author:
  name: Tanay Agrawal
  email: f2015567@pilani.bits-pilani.ac.in
categories:
- Captioning
tags:
- Medium
date: 2019-03-20 08:30:15 +0000

---
**Abstract:** This paper presents a novel approach for automatically generating image descriptions: visual detectors, language models, and multimodal similarity models learnt directly from a dataset of image captions. We use multiple instance learning to train visual detectors for words that commonly occur in captions, including many different parts of speech such as nouns, verbs, and adjectives. The word detector outputs serve as conditional inputs to a maximum-entropy language model. The language model learns from a set of over 400,000 image descriptions to capture the statistics of word usage. We capture global semantics by re-ranking caption candidates using sentence-level features and a deep multimodal similarity model. Our system is state-of-the-art on the official Microsoft COCO benchmark, producing a BLEU-4 score of 29.1%. When human judges compare the system captions to ones written by other people on our heldout test set, the system captions have equal or better quality 34% of the time.

**Paper link:** [https://arxiv.org/pdf/1411.4952v3.pdf](https://arxiv.org/pdf/1411.4952v3.pdf "https://arxiv.org/pdf/1411.4952v3.pdf")

**Task:**

1. Using the datasets mentioned in the paper (MS COCO and PASCAL) and the mentioned algorithm, reproduce the results of the research paper for all the given metrics.

**ID:** 102