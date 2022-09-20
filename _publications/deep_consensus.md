---
title: "DeepConsensus: using the consensus of features from multiple layers to attain robust image classification"
collection: publications
permalink: /publication/deep_consensus
excerpt: ''
date: 2018-12-02
paperurl: 'https://arxiv.org/abs/1811.07266'
---
We consider a classifier whose test set is exposed to various perturbations that are not present in the training set. These test samples still contain enough features to map them to the same class as their unperturbed counterpart. Current architectures exhibit rapid degradation of accuracy when trained on standard datasets but then used to classify perturbed samples of that data. To address this, we present a novel architecture named DeepConsensus that significantly improves generalization to these test-time perturbations. Our key insight is that deep neural networks should directly consider summaries of low and high level features when making classifications. Existing convolutional neural networks can be augmented with DeepConsensus, leading to improved resistance against large and small perturbations on MNIST, EMNIST, FashionMNIST, CIFAR10 and SVHN datasets.

[Find paper here](https://arxiv.org/pdf/1811.07266.pdf)
