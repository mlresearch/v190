---
title: Online Weak-form Sparse Identification of Partial Differential Equations
abstract: This paper presents an online algorithm for identification of partial differential
  equations (PDEs) based on the weak-form sparse identification of nonlinear dynamics
  algorithm (WSINDy). The algorithm is online in a sense that if performs the identification
  task by processing solution snapshots that arrive sequentially. The core of the
  method combines a weak-form discretization of candidate PDEs with an online proximal
  gradient descent approach to the sparse regression problem. In particular, we do
  not regularize the $\ell_0$-pseudo-norm, instead finding that directly applying
  its proximal operator (which corresponds to a hard thresholding) leads to efficient
  online system identification from noisy data. We demonstrate the success of the
  method on the Kuramoto-Sivashinsky equation, the nonlinear wave equation with time-varying
  wavespeed, and the linear wave equation, in one, two, and three spatial dimensions,
  respectively. In particular, our examples show that the method is capable of identifying
  and tracking systems with coefficients that vary abruptly in time, and offers a
  streaming alternative to problems in higher dimensions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: a-messenger22a
month: 0
tex_title: Online Weak-form Sparse Identification of Partial Differential Equations
firstpage: 241
lastpage: 256
page: 241-256
order: 241
cycles: false
bibtex_author: A.Messenger, Daniel and Dall'Anese, Emiliano and Bortz, David
author:
- given: Daniel
  family: A.Messenger
- given: Emiliano
  family: Dall’Anese
- given: David
  family: Bortz
date: 2022-09-14
address:
container-title: Proceedings of Mathematical and Scientific Machine Learning
volume: '190'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 9
  - 14
pdf: https://proceedings.mlr.press/v190/a-messenger22a/a-messenger22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
