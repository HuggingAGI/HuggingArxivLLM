# OAT-Rephrase：面向零阶大语言模型微调的优化感知训练数据重述方法

发布时间：2025年06月09日

`LLM理论`

> OAT-Rephrase: Optimization-Aware Training Data Rephrasing for Zeroth-Order LLM Fine-Tuning

# 摘要

> 零阶优化 (ZO) 为大型语言模型 (LLMs) 的微调提供了一种内存高效的替代方案，但噪声梯度估计导致了较慢的收敛速度和不稳定的优化过程。本文提出了一种名为 OAT-Rephrase 的优化感知训练数据重写策略，它利用 LLM 根据其对 ZO 动力学的理解（特别是直接从论文中推导出的 MeZO）来重写训练实例。该方法采用了双阶段管道，包含一个重写器 LLM 和一个语义判别器，确保所有重写均保持任务相关性和逻辑一致性。在五个分类任务和三种 LLM 架构上的评估表明，OAT-Rephrase 一致提升了 MeZO 微调性能，通常缩小或消除了与一阶方法的差距。我们的研究结果表明，优化感知重写为零阶调整方案提供了一种可重复使用且开销低的增强方法。

> Fine-tuning large language models (LLMs) using zeroth-order optimization (ZO) offers a memory-efficient alternative to gradient-based methods but suffers from slower convergence and unstable optimization due to noisy gradient estimates. This paper introduces OAT-Rephrase, an Optimization-Aware Training data rephrasing strategy that leverages an LLM to rephrase training instances based on its understanding of the ZO dynamics, specifically MeZO, derived directly from its paper. The approach incorporates a dual-stage pipeline featuring a rewriter LLM and a semantic judge, ensuring all rephrasings retain task relevance and logical consistency. Evaluations across five classification tasks and three LLM architectures demonstrate that OAT-Rephrase consistently improves MeZO fine-tuning performance, often narrowing or eliminating the gap with first-order methods. Our findings suggest that optimization-aware rephrasing serves as a reusable and low-overhead enhancement for zeroth-order tuning regimes.

[Arxiv](https://arxiv.org/abs/2506.17264)