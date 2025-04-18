---
title: "MIB: A Mechanistic Interpretability Benchmark"
date: 2025-04-18T09:49:09.750Z
source: paper
link: "http://arxiv.org/abs/2504.13151v1"
tags: ["paper","ml"]
---
How can we know whether new mechanistic interpretability methods achieve real
improvements? In pursuit of meaningful and lasting evaluation standards, we
propose MIB, a benchmark with two tracks spanning four tasks and five models.
MIB favors methods that precisely and concisely recover relevant causal
pathways or specific causal variables in neural language models. The circuit
localization track compares methods that locate the model components - and
connections between them - most important for performing a task (e.g.,
attribution patching or information flow routes). The causal variable
localization track compares methods that featurize a hidden vector, e.g.,
sparse autoencoders (SAEs) or distributed alignment search (DAS), and locate
model features for a causal variable relevant to the task. Using MIB, we find
that attribution and mask optimization methods perform best on circuit
localization. For causal variable localization, we find that the supervised DAS
method performs best, while SAE features are not better than neurons, i.e.,
standard dimensions of hidden vectors. These findings illustrate that MIB
enables meaningful comparisons of methods, and increases our confidence that
there has been real progress in the field.
