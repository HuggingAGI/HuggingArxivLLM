# SynerGen-VL：致力于实现结合视觉专家和令牌折叠的协同图像理解与生成

发布时间：2024年12月12日

`LLM应用` `多模态` `图像理解与生成`

> SynerGen-VL: Towards Synergistic Image Understanding and Generation with Vision Experts and Token Folding

# 摘要

> 大型语言模型（LLMs）取得了显著成功，并拓展至多模态领域，在图像理解与生成方面表现出色。近来，开发融合这些能力的统一多模态大型语言模型（MLLMs）的努力成果喜人。然而，现有的方法在模型架构或训练流程上设计复杂，加大了模型训练和扩展的难度。本文中，我们提出了 SynerGen-VL，这是一个简单却强大的无编码器 MLLM，兼具图像理解和生成能力。为应对现有无编码器统一 MLLMs 存在的挑战，我们引入了令牌折叠机制和基于视觉专家的渐进式对齐预训练策略，有效支持高分辨率图像理解的同时降低了训练复杂度。通过使用统一的下一个令牌预测目标对大规模混合图像 - 文本数据进行训练，SynerGen-VL 在参数规模相当或更小时达到或超越了现有无编码器统一 MLLMs 的性能，缩小了与特定任务最先进模型的差距，为未来统一 MLLMs 指明了充满希望的发展方向。我们的代码和模型将会发布。

> The remarkable success of Large Language Models (LLMs) has extended to the multimodal domain, achieving outstanding performance in image understanding and generation. Recent efforts to develop unified Multimodal Large Language Models (MLLMs) that integrate these capabilities have shown promising results. However, existing approaches often involve complex designs in model architecture or training pipeline, increasing the difficulty of model training and scaling. In this paper, we propose SynerGen-VL, a simple yet powerful encoder-free MLLM capable of both image understanding and generation. To address challenges identified in existing encoder-free unified MLLMs, we introduce the token folding mechanism and the vision-expert-based progressive alignment pretraining strategy, which effectively support high-resolution image understanding while reducing training complexity. After being trained on large-scale mixed image-text data with a unified next-token prediction objective, SynerGen-VL achieves or surpasses the performance of existing encoder-free unified MLLMs with comparable or smaller parameter sizes, and narrows the gap with task-specific state-of-the-art models, highlighting a promising path toward future unified MLLMs. Our code and models shall be released.

[Arxiv](https://arxiv.org/abs/2412.09604)