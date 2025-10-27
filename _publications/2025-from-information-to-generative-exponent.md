---
title: "From Information to Generative Exponent: Learning Rate Induces Phase Transitions in SGD"
collection: publications
category: conferences
permalink: /publication/2025-from-information-to-generative-exponent
date: 2025-09-18
venue: '<i>39th International Conference on Neural Information Processing Systems</i> (NeurIPS)'
paperurl: 'https://arxiv.org/pdf/2510.21020'
excerpt: ''
citation: 'Konstantinos Christopher Tsiolis, Alireza Mousavi-Hosseini, and Murat A. Erdogdu. <i>From Information to Generative Exponent: Learning Rate Induces Phase Transitions in SGD.</i> arXiv preprint arXiv:2510.21020, 2025.'
---

<b>Abstract</b>: To understand feature learning dynamics in neural networks, recent theoretical works have focused on gradient-based learning of Gaussian single-index models, where the label is a nonlinear function of a latent one-dimensional projection of the input. While the sample complexity of online SGD is determined by the information exponent of the link function, recent works improved this by performing multiple gradient steps on the same sample with different learning rates --- yielding a non-correlational update rule --- and instead are limited by the (potentially much smaller) generative exponent. However, this picture is only valid when these learning rates are sufficiently large. In this paper, we characterize the relationship between learning rate(s) and sample complexity for a broad class of gradient-based algorithms that encapsulates both correlational and non-correlational updates. We demonstrate that, in certain cases, there is a phase transition from an "information exponent regime" with small learning rate to a "generative exponent regime" with large learning rate. Our framework covers prior analyses of one-pass SGD and SGD with batch reuse, while also introducing a new layer-wise training algorithm that leverages a two-timescales approach (via different learning rates for each layer) to go beyond correlational queries without reusing samples or modifying the loss from squared error. Our theoretical study demonstrates that the choice of learning rate is as important as the design of the algorithm in achieving statistical and computational efficiency.