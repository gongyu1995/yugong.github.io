---
title: "Co-Exploring Structured Sparsification and Low-Rank Tensor Decomposition for Compact DNNs"
collection: publications
category: manuscripts
permalink: /publication/Journal-1
excerpt: 'Yang Sui, Miao Yin, **Yu Gong**, Bo Yuan.'
date: 2024-06-27
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
slidesurl: 
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10574865'
# citation: 'Yang Sui, Miao Yin, **Yu Gong**, Bo Yuan. Co-Exploring Structured Sparsification and Low-Rank Tensor Decomposition for Compact DNNs[J]. IEEE Transactions on Neural Networks and Learning Systems, 2024.'
---

Sparsification and low-rank decomposition are two important techniques to compress deep neural network (DNN) models. To date, these two popular yet distinct approaches are typically used in separate ways; while their efficient inte- gration for better compression performance is little explored, especially for structured sparsification and decomposition. In this article, we perform systematic co-exploration on structured sparsification and decomposition toward compact DNN models. We first investigate and analyze several important design factors for joint structured sparsification and decomposition, including operational sequence, decomposition format, and optimization procedure. Based on the observations from our analysis, we then propose CEPD, a unified DNN compression framework that can co-explore the benefits of structured sparsification and tensor decomposition in an efficient way. Empirical experiments demonstrate the promising performance of our proposed solution. Notably, on the CIFAR-10 dataset, CEPD brings 0.72%–0.45% accuracy increase over the baseline ResNet-56 and MobileNetV2 models, respectively, and meanwhile, the computational costs are reduced by 43.0%–44.2%, respectively. On the ImageNet dataset, our approach can enable 0.10%–1.39% accuracy increase over the baseline ResNet-18 and ResNet-50 models with 59.4%–54.6% fewer parameters, respectively.