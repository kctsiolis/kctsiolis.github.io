---
title: "From Information to Generative Exponent: Learning Rate Induces Phase Transitions in SGD"
collection: publications
category: preprints_workshops
permalink: /publication/2025-from-information-to-generative-exponent
date: 2025-06-09
venue: 'To appear in <i>3rd Workshop on High-dimensional Learning Dynamics (HiLD)</i> at ICML'
paperurl: 'https://openreview.net/forum?id=0uozboWsA2&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICML.cc%2F2025%2FWorkshop%2FHiLD%2FAuthors%23your-submissions)'
excerpt: ''
citation: 
---

<b>Abstract</b>: To understand feature learning dynamics in neural networks, recent theoretical works have focused on gradient-based learning of Gaussian single-index models, where the label is a function of a latent one-dimensional projection of the input. While the sample complexity of online SGD is determined by the information exponent of the link function, recently proposed variants of SGD that introduce non-correlational updates are instead limited by the generative exponent. However, this picture is only valid for sufficiently large learning rate. In this paper, we characterize the relationship between learning rate and sample complexity for a general class of gradient-based algorithms, and demonstrate a phase transition from an "information exponent regime" with small learning rate to a "generative exponent regime" with large learning rate. Our framework covers prior analyses of online SGD and SGD with batch reuse, while also introducing a new layer-wise training algorithm. Our theoretical study demonstrates that the choice of learning rate is as important as the design of the algorithm in achieving statistical and computational efficiency.