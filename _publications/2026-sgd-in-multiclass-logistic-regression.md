---
title: "SGD in Multiclass Logistic Regression: Sequential Learning and Scaling Laws"
collection: publications
category: preprints
permalink: /publication/2026-sgd-in-multiclass-logistic-regression
date: 2026-09-08
venue: Preprint (Under Review)
paperurl: 'https://arxiv.org/pdf/2609.07868'
citation: 'Konstantinos Christopher Tsiolis, Denny Wu, Christos Thrampoulidis, and Murat A. Erdogdu. <i>SGD in Multiclass Logistic Regression: Sequential Learning and Scaling Laws</i> arXiv preprint arXiv:2609.07868, 2026.'
---

<b>Abstract</b>: We study the training dynamics of multiclass logistic regression on high-dimensional Gaussian mixture models with a large number of classes and establish precise scaling laws governing the cross-entropy risk under gradient-based optimization. We show that learning proceeds sequentially across classes, from most to least frequent. When the class priors follow a power law distribution, the risk dynamics decompose into three phases: an initial plateau until the first class is learned, a power-law decay regime during which sequential learning occurs, and a final convergence regime. 

We then analyze how model capacity interacts with optimization under a fixed compute budget. When the effective dimension is restricted via projection onto leading principal components, the risk decomposes into a capacity term (a power law in the retained dimension) and an optimization term (a power law in training time). Optimizing this tradeoff yields a compute-optimal scaling law for logistic regression, with explicit prescriptions for model size and training time as functions of compute. These results extend theoretical scaling laws from linear regression to multiclass classification, while connecting to empirical scaling laws observed in large-scale neural networks.