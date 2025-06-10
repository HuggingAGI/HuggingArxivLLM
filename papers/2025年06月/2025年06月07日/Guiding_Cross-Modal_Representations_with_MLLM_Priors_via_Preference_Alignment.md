# 通过偏好一致性引导，利用多语言大模型先验优化跨模态表示

发布时间：2025年06月07日

`LLM应用` `计算机视觉`

> Guiding Cross-Modal Representations with MLLM Priors via Preference Alignment

# 摘要

> 尽管对比语言-图像预训练（CLIP）在跨模态检索中表现优异，但其特征空间中仍存在显著的模态间隙。有趣的是，现成的多模态大型语言模型（MLLMs）展现出强大的内在模态对齐特性。尽管基于MLLM的统一架构检索器在一定程度上缓解了这一问题，但其对粗粒度模态对齐机制的依赖从根本上限制了潜力。为此，我们提出了MAPLE（用于嵌入的模态对齐偏好学习），一个利用MLLM中固有的细粒度对齐先验来指导跨模态表示学习的新框架。MAPLE将学习过程表述为强化学习，包含两个关键组件：（1）使用现成的MLLM自动构建偏好数据，以及（2）一种新的相对偏好对齐（RPA）损失，该损失将直接偏好优化（DPO）适应到嵌入学习场景中。实验结果表明，我们的偏好引导对齐在细粒度跨模态检索中取得了显著提升，突显了其在处理微妙语义差异方面的有效性。

> Despite Contrastive Language-Image Pretraining (CLIP)'s remarkable capability to retrieve content across modalities, a substantial modality gap persists in its feature space. Intriguingly, we discover that off-the-shelf MLLMs (Multimodal Large Language Models) demonstrate powerful inherent modality alignment properties. While recent MLLM-based retrievers with unified architectures partially mitigate this gap, their reliance on coarse modality alignment mechanisms fundamentally limits their potential. In this work, We introduce MAPLE (Modality-Aligned Preference Learning for Embeddings), a novel framework that leverages the fine grained alignment priors inherent in MLLM to guide cross modal representation learning. MAPLE formulates the learning process as reinforcement learning with two key components: (1) Automatic preference data construction using off-the-shelf MLLM, and (2) a new Relative Preference Alignment (RPA) loss, which adapts Direct Preference Optimization (DPO) to the embedding learning setting. Experimental results show that our preference-guided alignment achieves substantial gains in fine-grained cross-modal retrieval, underscoring its effectiveness in handling nuanced semantic distinctions.

[Arxiv](https://arxiv.org/abs/2506.06970)