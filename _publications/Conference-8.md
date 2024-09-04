---
title: "Hodec: Towards efficient high-order decomposed convolutional neural networks"
collection: publications
category: conferences
permalink: /publication/Conference-8
excerpt: 'Miao Yin, Yang Sui, Wanzhao Yang, Xiao Zang, **Yu Gong**, Bo Yuan'
date: 2022/06/19
venue: 'CVPR'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2022/papers/Yin_HODEC_Towards_Efficient_High-Order_DEcomposed_Convolutional_Neural_Networks_CVPR_2022_paper.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

High-order decomposition is a widely used model compression approach towards compact convolutional neural networks (CNNs). However, many of the existing solutions, though can efficiently reduce CNN model sizes, are very difficult to bring considerable saving for computational costs, especially when the compression ratio is not huge, thereby causing the severe computation inefficiency problem. To overcome this challenge, in this paper we propose efficient High-Order DEcomposed Convolution (HODEC). By performing systematic explorations on the underlying reason and mitigation strategy for the computation inefficiency, we develop a new decomposition and computation-efficient execution scheme, enabling simultaneous reductions in computational and storage costs.
To demonstrate the effectiveness of HODEC, we perform empirical evaluations for various CNN models on different datasets. HODEC shows consistently outstanding compression and acceleration performance. For compressing ResNet-56 on CIFAR-10 dataset, HODEC brings 67% fewer parameters and 62% fewer FLOPs with 1.17% accuracy increase than the baseline model. For compressing ResNet-50 on ImageNet dataset, HODEC achieves 63% FLOPs reduction with 0.31% accuracy increase than the uncompressed model.