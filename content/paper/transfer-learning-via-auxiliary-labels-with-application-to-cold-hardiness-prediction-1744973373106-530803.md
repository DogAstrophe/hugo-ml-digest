---
title: "Transfer Learning via Auxiliary Labels with Application to
  Cold-Hardiness Prediction"
date: "2025-04-18T10:49:33.106Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13142v1"
tags: ["paper", "ml"]
---

Cold temperatures can cause significant frost damage to fruit crops depending on their resilience, or cold hardiness, which changes throughout the dormancy season. This has led to the development of predictive cold-hardiness models, which help farmers decide when to deploy expensive frost-mitigation measures. Unfortunately, cold-hardiness data for model training is only available for some fruit cultivars due to the need for specialized equipment and expertise. Rather, farmers often do have years of phenological data (e.g. date of budbreak) that they regularly collect for their crops. In this work, we introduce a new transfer-learning framework, Transfer via Auxiliary Labels (TAL), that allows farmers to leverage the phenological data to produce more accurate cold-hardiness predictions, even when no cold-hardiness data is available for their specific crop. The framework assumes a set of source tasks (cultivars) where each has associated primary labels (cold hardiness) and auxiliary labels (phenology). However, the target task (new cultivar) is assumed to only have the auxiliary labels. The goal of TAL is to predict primary labels for the target task via transfer from the source tasks. Surprisingly, despite the vast literature on transfer learning, to our knowledge, the TAL formulation has not been previously addressed. Thus, we propose several new TAL approaches based on model selection and averaging that can leverage recent deep multi-task models for cold-hardiness prediction. Our results on real-world cold-hardiness and phenological data for multiple grape cultivars demonstrate that TAL can leverage the phenological data to improve cold-hardiness predictions in the absence of cold-hardiness data.
