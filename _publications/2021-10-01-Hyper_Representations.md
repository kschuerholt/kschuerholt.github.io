---
title: "Self-Supervised Representation Learning on Neural Network Weights for Model Characteristic Prediction"
collection: publications
permalink: /publication/2021-10-01-Hyper_Representations
excerpt: 'This paper proposes to learn self-supervised representations of the weights of populations of NN models using novel data augmentations and an adapted transformer architecture.'
date: 2022-10-01
venue: 'Neural Information Processing Systems (NeurIPS) 2021'
paperurl: 'https://arxiv.org/abs/2110.15288'
citation: 'Schürholt et al., 2021. &quot;Self-Supervised Representation Learning on Neural Network Weights for Model Characteristic Prediction.&quot; <i>NeurIPS</i> 2021.'
---
Self-Supervised Learning (SSL) has been shown to learn useful and information-preserving representations. Neural Networks (NNs) are widely applied, yet their weight space is still not fully understood. Therefore, we propose to use SSL to learn hyper-representations of the weights of populations of NNs. To that end, we introduce domain specific data augmentations and an adapted attention architecture. Our empirical evaluation demonstrates that self-supervised representation learning in this domain is able to recover diverse NN model characteristics. Further, we show that the proposed learned representations outperform prior work for predicting hyper-parameters, test accuracy, and generalization gap as well as transfer to out-of-distribution settings. 

[Download paper here](https://arxiv.org/abs/2110.15288)

Bibtex:  
```json
@inproceedings{  
  sch{\"u}rholt2021selfsupervised,    
  title={Self-Supervised Representation Learning on Neural Network Weights for Model Characteristic Prediction},    
  author={Konstantin Sch{\"u}rholt and Dimche Kostadinov and Damian Borth},    
  booktitle={Advances in Neural Information Processing Systems},    
  editor={A. Beygelzimer and Y. Dauphin and P. Liang and J. Wortman Vaughan},    
  year={2021},    
  url={https://arxiv.org/abs/2110.15288}    
}  
```