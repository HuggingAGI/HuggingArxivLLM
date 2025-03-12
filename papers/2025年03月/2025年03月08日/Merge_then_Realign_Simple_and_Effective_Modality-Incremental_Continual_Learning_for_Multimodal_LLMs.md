# # 合并后重新对齐：多模态LLMs的简单有效模态增量持续学习方案

发布时间：2025年03月08日

`LLM理论` `人工智能` `多模态`

> Merge then Realign: Simple and Effective Modality-Incremental Continual Learning for Multimodal LLMs

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展显著提升了其 versatility，这是因为它们整合了越来越多的模态。然而，考虑到训练 MLLMs 的高昂成本，我们不仅需要复用现有模型，还希望通过模态增量持续学习（MCL）进一步扩展其支持的模态数量。然而，这种扩展往往会导致之前学习的模态性能下降。本研究重新审视了 MCL，并发现了一个相较于传统持续学习更为严峻的问题：性能下降不仅源于灾难性遗忘，还源于模态无关组件与模态特定组件之间的不匹配。为了解决这一问题，我们提出了一种名为“MErge then ReAlign”（MERA）的简单而优雅的 MCL 方法。该方法无需引入繁重的训练开销或修改模型架构，因此易于部署且在 MLLM 社区中具有高度复用性。大量实验表明，尽管 MERA 简单，但它表现出了令人印象深刻的性能，在扩展到四种模态时，其反向相对增益达到了 99.84%，几乎实现了无损的 MCL 性能。

> Recent advances in Multimodal Large Language Models (MLLMs) have enhanced their versatility as they integrate a growing number of modalities. Considering the heavy cost of training MLLMs, it is necessary to reuse the existing ones and further extend them to more modalities through Modality-incremental Continual Learning (MCL). However, this often comes with a performance degradation in the previously learned modalities. In this work, we revisit the MCL and investigate a more severe issue it faces in contrast to traditional continual learning, that its degradation comes not only from catastrophic forgetting but also from the misalignment between the modality-agnostic and modality-specific components. To address this problem, we propose an elegantly simple MCL paradigm called "MErge then ReAlign" (MERA). Our method avoids introducing heavy training overhead or modifying the model architecture, hence is easy to deploy and highly reusable in the MLLM community. Extensive experiments demonstrate that, despite the simplicity of MERA, it shows impressive performance, holding up to a 99.84% Backward Relative Gain when extending to four modalities, achieving a nearly lossless MCL performance.

[Arxiv](https://arxiv.org/abs/2503.07663)