# 多模态大语言模型中的多层视觉特征融合方法、分析与最佳实践

发布时间：2025年03月08日

`LLM理论` `多模态`

> Multi-Layer Visual Feature Fusion in Multimodal LLMs: Methods, Analysis, and Best Practices

# 摘要

> 近年来，多模态大型语言模型（MLLMs）取得了显著进展，视觉特征在提升模型性能方面发挥着越来越重要的作用。然而，MLLMs中多层视觉特征的整合仍未得到充分探索，尤其是在最优层选择和融合策略方面。现有方法通常依赖于任意的设计选择，导致效果欠佳。本文系统性地研究了多层视觉特征融合的两个核心方面：（1）选择最有效的视觉层；（2）确定与语言模型的最佳融合方式。实验表明，尽管整合多阶段的视觉特征能够提升泛化能力，但加入同一阶段的额外特征通常会导致性能下降。此外，我们发现直接在输入阶段融合多层视觉特征，能持续获得更优且稳定的性能表现。我们的代码已公开发布：https://github.com/EIT-NLP/Layer_Select_Fuse_for_MLLM。

> Multimodal Large Language Models (MLLMs) have made significant advancements in recent years, with visual features playing an increasingly critical role in enhancing model performance. However, the integration of multi-layer visual features in MLLMs remains underexplored, particularly with regard to optimal layer selection and fusion strategies. Existing methods often rely on arbitrary design choices, leading to suboptimal outcomes. In this paper, we systematically investigate two core aspects of multi-layer visual feature fusion: (1) selecting the most effective visual layers and (2) identifying the best fusion approach with the language model. Our experiments reveal that while combining visual features from multiple stages improves generalization, incorporating additional features from the same stage typically leads to diminished performance. Furthermore, we find that direct fusion of multi-layer visual features at the input stage consistently yields superior and more stable performance across various configurations. We make all our code publicly available: https://github.com/EIT-NLP/Layer_Select_Fuse_for_MLLM.

[Arxiv](https://arxiv.org/abs/2503.06063)