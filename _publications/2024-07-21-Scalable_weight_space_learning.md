---
title: "Towards Scalable and Versatile Weight Space Learning"
collection: publications
permalink: /publication/2024-07-21-Scalable_weight_space_learning
excerpt: 'In this paper, we propose methods to scale weight space learning approaches to large models of varying architectures.'
date: 2024-07-21
venue: 'International Conference on Machine Learning'
paperurl: 'https://arxiv.org/abs/2406.09997'
citation: 'Schürholt et al., 2024. &quot;Towards Scalable and Versatile Weight Space Learning.&quot; <i>ICML</i> 2024.'
---

Abstract 
=====

Learning representations of well-trained neural network models holds the promise to provide an understanding of the inner workings of those models. However, previous work has either faced limitations when processing larger networks or was task-specific to either discriminative or generative tasks. This paper introduces the SANE approach to weight-space learning. SANE overcomes previous limitations by learning task-agnostic representations of neural networks that are scalable to larger models of varying architectures and that show capabilities beyond a single task. Our method extends the idea of *hyper-representations* towards sequential processing of subsets of neural network weights, thus allowing one to embed larger neural networks as a set of tokens into the learned representation space. SANE reveals global model information from layer-wise embeddings, and it can sequentially generate unseen neural network models, which was unattainable with previous *hyper-representation* learning methods. Extensive empirical evaluation demonstrates that SANE matches or exceeds state-of-the-art performance on several weight representation learning benchmarks, particularly in initialization for new tasks and larger ResNet architectures.

Bibtex: 
```
@inproceedings{sch{\"u}rholt2024towards,
title={Towards Scalable and Versatile Weight Space Learning},
author={Konstantin Sch{\"u}rholt and Michael W. Mahoney and Damian Borth},
booktitle={Forty-first International Conference on Machine Learning},
year={2024},
url={https://openreview.net/forum?id=ug2uoAZ9c2}
}
```