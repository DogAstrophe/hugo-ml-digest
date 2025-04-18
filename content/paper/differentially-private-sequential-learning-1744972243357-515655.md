---
title: "Differentially Private Sequential Learning"
date: "2025-04-18T10:30:43.358Z"
source: "paper"
link: "http://arxiv.org/abs/2502.19525v3"
tags: ["paper", "ml"]
---

In a differentially private sequential learning setting, agents introduce endogenous noise into their actions to maintain privacy. Applying this to a standard sequential learning model leads to different outcomes for continuous vs. binary signals. For continuous signals with a nonzero privacy budget, we introduce a novel smoothed randomized response mechanism that adapts noise based on distance to a threshold, unlike traditional randomized response, which applies uniform noise. This enables agents' actions to better reflect both private signals and observed history, accelerating asymptotic learning speed to $\Theta_\epsilon(\log(n))$, compared to $\Theta(\sqrt\log(n))$ in the non-private regime where privacy budget is infinite. Moreover, in the non-private setting, the expected stopping time for the first correct decision and the number of incorrect actions diverge, meaning early agents may make mistakes for an unreasonably long period. In contrast, under a finite privacy budget $\epsi
