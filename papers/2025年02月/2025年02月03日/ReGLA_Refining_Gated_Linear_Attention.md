# ReGLA: 门控线性注意力的优化

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）中的计算和存储需求问题，特别是softmax注意力的二次计算复杂度。论文提出了线性注意力机制，并深入探讨了影响其性能的关键要素，如特征映射、归一化和门控机制。这些内容属于对LLM内部机制和理论基础的改进和优化，因此应归类为“LLM理论”。` `机器学习`

> ReGLA: Refining Gated Linear Attention

# 摘要

> # 摘要
最近，大型语言模型（LLMs）在复杂语言建模任务中的卓越表现使其脱颖而出。然而，这些模型也因巨大的计算和存储需求而备受关注，这主要源于softmax注意力的二次计算复杂度。为解决这一问题，线性注意力应运而生，旨在降低标准Transformer中固有的二次时空复杂度。在本研究中，我们深入探讨了影响门控线性注意力模块性能的三大关键要素：特征映射、归一化和门控机制。我们设计了一种特征映射函数，解决了以往方案忽视的关键问题，并进一步论证了归一化层在稳定训练过程中的作用。此外，我们还研究了门控机制的饱和现象，并通过精炼模块对其进行了优化。通过大量实验，我们证明了该架构在包括从头训练和持续预训练后的线性化等广泛任务中，均优于之前的门控线性注意力机制。

> Recent advancements in Large Language Models (LLMs) have set themselves apart with their exceptional performance in complex language modelling tasks. However, these models are also known for their significant computational and storage requirements, primarily due to the quadratic computation complexity of softmax attention. To mitigate this issue, linear attention has been designed to reduce the quadratic space-time complexity that is inherent in standard transformers. In this work, we embarked on a comprehensive exploration of three key components that substantially impact the performance of the Gated Linear Attention module: feature maps, normalization, and the gating mechanism. We developed a feature mapping function to address some crucial issues that previous suggestions overlooked. Then we offered further rationale for the integration of normalization layers to stabilize the training process. Moreover, we explored the saturation phenomenon of the gating mechanism and augmented it with a refining module. We conducted extensive experiments and showed our architecture outperforms previous Gated Linear Attention mechanisms in extensive tasks including training from scratch and post-linearization with continual pre-training.

[Arxiv](https://arxiv.org/abs/2502.01578)