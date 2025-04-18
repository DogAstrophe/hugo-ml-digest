---
title: "A New Semidefinite Relaxation for Linear and Piecewise-Affine Optimal
  Control with Time Scaling"
date: "2025-04-18T12:16:10.519Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13170v1"
tags: ["paper","ml"]
---

We introduce a semidefinite relaxation for optimal control of linear systems with time scaling. These problems are inherently nonconvex, since the system dynamics involves bilinear products between the discretization time step and the system state and controls. The proposed relaxation is closely related to the standard second-order semidefinite relaxation for quadratic constraints, but we carefully select a subset of the possible bilinear terms and apply a change of variables to achieve empirically tight relaxations while keeping the computational load light. We further extend our method to handle piecewise-affine (PWA) systems by formulating the PWA optimal-control problem as a shortest-path problem in a graph of convex sets (GCS). In this GCS, different paths represent different mode sequences for the PWA system, and the convex sets model the relaxed dynamics within each mode. By combining a tight convex relaxation of the GCS problem with our semidefinite relaxation with time scaling, we can solve PWA optimal-control problems through a single semidefinite program.

[Watch on YouTube](http://arxiv.org/abs/2504.13170v1)
