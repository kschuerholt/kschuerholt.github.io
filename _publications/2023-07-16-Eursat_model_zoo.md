---
title: "Eurosat Model Zoo: A Dataset and Benchmark on Populations of Neural Networks and Its Sparsified Model Twins"
collection: publications
permalink: /publication/2023-07-16-Eursat_model_zoo
excerpt: 'Here, we study the benefits of populations of small models for remote sensing applications.'
date: 2023-07-16
venue: '2023 IEEE International Geoscience and Remote Sensing Symposium (IGARSS)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10283060'
citation: 'Honegger et al., 2023. &quot;Eurosat Model Zoo: A Dataset and Benchmark on Populations of Neural Networks and Its Sparsified Model Twins.&quot; <i>IGARSS</i> 2023.'
---

Abstract 
=====
The availability of large-scale labeled datasets in remote sensing and Earth observation accelerated the use of deep neural networks in this domain. In the standard workflow, data is first downloaded from satellites and then processed or analyzed locally on Earth. However, the advent of commercial satellite mega-constellations in low-earth orbit, from corporations such as SpaceX or Planet, renders the downstream link of the data for analysis as the limiting factor. Downstream capacity thus becomes a crucial bottleneck for Earth observation. Given this situation, potential future paradigms would require to run deep neural networks on the satellite itself and only download the results of data processing or analysis to Earth. In this scenario, data processing and analysis capabilities are limited by the constraints in compute and power supply of the on-board computer. This work investigates the potential of neural network sparsification techniques to reduce model size and improve efficiency in the Earth observation domain. We study neural network sparsification through the use of populations of neural networks, i.e., thousands of models trained on satellite imagery, to derive insights into the performance of sparsified neural networks for Earth observation.

Bibtex: 
```
@INPROCEEDINGS{10283060,
  author={Honegger, Dominik and Schürholt, Konstantin and Scheibenreif, Linus and Borth, Damian},
  booktitle={IGARSS 2023 - 2023 IEEE International Geoscience and Remote Sensing Symposium}, 
  title={Eurosat Model Zoo: A Dataset and Benchmark on Populations of Neural Networks and Its Sparsified Model Twins}, 
  year={2023},
  volume={},
  number={},
  pages={888-891},
  keywords={Earth;Analytical models;Satellites;Computational modeling;Sociology;Benchmark testing;Data processing;Remote Sensing;Neural Networks;Model Zoo;Sparsification},
  doi={10.1109/IGARSS52108.2023.10283060}
}
```