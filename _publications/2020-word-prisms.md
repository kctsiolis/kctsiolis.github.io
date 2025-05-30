---
title: "Learning Efficient Task-Specific Embeddings with Word Prisms"
collection: publications
category: conferences
permalink: /publication/2020-word-prisms
date: 2020-12-08
venue: 'Published in <i>The 28th International Confernence on Comutational Linguistics</i>'
paperurl: 'https://aclanthology.org/2020.coling-main.106.pdf'
citation: 'Jingyi He, KC Tsiolis, Kian Kenyon-Dean, and Jackie Chi Kit Cheung. 2020. <i>Learning Efficient Task-Specific Meta-Embeddings with Word Prisms.</i> In <i>Proceedings of the 28th International Conference on Computational Linguistics</i>, pages 1229–1241, Barcelona, Spain (Online). International Committee on Computational Linguistics.'
excerpt: ''
---

<b> Abstract:</b> Word embeddings are trained to predict word cooccurrence statistics, which leads them to possess different lexical properties (syntactic, semantic, etc.) depending on the notion of context defined at training time. These properties manifest when querying the embedding space for the most similar vectors, and when used at the input layer of deep neural networks trained to solve downstream NLP problems. Meta-embeddings combine multiple sets of differently trained word embeddings, and have been shown to successfully improve intrinsic and extrinsic performance over equivalent models which use just one set of source embeddings. We introduce word prisms: a simple and efficient meta-embedding method that learns to combine source embeddings according to the task at hand. Word prisms learn orthogonal transformations to linearly combine the input source embeddings, which allows them to be very efficient at inference time. We evaluate word prisms in comparison to other meta-embedding methods on six extrinsic evaluations and observe that word prisms offer improvements in performance on all tasks.