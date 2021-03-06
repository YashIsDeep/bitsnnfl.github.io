---
layout: post
author:
  name: 'Paper ID: 93'
  email: bitsnnfl@gmail.com
share: true
title: News Text Classification based on a Weighted RNN
categories:
- NLP
- RNN
- Text Classification
tags: []

---
**Abstract** - Most of the information is stored as text, so text mining is regarded as having high commercial potential. Aiming at the semantic constraint problem of classification methods based on sparse representation, we propose a weighted recurrent neural network (W-RNN), which can fully extract text serialization semantic information. For the problem that the feature high dimensionality and unclear semantic relationship in text data representation, we first utilize the word vector to represent the vocabulary in the text and use Recurrent Neural Network (RNN) to extract features of the serialized text data. The word vector is then automatically weighed and summed using the intermediate output of the word vector to form the text representation vector. Finally, the neural network is used for classification. W-RNN is verified on the news dataset and proves that W-RNN is superior to the other four baseline methods in Precision, Recall, F1 and loss values, which is suitable for text classification.

**Paper** - [https://arxiv.org/ftp/arxiv/papers/1909/1909.13077.pdf](https://arxiv.org/ftp/arxiv/papers/1909/1909.13077.pdf "https://arxiv.org/ftp/arxiv/papers/1909/1909.13077.pdf")

**Dataset** - [http://qwone.com/\~jason/20Newsgroups/](http://qwone.com/\~jason/20Newsgroups/ "http://qwone.com/~jason/20Newsgroups/") (Use the [20news-bydate.tar.gz](http://qwone.com/\~jason/20Newsgroups/20news-bydate.tar.gz) version)

**Problem Statement -**

1. Split the training and testing set as given in the paper and then develop the model. Clearly report the number of data samples of each category in training and testing sets by generating necessary graphs in the notebook. Submit the final dataset used for the project along with the notebook.
2. Tokenize and perform word embedding of the files using the 'Word2vec' technique, as given in the paper. Make necessary and logical assumptions of parameters wherever necessary. (Feel free to use any other word embedding technique. However, state clear reasons for doing so)
3. Develop the model using Keras API of Tensorflow, and use GRU blocks as the RNN units. Use early stopping with respect to cross-validation loss as stopping criteria. (**Note** - Don't worry about the high training accuracy as mentioned in the paper. The idea is to achieve maximum testing accuracy).
4. Show comparison with replacing the GRU unit by LSTM unit in the above model and with baseline GRU-based RNN model and Bidirectional GRU based model. Clearly report the difference in terms of accuracy, the convergence rate of the loss function, and avg time per epoch.
5. Report graph of loss function & accuracy vs. epochs during training, and confusion matrix, precision, recall, F1 score, and accuracy for all three cases for the test set (in the notebook).

**Few Resources to Understand Key Concepts -**

1. Understand LSTMs and GRUs - [http://colah.github.io/posts/2015-08-Understanding-LSTMs/](http://colah.github.io/posts/2015-08-Understanding-LSTMs/ "http://colah.github.io/posts/2015-08-Understanding-LSTMs/"), [https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21 "https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21")
2. Understand CNNs - [http://cs231n.github.io/convolutional-networks/](http://cs231n.github.io/convolutional-networks/ "http://cs231n.github.io/convolutional-networks/"), [http://cs231n.github.io/understanding-cnn/](http://cs231n.github.io/understanding-cnn/ "http://cs231n.github.io/understanding-cnn/"), [https://towardsdatascience.com/understanding-cnn-convolutional-neural-network-69fd626ee7d4](https://towardsdatascience.com/understanding-cnn-convolutional-neural-network-69fd626ee7d4 "https://towardsdatascience.com/understanding-cnn-convolutional-neural-network-69fd626ee7d4")

(**Note** - These resources are just suggestive and not compulsory to go through. Feel free to explore and understand in your own way)