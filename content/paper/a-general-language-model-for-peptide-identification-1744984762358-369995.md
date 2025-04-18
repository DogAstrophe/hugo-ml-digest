---
title: "A general language model for peptide identification"
date: "2025-04-18T13:59:22.358Z"
source: "paper"
link: "http://arxiv.org/abs/2502.15610v2"
tags: ["paper", "ml"]
---

Advances in peptide identification are revolutionizing our ability to decipher protein functions and accelerate therapeutic discovery. We present PDeepPP, a deep learning framework that integrates pretrained protein language models with parallel transformer-CNN architectures, achieving state-of-the-art performance in peptide characterization tasks. The model's hybrid architecture demonstrates unique capabilities in capturing both local sequence motifs and global structural features, as evidenced by 29% improved cluster separation in UMAP visualizations compared to conventional approaches. Evaluated across 33 biological recognition tasks - including post-translational modification site prediction and bioactive peptide identification - PDeepPP outperformed existing methods in 25 tasks with average AUC improvements of 4.2%. Notably, it achieved 0.9726 accuracy with PR AUC 0.9977 in antimicrobial peptide detection while reducing false negatives by 37.5% in antimalarial recognition scenarios. This framework enables accurate large-scale peptide analysis, achieving 218* acceleration over sequence-alignment-based methods while maintaining 99.5% specificity in critical glycosylation site detection.PDeepPP establishes a new paradigm for computational peptide analysis through its synergistic architecture design, enabling rapid yet precise functional annotation that bridges molecular pattern recognition with translational biomedical applications.We have made our implementation, including code, data, and pretrained models, publicly available via GitHub (https://github.com/fondress/PDeepPP) and Hugging Face (https://huggingface.co/fondress/PDeppPP).

[Read on Arxiv](http://arxiv.org/abs/2502.15610v2)
