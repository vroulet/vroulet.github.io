---
layout: archive
title: "Software"
author_profile: true
redirect_from:
  - /software.html
---

{% include base_path %}

[**ilqc**](https://github.com/vroulet/ilqc)  
Toolbox for analyzing non-linear control algorithms from an optimization perspective.  
-- Implementation of classical nonlinear algorithms: gradient, Gauss-Newton, Newton, Differentiable Dynamic Programming approach with quadratic or linear-quadratic approximations.  
-- Oracles implemented à la Pytorch, various line-searches tested for all algorithms.  
-- Diverse environments available with animations: pendulum, pendulum on a cart, simple model of a car, bicycle model of a cart.  
-- Model Predictive Controller implemented for a contouring objective of a track racing task on a complex track.  
[conference paper](http://proceedings.mlr.press/v97/roulet19a.html)
[follow-up (theory)](https://github.com/vroulet/ilqc/blob/master/papers/ilqc_theory.pdf)
[follow-up (implementation)](https://github.com/vroulet/ilqc/blob/master/papers/ilqc_algos.pdf)
[notebook tutorial](https://github.com/vroulet/ilqc/blob/master/ilqc.ipynb)

[**tpri**](https://github.com/vroulet/tpri)  
Implementation of Target Propagation oracles for Recurrent Neural Networks (RNNs). Our implementation uses the analytical formulation of the inverse of the layers of a RNN rather than an inverse approximated by an auto-encoder. Our experimental results demonstrate the potential of Target Propagation on several tasks for very long RNNs.  
[paper](https://arxiv.org/abs/2112.01453)

[**xsdc**](https://github.com/cjones6/xsdc)  
Implementation of semi-supervised learning methods with deep network feature representations (XSDC). Our work extends the discriminative clustering approach of F. Bach and Z. Harchaoui [DIFFRAC](https://papers.nips.cc/paper/2007/hash/22fb0cee7e1f3bde58293de743871417-Abstract.html) to nonlinear feature representations. Our results show the benefits of incorporating nonlinear feature representation learning in semi-supervised learning in a flexible framework that can tackle any level of supervision in the data.  
[paper](https://link.springer.com/article/10.1007/s11222-021-10067-x)

[**casimir**](https://github.com/krishnap25/casimir)  
Toolbox of selected optimization algorithms for unstructured tasks such as binary classification, and structured prediction tasks such as visual object localization and named entity recognition.  
[paper](http://papers.nips.cc/paper/7726-a-smoother-way-to-train-structured-prediction-models)

[**yesweckn**](https://github.com/cjones6/yesweckn)  
Code to implement Convolutional Kernel Networks (CKNs) on image classification tasks. CKNs are the translation of Convolutional Neural Networks (ConvNets) into the framework of kernel methods. The present code provides a concrete implementation of this framework on benchmark architectures and datasets.  
[paper](https://arxiv.org/abs/1903.08131)
