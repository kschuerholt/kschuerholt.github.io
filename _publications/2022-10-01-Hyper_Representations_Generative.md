---
title: "Hyper-Representations as Generative Models: Sampling Unseen Neural Network Weights"
collection: publications
permalink: /publication/2022-10-01-Hyper_Representations_Generative
excerpt: 'In this paper, we extend hyper-representations for generative use to sample neural network weights for initialization, ensembling and transfer learning.'
date: 2022-10-01
venue: 'Neural Information Processing Systems (NeurIPS) 2022'
paperurl: 'https://arxiv.org/abs/2209.14733'
citation: 'Schürholt et al., 2022. &quot;Hyper-Representations as Generative Models: Sampling Unseen Neural Network Weights.&quot; <i>NeurIPS</i> 2022.'
---
Learning representations of neural network weights given a model zoo is an emerging and challenging area with many potential applications from model inspection, to neural architecture search or knowledge distillation. Recently, an autoencoder trained on a model zoo was able to learn a hyper-representation, which captures intrinsic and extrinsic properties of the models in the zoo. In this work, we extend hyper-representations for generative use to sample new model weights. We propose layer-wise loss normalization which we demonstrate is key to generate high-performing models and several sampling methods based on the topology of hyper-representations. The models generated using our methods are diverse, performant and capable to outperform strong baselines as evaluated on several downstream tasks: initialization, ensemble sampling and transfer learning. Our results indicate the potential of knowledge aggregation from model zoos to new models via hyper-representations thereby paving the avenue for novel research directions. 

[Download paper here](https://arxiv.org/abs/2209.14733)

Bibtex: 
@inproceedings{schurholtHyperRepresentationsGenerativeModels2022,
  title = {Hyper-{{Representations}} as {{Generative Models}}: {{Sampling Unseen Neural Network Weights}}},
  booktitle = {Thirty-Sixth {{Conference}} on {{Neural Information Processing Systems}} ({{NeurIPS}})},
  author = {Sch{\"u}rholt, Konstantin and Knyazev, Boris and {Gir{\'o}-i-Nieto}, Xavier and Borth, Damian},
  year = {2022},
  month = oct,
}