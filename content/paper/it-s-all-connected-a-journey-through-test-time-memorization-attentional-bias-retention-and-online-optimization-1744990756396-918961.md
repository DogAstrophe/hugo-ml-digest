---
title: "It's All Connected: A Journey Through Test-Time Memorization,
  Attentional Bias, Retention, and Online Optimization"
date: "2025-04-18T15:39:16.396Z"
source: "paper"
link: "http://arxiv.org/abs/2504.13173v1"
thumbnail: ""
tags: ["paper", "ml"]
---



Designing efficient and effective architectural backbones has been in the
core of research efforts to enhance the capability of foundation models.
Inspired by the human cognitive phenomenon of attentional bias-the natural
tendency to prioritize certain events or stimuli-we reconceptualize neural
architectures, including Transformers, Titans, and modern linear recurrent
neural networks as associative memory modules that learn a mapping of keys and
values using an internal objective, referred to as attentional bias.
Surprisingly, we observed that most existing sequence models leverage either
(1) dot-product similarity, or (2) L2 regression objectives as their
attentional bias. Going beyond these objectives, we present a set of
alternative attentional bias configurations along with their effective
approximations to stabilize their training procedure. We then reinterpret
forgetting mechanisms in modern deep learning architectures as a form of
retention regularization, providing a novel set of forget gates for sequence
models. Building upon these insights, we present Miras, a general framework to
design deep learning architectures based on four choices of: (i) associative
memory architecture, (ii) attentional bias objective, (iii) retention gate, and
(iv) memory learning algorithm. We present three novel sequence models-Moneta,
Yaad, and Memora-that go beyond the power of existing linear RNNs while
maintaining a fast parallelizable training process. Our experiments show
different design choices in Miras yield models with varying strengths. For
example, certain instances of Miras achieve exceptional performance in special
tasks such as language modeling, commonsense reasoning, and recall intensive
tasks, even outperforming Transformers and other modern linear recurrent
models.

[Watch on YouTube](http://arxiv.org/abs/2504.13173v1)
