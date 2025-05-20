# 跨越模态鸿沟：通过语义对齐的大语言模型与知识蒸馏提升信道预测能力

发布时间：2025年05月19日

`LLM应用` `人工智能`

> Bridging the Modality Gap: Enhancing Channel Prediction with Semantically Aligned LLMs and Knowledge Distillation

# 摘要

> 在大规模多输入多输出 (m-MIMO) 系统中，准确的信道预测至关重要，它不仅能够提升预编码效果，还能有效降低信道状态信息 (CSI) 反馈的开销。然而，现有方法往往面临累积预测误差和对动态无线环境适应性差的难题。大型语言模型 (LLMs) 在时间序列预测等任务中展现了卓越的建模和泛化能力，使其成为信道预测的潜力股。然而，预训练 LLMs 中的语言知识与 CSI 的特性之间存在显著的模态差距，这对 LLMs 的直接应用提出了挑战。此外，LLMs 的庞大参数规模也限制了其在实际通信系统中的部署。为解决这些问题，我们提出了一种基于语义对齐的大型模型框架——CSI-ALM，成功弥合了自然语言与信道信息之间的模态差距。具体而言，我们设计了跨模态融合模块来对齐 CSI 表示，并通过最大化词嵌入与 CSI 嵌入的余弦相似度构建语义线索。为了降低复杂度并实现实际部署，我们还推出了轻量化版本 CSI-ALM-Light，该版本通过基于注意力矩阵的知识蒸馏策略优化而来。实验结果表明，CSI-ALM 较现有深度学习方法实现了 1 dB 的性能提升。即使在有限训练数据条件下，仅含 0.34M 参数的 CSI-ALM-Light 也达到了与 CSI-ALM 相当的性能，显著优于传统深度学习方法。

> Accurate channel prediction is essential in massive multiple-input multiple-output (m-MIMO) systems to improve precoding effectiveness and reduce the overhead of channel state information (CSI) feedback. However, existing methods often suffer from accumulated prediction errors and poor generalization to dynamic wireless environments. Large language models (LLMs) have demonstrated remarkable modeling and generalization capabilities in tasks such as time series prediction, making them a promising solution. Nevertheless, a significant modality gap exists between the linguistic knowledge embedded in pretrained LLMs and the intrinsic characteristics of CSI, posing substantial challenges for their direct application to channel prediction. Moreover, the large parameter size of LLMs hinders their practical deployment in real-world communication systems with stringent latency constraints. To address these challenges, we propose a novel channel prediction framework based on semantically aligned large models, referred to as CSI-ALM, which bridges the modality gap between natural language and channel information. Specifically, we design a cross-modal fusion module that aligns CSI representations . Additionally, we maximize the cosine similarity between word embeddings and CSI embeddings to construct semantic cues. To reduce complexity and enable practical implementation, we further introduce a lightweight version of the proposed approach, called CSI-ALM-Light. This variant is derived via a knowledge distillation strategy based on attention matrices. Extensive experimental results demonstrate that CSI-ALM achieves a 1 dB gain over state-of-the-art deep learning methods. Moreover, under limited training data conditions, CSI-ALM-Light, with only 0.34M parameters, attains performance comparable to CSI-ALM and significantly outperforms conventional deep learning approaches.

[Arxiv](https://arxiv.org/abs/2505.12729)