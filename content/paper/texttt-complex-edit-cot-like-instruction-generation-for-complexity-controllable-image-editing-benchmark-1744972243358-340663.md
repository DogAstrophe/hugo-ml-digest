---
title: "$\textttComplex-Edit$: CoT-Like Instruction Generation for Complexity-Controllable Image Editing Benchmark"
date: "2025-04-18T10:30:43.358Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13143v1"
tags: ["paper", "ml"]
---

We introduce $\textttComplex-Edit$, a comprehensive benchmark designed to systematically evaluate instruction-based image editing models across instructions of varying complexity. To develop this benchmark, we harness GPT-4o to automatically collect a diverse set of editing instructions at scale. Our approach follows a well-structured Chain-of-Edit'' pipeline: we first generate individual atomic editing tasks independently and then integrate them to form cohesive, complex instructions. Additionally, we introduce a suite of metrics to assess various aspects of editing performance, along with a VLM-based auto-evaluation pipeline that supports large-scale assessments. Our benchmark yields several notable insights: 1) Open-source models significantly underperform relative to proprietary, closed-source models, with the performance gap widening as instruction complexity increases; 2) Increased instructional complexity primarily impairs the models' ability to retain key elements from the inpu
