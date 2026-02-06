---
layout: page
title: Projects
permalink: /projects/
---

You can find details about what I have worked on most recently below.

### Bayesian Shear Inference with Differentiable Forward Modeling

- We leverage JAX-GalSim together with Schneider et al.'s importance sampling [approach](https://arxiv.org/abs/1411.2608) to develop a new Bayesian algorithm for cosmic shear inference.

### Differentiable Forward Models of Galaxy Light Profiles

- I lead the development [JAX-GalSim](https://github.com/GalSim-developers/JAX-GalSim), a GPU-accelerated and differentiable version of [GalSim](https://github.com/GalSim-developers/GalSim), which is currently under active development.


### Machine Learning models for mitigating the galaxy-galaxy blending problem in cosmological surveys

- We developed [BLISS](https://github.com/prob-ml/bliss) a machine learning model for probablistic inference of galaxy properties specifically targeted at blended galaxy fields.

<p align="center">
    <img src="https://github.com/ismael-mendoza/ismael-mendoza.github.io/blob/main/images/bliss.jpg?raw=true" alt="bliss" width="600"/>
</p>

*This figure showcases the overall structure of the BLISS inference pipeline.*


### Statistical framework for Galaxy-Halo Connection on N-body Simulations

- I developed [MultiCAM](https://github.com/ismael-mendoza/multicam), a multi-variable extension to conditional abundance matching (CAM) that can be used to connect properties of dark matter haloes with properties of galaxies.

<p align="center">
    <img src="https://github.com/ismael-mendoza/ismael-mendoza.github.io/blob/main/images/multicam.jpg?raw=true" alt="multicam" width="500"/>
</p>

*Above is a comparison of the correlation strength between predictions of MultiCAM and CAM, where MultiCAM can use the full mass accretion history (MAH) of a dark matter haloes as features for prediction.*

### Framework for evaluating galaxy deblending algorithms

- I lead the development of [BTK](https://github.com/LSSTDESC/BlendingToolKit) a software tool for simulating galaxy blends and consistent comparing galaxy deblenders based onv various metrics.

<p align="center">
    <img src="https://github.com/ismael-mendoza/ismael-mendoza.github.io/blob/main/images/btk.jpg?raw=true" alt="btk" width="600"/>
</p>

*This figure compares the reconstruction quality of individual galaxies from SExtractor and Scarlet when applied to simulated galaxy blends produced by BTK. The three metrics have been previously used in galaxy blending literature.*
