# CORD：在一致性与排名蒸馏之间取得平衡，以达成稳健的检索增强生成

发布时间：2024年12月19日

`RAG` `语言模型` `检索增强生成`

> CORD: Balancing COnsistency and Rank Distillation for Robust Retrieval-Augmented Generation

# 摘要

> 采用检索增强生成（RAG）后，大型语言模型（LLMs）有望依据检索到的上下文进行生成。但 LLMs 的位置偏差会对此造成阻碍，导致无法平等关注所有上下文。此前的工作通过合成具有黄金段扰动位置的上下文，创建了位置多样化的训练集来应对此问题。我们基于此提出了带有增强和提炼的一致性正则化。其一，对每个训练实例进行位置扰动增强，以鼓励无论顺序如何都能做出一致的预测。我们还对这一组合的行为进行提炼，不过在某些 RAG 场景中可能会起到反作用，因为在这些场景中，检索器给定的顺序对生成质量至关重要。于是，我们提出了 CORD，平衡一致性和排名提炼。CORD 从插值空间自适应采样噪声控制的扰动，既确保一致性，又尊重排名先验。实证结果显示，这种平衡使得 CORD 在各类 RAG 基准测试中持续表现优异。

> With the adoption of retrieval-augmented generation (RAG), large language models (LLMs) are expected to ground their generation to the retrieved contexts. Yet, this is hindered by position bias of LLMs, failing to evenly attend to all contexts. Previous work has addressed this by synthesizing contexts with perturbed positions of gold segment, creating a position-diversified train set. We extend this intuition to propose consistency regularization with augmentation and distillation. First, we augment each training instance with its position perturbation to encourage consistent predictions, regardless of ordering. We also distill behaviors of this pair, although it can be counterproductive in certain RAG scenarios where the given order from the retriever is crucial for generation quality. We thus propose CORD, balancing COnsistency and Rank Distillation. CORD adaptively samples noise-controlled perturbations from an interpolation space, ensuring both consistency and respect for the rank prior. Empirical results show this balance enables CORD to outperform consistently in diverse RAG benchmarks.

[Arxiv](https://arxiv.org/abs/2412.14581)