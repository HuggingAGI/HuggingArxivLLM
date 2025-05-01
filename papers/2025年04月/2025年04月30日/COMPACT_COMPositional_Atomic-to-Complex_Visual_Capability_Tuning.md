# COMPACT: 组合式原子到复杂视觉能力调优

发布时间：2025年04月30日

`LLM应用` `人工智能` `计算机视觉`

> COMPACT: COMPositional Atomic-to-Complex Visual Capability Tuning

# 摘要

> 多模态大型语言模型（MLLMs）在简单视觉-语言任务中表现优异，但在需要同时识别、计数和理解空间关系等复杂任务中显得力不从心。这可能与视觉指令微调（VIT）这一关键训练步骤的传统关注点有关——过去更注重数据量的扩展，而非训练样本的组合复杂度。为此，我们提出了COMPACT（从原子到复杂视觉能力调优的组合式方法），该方法通过生成一个明确控制训练样本组合复杂度的数据集，为MLLMs提供更高效的复杂能力学习方案。在所有基准测试中，COMPACT在仅使用LLaVA-665k VIT 10%数据量的情况下，达到了与其相当的性能，甚至在某些复杂多能力任务中表现更优。例如，在处理需要四种或更多原子能力的复杂问题时，COMPACT在MMStar和MM-Vet基准上的表现分别比完整的VIT方法提升了83.3%和94.0%。COMPACT提供了一种可扩展、数据高效且针对复杂视觉-语言任务优化的视觉组合式调优方案。

> Multimodal Large Language Models (MLLMs) excel at simple vision-language tasks but struggle when faced with complex tasks that require multiple capabilities, such as simultaneously recognizing objects, counting them, and understanding their spatial relationships. This might be partially the result of the fact that Visual Instruction Tuning (VIT), a critical training step for MLLMs, has traditionally focused on scaling data volume, but not the compositional complexity of training examples. We propose COMPACT (COMPositional Atomic-to-complex visual Capability Tuning), which generates a training dataset explicitly controlling for the compositional complexity of the training examples. The data from COMPACT allows MLLMs to train on combinations of atomic capabilities to learn complex capabilities more efficiently. Across all benchmarks, COMPACT achieves comparable performance to the LLaVA-665k VIT while using less than 10% of its data budget, and even outperforms it on several, especially those involving complex multi-capability tasks. For example, COMPACT achieves substantial 83.3% improvement on MMStar and 94.0% improvement on MM-Vet compared to the full-scale VIT on particularly complex questions that require four or more atomic capabilities. COMPACT offers a scalable, data-efficient, visual compositional tuning recipe to improve on complex visual-language tasks.

[Arxiv](https://arxiv.org/abs/2504.21850)