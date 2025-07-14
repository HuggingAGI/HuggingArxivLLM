# 基于 LLM 的循环语义增强潜在主题建模

发布时间：2025年07月11日

`LLM应用` `文本挖掘`

> Semantic-Augmented Latent Topic Modeling with LLM-in-the-Loop

# 摘要

> 潜在Dirichlet分配（LDA）是一种用于发现文档集合中抽象主题的著名生成概率模型。本文探讨了通过将大型语言模型（LLMs）整合到初始化和后校正两个关键阶段来增强主题模型的效果。由于LDA的性能高度依赖于初始化的质量，我们进行了大量实验，研究了基于LLM的主题聚类对Gibbs采样算法初始化的影响。有趣的是，实验结果表明，虽然提出的初始化策略改善了LDA的早期迭代，但它对收敛性没有影响，并且与基线相比表现最差。另一方面，LLM增强的后校正在连贯性评估中取得了令人兴奋的5.86%的改进。这些结果突显了LLM循环方法的实际优势，并挑战了LLMs始终是文本挖掘更优选择的观念。

> Latent Dirichlet Allocation (LDA) is a prominent generative probabilistic model used for uncovering abstract topics within document collections. In this paper, we explore the effectiveness of augmenting topic models with Large Language Models (LLMs) through integration into two key phases: Initialization and Post-Correction. Since the LDA is highly dependent on the quality of its initialization, we conduct extensive experiments on the LLM-guided topic clustering for initializing the Gibbs sampling algorithm. Interestingly, the experimental results reveal that while the proposed initialization strategy improves the early iterations of LDA, it has no effect on the convergence and yields the worst performance compared to the baselines. The LLM-enabled post-correction, on the other hand, achieved a promising improvement of 5.86% in the coherence evaluation. These results highlight the practical benefits of the LLM-in-the-loop approach and challenge the belief that LLMs are always the superior text mining alternative.

[Arxiv](https://arxiv.org/abs/2507.08498)