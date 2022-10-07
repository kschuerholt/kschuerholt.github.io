---
title: "Elements of future snowpack modeling – Part 1: A physical instability arising from the nonlinear coupling of transport and phase changes"
collection: publications
permalink: /publication/2022_03_11-Future_snowpack_modelling
excerpt: 'This paper studies the effect of numerical instabilities of coupled heat and mass equations of ice in snow pack.'
date: 2022-03-11
venue: 'The Cryosphere'
paperurl: 'https://tc.copernicus.org/articles/16/903/2022/'
citation: 'Schürholt et al., 2022. &quot;Elements of future snowpack modeling – Part 1: A physical instability arising from the nonlinear coupling of transport and phase changes.&quot; <i>The Cryosphere</i> 2022.'
---


Abstract 
=====

The incorporation of vapor transport has become a key demand for snowpack modeling in which accompanied phase changes give rise to a new, nonlinear coupling in the heat and mass equations. This coupling has an impact on choosing efficient numerical schemes for 1D snowpack models which are naturally not designed to cope with mathematical particularities of arbitrary, nonlinear partial differential equations (PDEs). To explore this coupling we have implemented a stand-alone finite element solution of the coupled heat and mass equations in snow using the computing platform FEniCS. We focus on the nonlinear feedback of the ice phase exchanging mass with a diffusing vapor phase with concurrent heat transport in the absence of settling. We demonstrate that existing continuum-mechanical models derived through homogenization or mixture theory yield similar results for homogeneous snowpacks of constant density. When snow density varies significantly with depth, we show that phase changes in the presence of temperature gradients give rise to nonlinear advection of the ice phase amplifying existing density variations. Eventually, this advection triggers a wave instability in the continuity equations. This is traced back to the density dependence of the effective transport coefficients as revealed by a linear stability analysis of the nonlinear PDE system. The instability is an inherent feature of existing continuum models and predicts, as a side product, the formation of a low-density (mechanical) weak layer on the sublimating side of an ice crust. The wave instability constitutes a key challenge for a faithful treatment of solid–vapor mass conservation between layers, which is discussed in view of the underlying homogenization schemes and their numerical solutions.


Bibtex: 
```
@article{schurholt2022elements,
    title={Elements of future snowpack modeling--Part 1: A physical instability arising from the nonlinear coupling of transport and phase changes},
    author={Schürholt, Konstantin and Kowalski, Julia and Löwe, Henning},
    journal={The Cryosphere},
    volume={16},
    number={3},
    pages={903--923},
    year={2022},
    publisher={Copernicus GmbH}
}

```