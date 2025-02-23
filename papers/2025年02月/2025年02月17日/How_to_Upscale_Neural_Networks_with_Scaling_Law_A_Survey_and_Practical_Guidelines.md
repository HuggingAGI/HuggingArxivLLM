# 神经网络扩展之道：缩放定律综述与实用指南

发布时间：2025年02月17日

`LLM理论` `人工智能` `机器学习`

> How to Upscale Neural Networks with Scaling Law? A Survey and Practical Guidelines

# 摘要

> 神经缩放法则通过揭示模型规模、数据集体量与计算资源之间的可预测关系，彻底改变了大规模AI模型的设计与优化。早期研究发现了模型性能中的幂律关系，从而形成了计算最优的缩放策略。然而，近期研究凸显了这些法则在不同架构、模态及部署场景上的局限性。稀疏模型、专家混合、检索增强学习以及多模态模型往往偏离传统的缩放模式。此外，缩放行为在视觉、强化学习及微调等领域存在显著差异，凸显了更细致入微方法的必要性。在本综述中，我们整合了50余项研究的见解，深入探讨缩放法则的理论基础、实证发现及其实际影响。我们还深入探讨关键挑战，包括数据效率、推理缩放及架构特定约束，倡导制定适应性缩放策略，以满足实际应用场景的需求。我们建议，尽管缩放法则提供了有用的指导，但它们并不总是适用于所有架构和训练策略。

> Neural scaling laws have revolutionized the design and optimization of large-scale AI models by revealing predictable relationships between model size, dataset volume, and computational resources. Early research established power-law relationships in model performance, leading to compute-optimal scaling strategies. However, recent studies highlighted their limitations across architectures, modalities, and deployment contexts. Sparse models, mixture-of-experts, retrieval-augmented learning, and multimodal models often deviate from traditional scaling patterns. Moreover, scaling behaviors vary across domains such as vision, reinforcement learning, and fine-tuning, underscoring the need for more nuanced approaches. In this survey, we synthesize insights from over 50 studies, examining the theoretical foundations, empirical findings, and practical implications of scaling laws. We also explore key challenges, including data efficiency, inference scaling, and architecture-specific constraints, advocating for adaptive scaling strategies tailored to real-world applications. We suggest that while scaling laws provide a useful guide, they do not always generalize across all architectures and training strategies.

[Arxiv](https://arxiv.org/abs/2502.12051)