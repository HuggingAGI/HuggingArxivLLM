# 基于激活信息的大型语言模型融合

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要讨论了模型合并技术，特别是通过激活信息合并（AIM）来提升大型语言模型（LLMs）的性能和鲁棒性。论文的核心内容涉及LLMs的参数和嵌入的合并方法，以及如何通过引入激活空间信息来改进这些方法。这些内容属于对LLMs的理论研究和改进，因此应归类为“LLM理论”。` `机器学习`

> Activation-Informed Merging of Large Language Models

# 摘要

> # 摘要
模型合并是一种将多个微调后的大型语言模型（LLMs）的参数和嵌入结合起来的方法，能够在保持计算效率的同时，显著提升模型在各种任务中的表现。本文提出了一种名为激活信息合并（AIM）的技术，通过将LLMs激活空间的信息融入合并过程，进一步提升模型的性能和鲁棒性。AIM作为一种灵活的补充方案，适用于所有现有的合并方法，旨在保留基础模型中的关键权重，并借鉴了持续学习（CL）和模型压缩的原理。通过使用任务无关的校准集，AIM在合并过程中有选择地优先保留重要权重。实验表明，AIM显著提升了合并模型在多个基准测试中的表现，基准性能提升高达40%。我们的研究证明，激活空间信息的引入为LLMs的模型合并策略带来了显著进步。

> Model merging, a method that combines the parameters and embeddings of multiple fine-tuned large language models (LLMs), offers a promising approach to enhance model performance across various tasks while maintaining computational efficiency. This paper introduces Activation-Informed Merging (AIM), a technique that integrates the information from the activation space of LLMs into the merging process to improve performance and robustness. AIM is designed as a flexible, complementary solution that is applicable to any existing merging method. It aims to preserve critical weights from the base model, drawing on principles from continual learning~(CL) and model compression. Utilizing a task-agnostic calibration set, AIM selectively prioritizes essential weights during merging. We empirically demonstrate that AIM significantly enhances the performance of merged models across multiple benchmarks. Our findings suggest that considering the activation-space information can provide substantial advancements in the model merging strategies for LLMs with up to 40\% increase in benchmark performance.

[Arxiv](https://arxiv.org/abs/2502.02421)