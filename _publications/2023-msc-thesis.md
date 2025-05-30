---
title: "Contrastive Learning as Kernel Approximation"
collection: publications
category: theses
permalink: /publication/2023-msc-thesis
date: 2023-08-01
venue: 'MSc Thesis'
paperurl: 'https://escholarship.mcgill.ca/concern/theses/6w924j09p'
citation: 'Konstantinos Christopher Tsiolis. 2023. <i>Contrastive Learning as Kernel Approximation.</i> McGill University (Canada).'
excerpt: ''
---

<b>Abstract</b>: In standard supervised machine learning, it is necessary to provide a label for every input in the data. While raw data in many application domains is easily obtainable on the Internet, manual labelling of this data is prohibitively expensive. To circumvent this issue, contrastive learning methods produce low-dimensional vector representations (also called features) of high-dimensional inputs on large unlabelled datasets. This is done by training with a contrastive loss function, which enforces that similar inputs have high inner product and dissimilar inputs have low inner product in the feature space. Rather than annotating each input individually, it suffices to define a means of sampling pairs of similar and dissimilar inputs. Contrastive features can then be fed as inputs to supervised learning systems on much smaller labelled datasets to obtain high accuracy on end tasks of interest. The goal of this thesis is to provide an overview of the current theoretical understanding of contrastive learning, specifically as it pertains to the minimizers of contrastive loss functions and their relationship to prior methods for learning features from unlabelled data. We highlight popular contrastive loss functions whose minimizers implicitly approximate a positive semidefinite (PSD) kernel. The latter is a well-studied object in functional analysis and learning theory that formalizes a notion of similarity between elements of a space. PSD kernels provide an implicit definition of features through the theory of reproducing kernel Hilbert spaces.