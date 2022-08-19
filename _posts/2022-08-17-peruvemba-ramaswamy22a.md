---
title: Learning large Bayesian networks with expert constraints
abstract: We propose a new score-based algorithm for learning the structure of a Bayesian
  Network (BN). It is the first algorithm that simultaneously supports the requirements
  of (i) learning a BN of bounded treewidth, (ii) satisfying expert constraints, including
  positive and negative ancestry properties between nodes, and (iii) scaling up to
  BNs with several thousand nodes. The algorithm operates in two phases. In Phase
  1, we utilize a modified version of an existing BN structure learning algorithm,
  modified to generate an initial Directed Acyclic Graph (DAG) that supports a portion
  of the given constraints. In Phase 2, we follow the BN-SLIM framework, introduced
  by Peruvemba Ramaswamy and Szeider (AAAI 2021). We improve the initial DAG by repeatedly
  running a MaxSAT solver on selected local parts. The MaxSAT encoding entails local
  versions of the expert constraints as hard constraints. We evaluate a prototype
  implementation of our algorithm on several standard benchmark sets. The encouraging
  results demonstrate the power and flexibility of the BN-SLIM framework. It boosts
  the score while increasing the number of satisfied expert constraints.
openreview: HhMg3wUsclc
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: peruvemba-ramaswamy22a
month: 0
tex_title: Learning large {Bayesian} networks with expert constraints
firstpage: 1592
lastpage: 1601
page: 1592-1601
order: 1592
cycles: false
bibtex_author: Peruvemba Ramaswamy, Vaidyanathan and Szeider, Stefan
author:
- given: Vaidyanathan
  family: Peruvemba Ramaswamy
- given: Stefan
  family: Szeider
date: 2022-08-17
address:
container-title: Proceedings of the Thirty-Eighth Conference on Uncertainty in Artificial
  Intelligence
volume: '180'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 8
  - 17
pdf: https://proceedings.mlr.press/v180/peruvemba-ramaswamy22a/peruvemba-ramaswamy22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
