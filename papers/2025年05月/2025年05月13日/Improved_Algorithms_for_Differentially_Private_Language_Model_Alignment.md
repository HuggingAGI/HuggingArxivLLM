# 提升差分隐私语言模型对齐算法

发布时间：2025年05月13日

`LLM理论` `隐私保护` `机器学习`

> Improved Algorithms for Differentially Private Language Model Alignment

# 摘要

> 语言模型对齐至关重要，它确保了大型语言模型（LLMs）与人类偏好保持一致。然而，这一过程涉及敏感用户数据，引发了重大隐私担忧。尽管先前研究将差分隐私（DP）与对齐技术相结合，但性能仍有限。本文提出了一种新型隐私保护对齐算法，并对其在不同隐私预算和模型下的有效性进行了严格分析。我们的框架支持直接偏好优化（DPO）和基于人类反馈的强化学习（RLHF）两种著名技术。通过在大规模语言模型上的系统实验，我们证明了我们的方法达到了最先进的性能。值得注意的是，我们的DP-AdamW算法与DPO结合使用，在中等隐私预算（ε=2-5）下，对齐质量比现有方法提高了高达15%。我们进一步研究了隐私保证、对齐效果和计算需求之间的相互作用，并提供了优化这些权衡的实用指南。

> Language model alignment is crucial for ensuring that large language models (LLMs) align with human preferences, yet it often involves sensitive user data, raising significant privacy concerns. While prior work has integrated differential privacy (DP) with alignment techniques, their performance remains limited. In this paper, we propose novel algorithms for privacy-preserving alignment and rigorously analyze their effectiveness across varying privacy budgets and models. Our framework can be deployed on two celebrated alignment techniques, namely direct preference optimization (DPO) and reinforcement learning from human feedback (RLHF). Through systematic experiments on large-scale language models, we demonstrate that our approach achieves state-of-the-art performance. Notably, one of our algorithms, DP-AdamW, combined with DPO, surpasses existing methods, improving alignment quality by up to 15% under moderate privacy budgets (ε=2-5). We further investigate the interplay between privacy guarantees, alignment efficacy, and computational demands, providing practical guidelines for optimizing these trade-offs.

[Arxiv](https://arxiv.org/abs/2505.08849)