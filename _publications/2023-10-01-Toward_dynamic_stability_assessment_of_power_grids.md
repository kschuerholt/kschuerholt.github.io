---
title: "Toward dynamic stability assessment of power grid topologies using graph neural networks"
collection: publications
permalink: /publication/2023-10-01-Toward_dynamic_stability_assessment_of_power_grids
excerpt: 'This paper investigats the applicability of Graph Neural Networks to predict dynamic stability of power grids.'
date: 2023-10-01
venue: 'Chaos: An Interdisciplinary Journal of Nonlinear Science'
paperurl: 'https://pubs.aip.org/aip/cha/article/33/10/103103/2914062'
citation: 'Nauck et al., 2023. &quot;Toward dynamic stability assessment of power grid topologies using graph neural networks.&quot; <i>New Journal of Physics</i> 2022.'
---


Abstract 
=====
The prediction of dynamical stability of power grids becomes more important and challenging with increasing shares of renewable energy sources due to their decentralized structure, reduced inertia and volatility. We investigate the feasibility of applying graph neural networks (GNN) to predict dynamic stability of synchronisation in complex power grids using the single-node basin stability (SNBS) as a measure. To do so, we generate two synthetic datasets for grids with 20 and 100 nodes respectively and estimate SNBS using Monte-Carlo sampling. Those datasets are used to train and evaluate the performance of eight different GNN-models. All models use the full graph without simplifications as input and predict SNBS in a nodal-regression-setup. We show that SNBS can be predicted in general and the performance significantly changes using different GNN-models. Furthermore, we observe interesting transfer capabilities of our approach: GNN-models trained on smaller grids can directly be applied on larger grids without the need of retraining.


Bibtex: 
```
@article{nauckDynamicStabilityAssessment2023,
  title = {Toward Dynamic Stability Assessment of Power Grid Topologies Using Graph Neural Networks},
  author = {Nauck, Christian and Lindner, Michael and Sch{\"u}rholt, Konstantin and Hellmann, Frank},
  year = {2023},
  month = oct,
  journal = {Chaos: An Interdisciplinary Journal of Nonlinear Science},
  volume = {33},
  number = {10},
  pages = {103103},
  issn = {1054-1500},
  doi = {10.1063/5.0160915},
}

```