---
title: "Predicting basin stability of power grids using graph neural networks"
collection: publications
permalink: /publication/2022_04_29-Predicting_basin_stability
excerpt: 'This paper investigats the applicability of Graph Neural Networks to predict dynamic stability of power grids.'
date: 2022-04-29
venue: 'New Journal of Physics'
paperurl: 'https://iopscience.iop.org/article/10.1088/1367-2630/ac54c9/pdf'
citation: 'Nauck et al., 2022. &quot;Predicting basin stability of power grids using graph neural networks.&quot; <i>New Journal of Physics</i> 2022.'
---


Abstract 
=====
The prediction of dynamical stability of power grids becomes more important and challenging with increasing shares of renewable energy sources due to their decentralized structure, reduced inertia and volatility. We investigate the feasibility of applying graph neural networks (GNN) to predict dynamic stability of synchronisation in complex power grids using the single-node basin stability (SNBS) as a measure. To do so, we generate two synthetic datasets for grids with 20 and 100 nodes respectively and estimate SNBS using Monte-Carlo sampling. Those datasets are used to train and evaluate the performance of eight different GNN-models. All models use the full graph without simplifications as input and predict SNBS in a nodal-regression-setup. We show that SNBS can be predicted in general and the performance significantly changes using different GNN-models. Furthermore, we observe interesting transfer capabilities of our approach: GNN-models trained on smaller grids can directly be applied on larger grids without the need of retraining.


Bibtex: 
```
@article{nauck2022predicting,
    title={Predicting basin stability of power grids using graph neural networks},
    author={Nauck, Christian and Lindner, Michael and Sch{\"u}rholt, Konstantin and Zhang, Haoming and Schultz, Paul and Kurths, J{\"u}rgen and Isenhardt, Ingrid and Hellmann, Frank},
    journal={New Journal of Physics},
    volume={24},
    number={4},
    pages={043041},
    year={2022},
    publisher={IOP Publishing}
}
```