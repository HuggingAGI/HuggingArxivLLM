# CRPO: 置信度-奖励驱动的机器翻译偏好优化

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在机器翻译（MT）中的应用，并提出了一种新的优化方法（CRPO）来提升翻译效果。虽然论文涉及了LLM的理论（如DPO和RLHF），但其核心关注点是如何在实际应用中优化LLM的性能，特别是在机器翻译任务中的应用。因此，将其归类为“LLM应用”更为合适。` `机器翻译`

> CRPO: Confidence-Reward Driven Preference Optimization for Machine Translation

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，但其在机器翻译（MT）中的应用仍面临挑战，主要源于以英语为中心的预训练数据和复杂的RLHF过程。直接偏好优化（DPO）虽然简单高效，但其效果高度依赖偏好数据的质量。为此，我们提出了置信度-奖励驱动的偏好优化（CRPO），通过结合奖励分数和模型置信度，优化微调数据选择。CRPO专注于选择模型不确定或表现不佳的句子对，从而提升学习效果。尽管CRPO主要针对LLMs设计，但它同样适用于NLLB等编码器-解码器模型，展现了其广泛适用性。实验证明，CRPO在翻译准确性和数据效率上均优于RS-DPO、RSO和MBR分数等现有方法。

> Large language models (LLMs) have shown great potential in natural language processing tasks, but their application to machine translation (MT) remains challenging due to pretraining on English-centric data and the complexity of reinforcement learning from human feedback (RLHF). Direct Preference Optimization (DPO) has emerged as a simpler and more efficient alternative, but its performance depends heavily on the quality of preference data. To address this, we propose Confidence-Reward driven Preference Optimization (CRPO), a novel method that combines reward scores with model confidence to improve data selection for fine-tuning. CRPO selects challenging sentence pairs where the model is uncertain or underperforms, leading to more effective learning. While primarily designed for LLMs, CRPO also generalizes to encoder-decoder models like NLLB, demonstrating its versatility. Empirical results show that CRPO outperforms existing methods such as RS-DPO, RSO and MBR score in both translation accuracy and data efficiency.

[Arxiv](https://arxiv.org/abs/2501.13927)