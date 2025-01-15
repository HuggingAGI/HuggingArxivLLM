# TriAdaptLoRA: 灵感源自大脑的三角自适应低秩适应，助力参数高效微调

发布时间：2025年01月14日

`LLM理论

**理由**：这篇论文主要讨论了大型语言模型（LLMs）的微调方法，特别是提出了一种新的参数高效微调框架（TriAdaptLoRA）。论文的核心内容集中在如何通过改进微调方法来提升LLM的性能，这属于对LLM的理论研究和优化，因此分类为LLM理论。` `机器学习`

> TriAdaptLoRA: Brain-Inspired Triangular Adaptive Low-Rank Adaptation for Parameter-Efficient Fine-Tuning

# 摘要

> 大型语言模型（LLMs）的微调是提升下游任务性能的关键。然而，完全微调虽然效果卓越，但计算和资源成本高昂。参数高效微调（PEFT）方法如LoRA通过减少可训练参数来应对这一挑战，但在秩调整效率和任务适应性上仍有不足。我们提出了三角自适应低秩适应（TriAdaptLoRA），这是一种受神经科学启发的新型PEFT框架，能够动态优化参数分配。TriAdaptLoRA的创新点包括：1）将变换矩阵三角分割为上下两部分以最大化参数利用率，2）基于归一化Frobenius范数的参数重要性度量，3）由动态阈值控制的自适应秩增长策略，灵活分配参数。实验表明，TriAdaptLoRA在自然语言理解和生成任务中表现优异，尤其在线性阈值驱动的秩增长下，性能稳定且计算开销低，展现了其作为高效LLM微调方案的潜力。

> The fine-tuning of Large Language Models (LLMs) is pivotal for achieving optimal performance across diverse downstream tasks. However, while full fine-tuning delivers superior results, it entails significant computational and resource costs. Parameter-Efficient Fine-Tuning (PEFT) methods, such as LoRA, address these challenges by reducing the number of trainable parameters, but they often struggle with rank adjustment efficiency and task-specific adaptability. We propose Triangular Adaptive Low-Rank Adaptation (TriAdaptLoRA), a novel PEFT framework inspired by neuroscience principles, which dynamically optimizes the allocation of trainable parameters. TriAdaptLoRA introduces three key innovations: 1) a triangular split of transformation matrices into lower and upper triangular components to maximize parameter utilization, 2) a parameter importance metric based on normalized Frobenius norms for efficient adaptation, and 3) an adaptive rank-growth strategy governed by dynamic thresholds, allowing flexible parameter allocation across training steps. Experiments conducted on a variety of natural language understanding and generation tasks demonstrate that TriAdaptLoRA consistently outperforms existing PEFT methods. It achieves superior performance, enhanced stability, and reduced computational overhead, particularly under linear threshold-driven rank growth. These results highlight its efficacy as a scalable and resource-efficient solution for fine-tuning LLMs.

[Arxiv](https://arxiv.org/abs/2501.08008)