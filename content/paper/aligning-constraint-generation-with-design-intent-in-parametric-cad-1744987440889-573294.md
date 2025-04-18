---
title: "Aligning Constraint Generation with Design Intent in Parametric CAD"
date: "2025-04-18T14:44:00.889Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13178v1"
tags: ["paper", "ml"]
---

We adapt alignment techniques from reasoning LLMs to the task of generating engineering sketch constraints found in computer-aided design (CAD) models. Engineering sketches consist of geometric primitives (e.g. points, lines) connected by constraints (e.g. perpendicular, tangent) that define the relationships between them. For a design to be easily editable, the constraints must effectively capture design intent, ensuring the geometry updates predictably when parameters change. Although current approaches can generate CAD designs, an open challenge remains to align model outputs with design intent, we label this problem `design alignment'. A critical first step towards aligning generative CAD models is to generate constraints which fully-constrain all geometric primitives, without over-constraining or distorting sketch geometry. Using alignment techniques to train an existing constraint generation model with feedback from a constraint solver, we are able to fully-constrain 93% of sketches compared to 34% when using a na\\"ive supervised fine-tuning (SFT) baseline and only 8.9% without alignment. Our approach can be applied to any existing constraint generation model and sets the stage for further research bridging alignment strategies between the language and design domains.

[Read on Arxiv](http://arxiv.org/abs/2504.13178v1)
