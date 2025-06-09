# # 基于自注意力机制的输入依赖型软提示方法在大型语言模型中的应用

发布时间：2025年06月05日

`LLM应用` `迁移学习`

> Leveraging Self-Attention for Input-Dependent Soft Prompting in LLMs

# 摘要

> 大型语言模型在特定领域任务中的表现往往需要进行参数微调，但这一过程计算成本高昂且技术难度较大。本文聚焦于一种有前景的参数高效微调方法——软提示（soft prompting），通过学习少量参数来适应预训练模型以应对下游任务。我们提出了一种基于输入依赖的软提示技术，结合自注意力机制（ID-SPAM），该方法能够根据输入tokens生成软提示，并以不同重要性程度关注不同的tokens。我们的方法简单高效，保持了可训练参数数量的精简。通过在多种任务中与现有最优技术的对比，我们展示了所提方法的优越性，并验证了其在零样本领域迁移能力上的显著提升。

> The performance of large language models in domain-specific tasks necessitates fine-tuning, which is computationally expensive and technically challenging. This paper focuses on parameter-efficient fine-tuning using soft prompting, a promising approach that adapts pre-trained models to downstream tasks by learning a small set of parameters. We propose a novel Input Dependent Soft Prompting technique with a self-Attention Mechanism (ID-SPAM) that generates soft prompts based on the input tokens and attends different tokens with varying importance. Our method is simple and efficient, keeping the number of trainable parameters small. We show the merits of the proposed approach compared to state-of-the-art techniques on various tasks and show the improved zero shot domain transfer capability.

[Arxiv](https://arxiv.org/abs/2506.05629)