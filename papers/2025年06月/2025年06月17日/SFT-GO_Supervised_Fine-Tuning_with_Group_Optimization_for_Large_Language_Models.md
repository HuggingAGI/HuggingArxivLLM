# SFT-GO：基于组优化的大型语言模型监督式微调方法

发布时间：2025年06月17日

`LLM理论` `机器学习`

> SFT-GO: Supervised Fine-Tuning with Group Optimization for Large Language Models

# 摘要

> 监督微调（SFT）已成为将大型语言模型（LLMs）与人类期望和特定下游任务对齐的不可或缺的一步。然而，现有的SFT方法往往将每个训练样本简单地视为统一的序列，在训练过程中给予所有标记同等的重视。这种做法忽视了一个关键事实：通常只有部分标记包含关键的、任务特定的信息。为了解决这一问题，我们提出了监督微调结合组优化（SFT-GO），一种根据标记重要性进行差异化处理的创新方法。

SFT-GO通过将每个样本中的标记按照重要性值进行分组，并结合最差组损失和标准交叉熵损失的加权组合来优化LLM。这一机制能够自适应地强调最具挑战性的标记组，并引导模型更好地处理不同组的分布，从而显著提升整体学习效果。我们从理论上分析了SFT-GO的收敛速率，证明了其高效性。在实证研究中，我们采用了三种不同的标记分组策略应用SFT-GO，并展示了使用SFT-GO训练的模型在多个流行LLM基准测试中始终优于基线方法。这些改进在各种数据集和基础模型上均表现一致，证明了我们方法的鲁棒性和有效性。

> Supervised fine-tuning (SFT) has become an essential step in tailoring large language models (LLMs) to align with human expectations and specific downstream tasks. However, existing SFT methods typically treat each training instance as a uniform sequence, giving equal importance to all tokens regardless of their relevance. This overlooks the fact that only a subset of tokens often contains critical, task-specific information. To address this limitation, we introduce Supervised Fine-Tuning with Group Optimization (SFT-GO), a novel approach that treats groups of tokens differently based on their importance.SFT-GO groups tokens in each sample based on their importance values and optimizes the LLM using a weighted combination of the worst-group loss and the standard cross-entropy loss. This mechanism adaptively emphasizes the most challenging token groups and guides the model to better handle different group distributions, thereby improving overall learning dynamics. We provide a theoretical analysis of SFT-GO's convergence rate, demonstrating its efficiency. Empirically, we apply SFT-GO with three different token grouping strategies and show that models trained with SFT-GO consistently outperform baseline approaches across popular LLM benchmarks. These improvements hold across various datasets and base models, demonstrating the robustness and the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2506.15021)