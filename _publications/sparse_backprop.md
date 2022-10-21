---
title: "Sparse Fourier Backpropagation in Cryo-EM Reconstruction"
collection: publications
permalink: /publication/sparse_backprop
excerpt: ''
date: 2022-05-26
venue: 'NeurIPS 2022'
paperurl: ''
---
**Authors**: Dari Kimanius, Kiarash Jamali, and Sjors H.W. Scheres

Cryogenic electron microscopy (cryo-EM) is a powerful method for investigating the structures of protein molecules, with important implications for understanding the molecular processes of life and drug development. In this technique, many noisy, two-dimensional projection images of protein molecules in unknown poses are combined into one or more three-dimensional reconstructions. The presence of multiple structural states in the data represents a major bottleneck in existing processing pipelines, often requiring expert user supervision. Variational auto-encoders (VAEs) have recently been proposed as an attractive means of learning the data manifold for data sets with a large number of different states. These methods are based on a coordinate-based approach, similar to Neural Radiance Fields (NeRF), to make volumetric reconstructions from 2D image data in Fourier space. Although NeRF is a powerful method for real-space reconstruction, many of the benefits of the method do not transfer to Fourier space, e.g. inductive bias for spacial locality. We present an approach where the VAE reconstruction is expressed on a volumetric grid, and demonstrate how such a model can be trained efficiently through a novel backpropagation protocol that exploits the sparsity of the projection operation in Fourier space. Comparing to the coordinate-based approach, we achieve improved results for an experimental dataset with multiple structural states. Moreover, our approach is computationally more efficient, especially in inference, enabling interactive analysis of latent space by the user.

[Find paper here](https://nips.cc/Conferences/2022/Schedule?showEvent=52953)
