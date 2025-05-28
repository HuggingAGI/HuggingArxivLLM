# 优化全局搜索：基于LLM的全局优化通过搜索空间划分实现提升

发布时间：2025年05月27日

`LLM应用`

> Improving LLM-based Global Optimization with Search Space Partitioning

# 摘要

> 大型语言模型 (LLMs) 近期在昂贵黑盒函数的全局优化框架中崭露头角，成为有效的替代模型和候选生成器。尽管展现出令人鼓舞的结果，但基于 LLM 的方法在面对高维搜索空间或缺乏领域特定先验知识时，往往难以提出有信息量的建议。为解决这些问题，我们提出了一种新颖的全局优化算法 HOLLM，该算法通过将搜索空间划分为有前景的子区域，来增强 LLM 驱动的采样过程。每个子区域作为一个 ``元臂''，通过基于多臂老虎机启发的评分机制进行选择，这种机制能够有效平衡探索与利用。在每个选定的子区域内，LLM 会提出高质量的候选点，无需任何显式的领域知识。在标准优化基准上的实证评估表明，HOLLM 一致匹配或超越了领先的贝叶斯优化和信任区域方法，同时显著优于全局 LLM 基础的采样策略。

> Large Language Models (LLMs) have recently emerged as effective surrogate models and candidate generators within global optimization frameworks for expensive blackbox functions. Despite promising results, LLM-based methods often struggle in high-dimensional search spaces or when lacking domain-specific priors, leading to sparse or uninformative suggestions. To overcome these limitations, we propose HOLLM, a novel global optimization algorithm that enhances LLM-driven sampling by partitioning the search space into promising subregions. Each subregion acts as a ``meta-arm'' selected via a bandit-inspired scoring mechanism that effectively balances exploration and exploitation. Within each selected subregion, an LLM then proposes high-quality candidate points, without any explicit domain knowledge. Empirical evaluation on standard optimization benchmarks shows that HOLLM consistently matches or surpasses leading Bayesian optimization and trust-region methods, while substantially outperforming global LLM-based sampling strategies.

[Arxiv](https://arxiv.org/abs/2505.21372)