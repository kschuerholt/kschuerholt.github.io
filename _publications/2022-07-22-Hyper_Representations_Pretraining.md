---
title: "Hyper-Representation for Pre-Training and Transfer Learning"
collection: publications
permalink: /publication/2022-07-22-Hyper_Representations_Pretraining
excerpt: 'In this paper, we extend hyper-representations for generative use to sample neural network weights for initialization and transfer learning.'
date: 2022-10-01
venue: 'International Conference on Machine Learning (ICML) Pretraining Workshop 2022'
paperurl: 'https://arxiv.org/abs/2207.10951'
citation: 'Schürholt et al., 2022. &quot;Hyper-Representation for Pre-Training and Transfer Learning.&quot; <i>ICML Pretraining Workshop</i> 2022.'
---
Learning representations of neural network weights given a model zoo is an emerging and challenging area with many potential applications from model inspection, to neural architecture search or knowledge distillation. Recently, an autoencoder trained on a model zoo was able to learn a hyper-representation, which captures intrinsic and extrinsic properties of the models in the zoo. In this work, we extend hyper-representations for generative use to sample new model weights. We propose layer-wise loss normalization which we demonstrate is key to generate high-performing models and several sampling methods based on the topology of hyper-representations. The models generated using our methods are diverse, performant and capable to outperform strong baselines as evaluated on several downstream tasks: initialization, ensemble sampling and transfer learning. Our results indicate the potential of knowledge aggregation from model zoos to new models via hyper-representations thereby paving the avenue for novel research directions. 

[Download paper here](https://arxiv.org/abs/2207.10951)

Bibtex: 
@inproceedings{
sch{\"u}rholt2022hyperrepresentation,
title={Hyper-Representation for Pre-Training and Transfer Learning},
author={Konstantin Sch{\"u}rholt and Boris Knyazev and Xavier Gir{\'o}-i-Nieto and Damian Borth},
booktitle={First Workshop on Pre-training: Perspectives, Pitfalls, and Paths Forward at ICML 2022},
year={2022},
url={https://arxiv.org/abs/2207.10951}
}