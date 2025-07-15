# 组相对策略优化能否助力泰国法律推理与问答性能的优化？

发布时间：2025年07月13日

`RAG` `问答系统`

> Can Group Relative Policy Optimization Improve Thai Legal Reasoning and Question Answering?

# 摘要

> 检索增强生成（RAG）系统在泰语法律问答领域表现仍有提升空间，尤其在处理复杂法律推理问题时。我们提出了一种基于组的相对策略优化（GRPO）方法，通过将大型语言模型（LLMs）对齐，显著提升了法律引用的准确性和回答质量。该方法采用BGE-M3嵌入技术作为语义相似性奖励，计算成本较传统大型语言模型裁判降低了2.5倍。实验数据显示，与基线模型相比，GRPO实现了90%的引用-F1提升，并在联合质量指标上比指令微调提高了31%。更重要的是，该方法在复杂法律推理任务上展现出更强的鲁棒性，为提升泰语法律LLMs性能提供了高效解决方案。

> The Retrieval-Augmented Generation (RAG) systems' performance on Thai legal question answering is still limited, especially for questions requiring extensive, complex legal reasoning. To address these limitations, we introduce an approach aligning LLMs toward improved law citation accuracy and better response quality using Group-Relative Policy Optimization (GRPO). Our approach leverages BGE-M3 embeddings as a cost-efficient semantic-similarity reward, significantly reducing computational expenses up to 2.5x compared to large language model judges. Experiments on the NitiBench benchmark demonstrate substantial improvements: GRPO achieves up to 90% citation-F1 gains from the base model and a 31% increase in joint quality metrics over instruction tuning. Crucially, our method shows enhanced robustness on complex legal reasoning tasks compared to instruction tuning, providing an effective and resource-efficient solution for enhancing Thai legal LLMs.

[Arxiv](https://arxiv.org/abs/2507.09638)