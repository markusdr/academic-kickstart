---
title: "Hill climbing on speech lattices: A new rescoring framework"
date: 2011-01-01
publishDate: 2019-12-15T19:22:25.431390Z
authors: ["Ariya Rastrow", "Markus Dreyer", "Abhinav Sethy", "Sanjeev Khudanpur", "Bhuvana Ramabhadran", "Mark Dredze"]
publication_types: ["1"]
abstract: "We describe a new approach for rescoring speech lattices - with long-span language models or wide-context acoustic models - that does not entail computationally intensive lattice expansion or limited rescoring of only an N-best list. We view the set of word-sequences in a lattice as a discrete space equipped with the edit-distance metric, and develop a hill climbing technique to start with, say, the 1-best hypothesis under the lattice-generating model(s) and iteratively search a local neighborhood for the highest-scoring hypothesis under the rescoring model(s); such neighborhoods are efficiently constructed via finite state techniques. We demonstrate empirically that to achieve the same reduction in error rate using a better estimated, higher order language model, our technique evaluates fewer utterance-length hypotheses than conventional N-best rescoring by two orders of magnitude. For the same number of hypotheses evaluated, our technique results in a significantly lower error rate."
featured: false
publication: "*Proceedings of ICASSP*"
tags: ["speech", "lattice", "icassp", "finite state"]
url_pdf: "https://www.cs.jhu.edu/~mdredze/publications/hill_climb_icassp_11.pdf"
---

