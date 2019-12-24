---
title: "Discovering Morphological Paradigms from Plain Text Using a Dirichlet Process Mixture Model"
date: 2011-07-01
publishDate: 2019-12-15T19:22:25.421057Z
authors: ["Markus Dreyer", "Jason Eisner"]
publication_types: ["1"]
abstract: "We present an inference algorithm that organizes observed words (tokens) into structured inflectional paradigms (types). It also naturally predicts the spelling of unobserved forms that are missing from these paradigms, and discovers inflectional principles (grammar) that generalize to wholly unobserved words. Our Bayesian generative model of the data explicitly represents tokens, types, inflections, paradigms, and locally conditioned string edits. It assumes that inflected word tokens are generated from an infinite mixture of inflectional paradigms (string tuples). Each paradigm is sampled all at once from a graphical model, whose potential functions are weighted finitestate transducers with language-specific parameters to be learned. These assumptions naturally lead to an elegant empirical Bayes inference procedure that exploits Monte Carlo EM, belief propagation, and dynamic programming.  Given 50–100 seed paradigms, adding a 10-million-word corpus reduces prediction error for morphological inflections by up to 10%."
featured: true
publication: "*Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP)*"
tags: ["emnlp", "morphology", "monte carlo", "dirichlet", "belief propagation", "graphical models"]
url_pdf: "http://cs.jhu.edu/~jason/papers/#dreyer-eisner-2011"
---
