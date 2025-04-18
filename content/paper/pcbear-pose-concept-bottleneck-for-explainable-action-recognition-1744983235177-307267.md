---
title: "PCBEAR: Pose Concept Bottleneck for Explainable Action Recognition"
date: "2025-04-18T13:33:55.177Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13140v1"
tags: ["paper","ml"]
---

Human action recognition (HAR) has achieved impressive results with deep learning models, but their decision-making process remains opaque due to their black-box nature. Ensuring interpretability is crucial, especially for real-world applications requiring transparency and accountability. Existing video XAI methods primarily rely on feature attribution or static textual concepts, both of which struggle to capture motion dynamics and temporal dependencies essential for action understanding. To address these challenges, we propose Pose Concept Bottleneck for Explainable Action Recognition (PCBEAR), a novel concept bottleneck framework that introduces human pose sequences as motion-aware, structured concepts for video action recognition. Unlike methods based on pixel-level features or static textual descriptions, PCBEAR leverages human skeleton poses, which focus solely on body movements, providing robust and interpretable explanations of motion dynamics. We define two types of pose-based concepts: static pose concepts for spatial configurations at individual frames, and dynamic pose concepts for motion patterns across multiple frames. To construct these concepts, PCBEAR applies clustering to video pose sequences, allowing for automatic discovery of meaningful concepts without manual annotation. We validate PCBEAR on KTH, Penn-Action, and HAA500, showing that it achieves high classification performance while offering interpretable, motion-driven explanations. Our method provides both strong predictive performance and human-understandable insights into the model's reasoning process, enabling test-time interventions for debugging and improving model behavior.

[Watch on YouTube](http://arxiv.org/abs/2504.13140v1)
