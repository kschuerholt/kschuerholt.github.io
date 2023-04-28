---
title: "Sparsified Model Zoo Twins: Investigating Populations of Sparsified Neural Network Models"
collection: publications
permalink: /publication/2023-03-01-Sparsified_Model_Zoos
excerpt: 'In this paper, we apply common sparsification methods on population of Neural Networks and analyze their performance and relation between sparse and full models.'
date: 2023-03-01
venue: 'ICLR Workshop on Sparsity in Neural Networks 2023'
paperurl: 'https://arxiv.org/abs/2304.13718'
citation: 'Honegger et al., 2023. &quot;Sparsified Model Zoo Twins: Investigating Populations of Sparsified Neural Network Models.&quot; <i>ICLR Workshop on Sparsity in Neural Networks</i> 2023.'
---

Abstract 
=====
With growing size of Neural Networks (NNs), model sparsification to reduce the computational cost and memory demand for model inference has become of vital interest for both research and production. While many sparsification methods have been proposed and successfully applied on individual models, to the best of our knowledge their behavior and robustness has not yet been studied on large populations of models. With this paper, we address that gap by applying two popular sparsification methods on populations of models (so called model zoos) to create sparsified versions of the original zoos. We investigate the performance of these two methods for each zoo, compare sparsification layer-wise, and analyse agreement between original and sparsified populations.
We find both methods to be very robust with magnitude pruning able outperform variational dropout with the exception of high sparsification ratios above 80%.
Further, we find sparsified models agree to a high degree with their original non-sparsified counterpart, and that the performance of original and sparsified model is highly correlated. Finally, all models of the model zoos and their sparsified model twins are publicly available: \url{modelzoos.cc}.

Bibtex: 
```
@inproceedings{
    honegger2023sparsified,
    title={Sparsified Model Zoo Twins: Investigating Populations of Sparsified Neural Network Models},
    author={Dominik Honegger and Konstantin Schürholt and Damian Borth},
    booktitle={ICLR 2023 Workshop on Sparsity in Neural Networks},
    year={2023},
}
```