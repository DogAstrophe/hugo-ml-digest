---
title: "Novel Demonstration Generation with Gaussian Splatting Enables Robust
  One-Shot Manipulation"
date: 2025-04-18T09:49:09.750Z
source: paper
link: "http://arxiv.org/abs/2504.13175v1"
tags: ["paper","ml"]
---
Visuomotor policies learned from teleoperated demonstrations face challenges
such as lengthy data collection, high costs, and limited data diversity.
Existing approaches address these issues by augmenting image observations in
RGB space or employing Real-to-Sim-to-Real pipelines based on physical
simulators. However, the former is constrained to 2D data augmentation, while
the latter suffers from imprecise physical simulation caused by inaccurate
geometric reconstruction. This paper introduces RoboSplat, a novel method that
generates diverse, visually realistic demonstrations by directly manipulating
3D Gaussians. Specifically, we reconstruct the scene through 3D Gaussian
Splatting (3DGS), directly edit the reconstructed scene, and augment data
across six types of generalization with five techniques: 3D Gaussian
replacement for varying object types, scene appearance, and robot embodiments;
equivariant transformations for different object poses; visual attribute
editing for various lighting conditions; novel view synthesis for new camera
perspectives; and 3D content generation for diverse object types. Comprehensive
real-world experiments demonstrate that RoboSplat significantly enhances the
generalization of visuomotor policies under diverse disturbances. Notably,
while policies trained on hundreds of real-world demonstrations with additional
2D data augmentation achieve an average success rate of 57.2%, RoboSplat
attains 87.8% in one-shot settings across six types of generalization in the
real world.
