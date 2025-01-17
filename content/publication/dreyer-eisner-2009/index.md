---
title: "Graphical Models over Multiple Strings"
date: 2009-08-01
publishDate: 2019-12-15T19:22:25.423139Z
authors: ["Markus Dreyer", "Jason Eisner"]
publication_types: ["1"]
abstract: "We study graphical modeling in the case of string-valued random variables. Whereas a weighted finite-state transducer can model the probabilistic relationship between two strings, we are interested in building up joint models of three or more strings. This is needed for inflectional paradigms in morphology, cognate modeling or language reconstruction, and multiple-string alignment. We propose a Markov Random Field in which each factor (potential function) is a weighted finite-state machine, typically a transducer that evaluates the relationship between just two of the strings. The full joint distribution is then a product of these factors. Though decoding is actually undecidable in general, we can still do efficient joint inference using approximate belief propagation; the necessary computations and messages are all finite-state. We demonstrate the methods by jointly predicting morphological forms."
featured: false
publication: "*Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP)*"
tags: ["emnlp", "morphology", "belief propagation", "graphical models"]
url_pdf: "http://cs.jhu.edu/~jason/papers/#dreyer-eisner-2009"
---

