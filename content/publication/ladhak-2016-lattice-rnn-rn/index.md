---
title: "LatticeRnn: Recurrent Neural Networks Over Lattices"
date: 2016-01-01
publishDate: 2019-12-15T19:22:25.429723Z
authors: ["Faisal Ladhak", "Ankur Gandhe", "Markus Dreyer", "Lambert Mathias", "Ariya Rastrow", "Björn Hoffmeister"]
publication_types: ["1"]
abstract: "We present a new model called LatticeRnn, which generalizes recurrent neural networks (RNNs) to process weighted lattices as input, instead of sequences. A LatticeRnn can encode the complete structure of a lattice into a dense representation, which makes it suitable to a variety of problems, including rescoring, classifying, parsing, or translating lattices using deep neural networks (DNNs). In this paper, we use LatticeRnns for a classification task: each lattice represents the output from an automatic speech recognition (ASR) component of a spoken language understanding (SLU) system, and we classify the intent of the spoken utterance based on the lattice embedding computed by a LatticeRnn. We show that making decisions based on the full ASR output lattice, as opposed to 1-best or n-best hypotheses, makes SLU systems more robust to ASR errors. Our experiments yield improvements of 13% over a baseline RNN system trained on transcriptions and 10% over an n-best list rescoring system for intent classification."
featured: false
publication: "*Proceedings of Interspeech*"
tags: ["interspeech", "amazon", "lattice", "rnn", "neural", "speech"]
url_pdf: "http://sail.usc.edu/publications/files/kalinliinterspeech2007.pdf"
doi: "10.21437/Interspeech.2016-1583"
---

