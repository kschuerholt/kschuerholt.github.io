---
title: "Model Zoos: A Dataset of Diverse Populations of Neural Network Models"
collection: publications
permalink: /publication/2022-10-01-Model_Zoos
excerpt: 'To enable the investigation of populations of neural network models, we release a novel dataset of diverse model zoos with this work.'
date: 2022-10-01
venue: 'Neural Information Processing Systems (NeurIPS) 2022 Datasets and Benchmarks Track'
paperurl: 'https://arxiv.org/abs/2209.14764'
citation: 'Schürholt et al., 2022. &quot;Model Zoos: A Dataset of Diverse Populations of Neural Network Models.&quot; <i>NeurIPS</i> 2022.'
---


Abstract 
=====

In the last years, neural networks (NN) have evolved from laboratory environments to the state-of-the-art for many real-world problems. It was shown that NN models (i.e., their weights and biases) evolve on unique trajectories in weight space during training. Following, a population of such neural network models (referred to as model zoo) would form structures in weight space. We think that the geometry, curvature and smoothness of these structures contain information about the state of training and can reveal latent properties of individual models. With such model zoos, one could investigate novel approaches for (i) model analysis, (ii) discover unknown learning dynamics, (iii) learn rich representations of such populations, or (iv) exploit the model zoos for generative modelling of NN weights and biases. Unfortunately, the lack of standardized model zoos and available benchmarks significantly increases the friction for further research about populations of NNs. With this work, we publish a novel dataset of model zoos containing systematically generated and diverse populations of NN models for further research. In total the proposed model zoo dataset is based on eight image datasets, consists of 27 model zoos trained with varying hyperparameter combinations and includes 50’360 unique NN models as well as their sparsified twins, resulting in over 3’844’360 collected model states. Additionally, to the model zoo data we provide an in-depth analysis of the zoos and provide benchmarks for multiple downstream tasks. The dataset can be found at www.modelzoos.cc.


Bibtex: 
```
@inproceedings{
    schurholt2022modelzoos,
    title={Model Zoos: A Dataset of Diverse Populations of Neural Network Models},
    author={Konstantin Schürholt and Diyar Taskiran and Boris Knyazev and Xavier Giro-i-Nieto and Damian Borth},
    booktitle={Thirty-sixth Conference on Neural Information Processing Systems Datasets and Benchmarks Track},
    year={2022},
    url={https://openreview.net/forum?id=MOCZI3h8Ye}
}
```