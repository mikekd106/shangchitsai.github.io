---
title: Modeling Diagnostic Label Correlation for Automatic ICD Coding
authors:
- Shang-Chi Tsai
- Chao-Wei Huang
- Yun-Nung Chen
date: '2021-06-01'
publishDate: '2025-06-15T13:39:47.969829Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 2021 Conference of the North American Chapter of
  the Association for Computational Linguistics: Human Language Technologies*'
doi: 10.18653/v1/2021.naacl-main.318
abstract: Given the clinical notes written in electronic health records (EHRs), it
  is challenging to predict the diagnostic codes which is formulated as a multi-label
  classification task. The large set of labels, the hierarchical dependency, and the
  imbalanced data make this prediction task extremely hard. Most existing work built
  a binary prediction for each label independently, ignoring the dependencies between
  labels. To address this problem, we propose a two-stage framework to improve automatic
  ICD coding by capturing the label correlation. Specifically, we train a label set
  distribution estimator to rescore the probability of each label set candidate generated
  by a base predictor. This paper is the first attempt at learning the label set distribution
  as a reranking module for ICD coding. In the experiments, our proposed framework
  is able to improve upon best-performing predictors for medical code prediction on
  the benchmark MIMIC datasets.
links:
- name: URL
  url: https://aclanthology.org/2021.naacl-main.318/
---
