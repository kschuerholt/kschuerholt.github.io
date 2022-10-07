---
title: "Model Zoos: A Dataset of Diverse Populations of Neural Network Models"
collection: publications
permalink: /publication/2019_01_01-Water_vapor_transport
excerpt: 'In this work, we investigate the numerical properties of coupled mass and energy equations of snow pack.'
date: 2019-01-01
venue: 'European Geosciences Union (EGU) General Assembly 2019'
paperurl: 'https://search.ebscohost.com/login.aspx?direct=true&profile=ehost&scope=site&authtype=crawler&jrnl=10297006&AN=140480720&h=OIy4BTnTfn8MswNyU913MD0Xo04OcI6gH7aYV7TAye0vFuoL6%2FrVJwyn3PeyJIlnbWBhd97x9Iezqwkcgn5k0w%3D%3D&crl=c'
citation: 'Schürholt et al., 2019. &quot;On water vapor transport in snowpack models: Comparison of existing schemes, numerical requirements and the role of non-local advection.&quot; <i>EGU General Assembly</i> 2019.'
---


Abstract 
=====

The incorporation of a mass-conserving treatment of vapor transport has become a key requirement for snowpack modeling to capture various eﬀects emerging particularly underpersistent temperature gradient conditions. Though diﬀerent schemes for the upscaled vapor diﬀusion undergoing phase changes with the ice matrix are available, none ofthem are presently included in common snowpack models. This is mainly due to diﬃculties of faithfully integrating the equations into the numerical core of existing models. To shed further light onto the mathematical and numerical nature of the non-linear problem we have revisited the numerical treatment for the macroscopic, one-dimensional continuity equations of energy, ice mass and vapor mass in snow modelling. We focus on a comparison between two established, homogenized models thatonly diﬀer in the presence or absence of a local thermodynamic equilibrium ofthe vapor phase. As a compromise between minimizing programming overheadand keeping access to low-level modiﬁcations of the numerical scheme, we have implemented a ﬁnite element model of the coupled problem using the FENICS framework. For numerical cross validation, we used a ﬁnite diﬀerence solver aswell as analytical solutions of reduced problems. Then, we conducted numerical experiments for idealized, initial density proﬁles which are either smooth (Gaussian) or non-diﬀerentiable (piece-wise linear). As a main result, we observe clear diﬀerences between the two schemes with regard to i) absolute values of simulated mass transfer,ii) the response to non-smooth initial conditions and the iii) onset of numerical instabilities emerging in the the same, fully coupled, non-stabilized, non-linear solver for both problems. Diﬀerences are at least partly related to the assumption of a strictequilibrium of the vapor phase imposing diﬀerent numerical requirements related to theseparation of time scales. To further understand the nature of the numerical instabilities, we have derived an analytical approximation of the fully coupled problem. This reveals the ice-phase dynamics as a non-linear and non-local advection problemwith associated gradient steepening of physical origin. Based on this insight we discuss remedies for a stable and robust numerical solution of vapor transport in snow.

Bibtex: 
```
@inproceedings{
    schurholt2019water,
    title={On water vapor transport in snowpack models: Comparison of existing schemes, numerical requirements and the role of non-local advection.},
    author={Schürholt, Konstantin and Kowalski, Julia and Löwe, Henning},
    booktitle={Geophysical Research Abstracts},
    volume={21},
    year={2019}
}

```