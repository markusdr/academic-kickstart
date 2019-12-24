---
title: "Better Informed Training of Latent Syntactic Features"
date: 2006-07-01
publishDate: 2019-12-15T19:22:25.425411Z
authors: ["Markus Dreyer", "Jason Eisner"]
publication_types: ["1"]
abstract: "We study unsupervised methods for learning refinements of the nonterminals in a treebank. Following Matsuzaki et al. (2005) and Prescher (2005), we may for example split NP without supervision into NP[0] and NP[1], which behave differently. We first propose to learn a PCFG that adds such features to nonterminals in such a way that they respect patterns of linguistic feature passing: each node’s nonterminal features are either identical to, or independent of, those of its parent. This linguistic constraint reduces runtime and the number of parameters to be learned. However, it did not yield improvements when training on the Penn Treebank. An orthogonal strategy was more successful: to improve the performance of the EM learner by treebank preprocessing and by annealing methods that split nonterminals selectively. Using these methods, we can maintain high parsing accuracy while dramatically reducing the model size."
featured: false
publication: "*Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP)*"
tags: ["emnlp", "parsing", "semi-supervised", "latent variables"]
url_pdf: "http://cs.jhu.edu/~jason/papers/#dreyer-eisner-2006"
---
