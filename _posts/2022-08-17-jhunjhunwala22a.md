---
title: 'Fedvarp: Tackling the variance due to partial client participation in federated
  learning'
abstract: 'Data-heterogeneous federated learning (FL) systems suffer from two significant
  sources of convergence error: 1) client drift error caused by performing multiple
  local optimization steps at clients, and 2) partial client participation error caused
  by the fact that only a small subset of the edge clients participate in every training
  round. We find that among these, only the former has received significant attention
  in the literature. To remedy this, we propose FedVARP, a novel variance reduction
  algorithm applied at the server that eliminates error due to partial client participation.
  To do so, the server simply maintains in memory the most recent update for each
  client and uses these as surrogate updates for the non-participating clients in
  every round. Further, to alleviate the memory requirement at the server, we propose
  a novel clustering-based variance reduction algorithm ClusterFedVARP. Unlike previously
  proposed methods, both FedVARP and ClusterFedVARP do not require additional computation
  at clients or communication of additional optimization parameters. Through extensive
  experiments, we show that FedVARP outperforms state-of-the-art methods, and ClusterFedVARP
  achieves performance comparable to FedVARP with much less memory requirements.'
openreview: HlWLLdUocx5
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jhunjhunwala22a
month: 0
tex_title: 'Fedvarp: Tackling the variance due to partial client participation in
  federated learning'
firstpage: 906
lastpage: 916
page: 906-916
order: 906
cycles: false
bibtex_author: Jhunjhunwala, Divyansh and Sharma, Pranay and Nagarkatti, Aushim and
  Joshi, Gauri
author:
- given: Divyansh
  family: Jhunjhunwala
- given: Pranay
  family: Sharma
- given: Aushim
  family: Nagarkatti
- given: Gauri
  family: Joshi
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
pdf: https://proceedings.mlr.press/v180/jhunjhunwala22a/jhunjhunwala22a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v180/jhunjhunwala22a/jhunjhunwala22a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
