---
title: "ViTa-Zero: Zero-shot Visuotactile Object 6D Pose Estimation"
date: "2025-04-18T12:28:43.550Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13179v1"
tags: ["paper","ml"]
---

Object 6D pose estimation is a critical challenge in robotics, particularly for manipulation tasks. While prior research combining visual and tactile (visuotactile) information has shown promise, these approaches often struggle with generalization due to the limited availability of visuotactile data. In this paper, we introduce ViTa-Zero, a zero-shot visuotactile pose estimation framework. Our key innovation lies in leveraging a visual model as its backbone and performing feasibility checking and test-time optimization based on physical constraints derived from tactile and proprioceptive observations. Specifically, we model the gripper-object interaction as a spring-mass system, where tactile sensors induce attractive forces, and proprioception generates repulsive forces. We validate our framework through experiments on a real-world robot setup, demonstrating its effectiveness across representative visual backbones and manipulation scenarios, including grasping, object picking, and bimanual handover. Compared to the visual models, our approach overcomes some drastic failure modes while tracking the in-hand object pose. In our experiments, our approach shows an average increase of 55% in AUC of ADD-S and 60% in ADD, along with an 80% lower position error compared to FoundationPose.

[Watch on YouTube](http://arxiv.org/abs/2504.13179v1)
