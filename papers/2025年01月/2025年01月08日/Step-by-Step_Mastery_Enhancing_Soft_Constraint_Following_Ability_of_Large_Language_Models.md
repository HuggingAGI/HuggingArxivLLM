# 逐步精通：提升大型语言模型的软约束遵循能力

发布时间：2025年01月08日

`LLM应用

理由：该论文摘要主要讨论了如何提升大型语言模型（LLMs）在遵循多约束指令方面的能力，特别是针对软约束的自动化验证问题。论文提出了一种自动化生成高质量输出的流程，并引入了基于课程学习的训练范式。这些内容属于LLM在实际应用中的改进和优化，因此应归类为LLM应用。`

> Step-by-Step Mastery: Enhancing Soft Constraint Following Ability of Large Language Models

# 摘要

> 大型语言模型（LLMs）在遵循多约束指令方面至关重要，但软约束因其语义关联性难以自动化验证，成为LLMs的一大挑战。为提升LLMs的软约束遵循能力，我们设计了一套自动化生成高质量输出的流程，并引入基于课程学习的训练范式。通过实验验证了方法的有效性，并深入分析了改进的关键因素。相关数据集和代码已开源，详见https://github.com/Rainier-rq/FollowSoftConstraints。

> It is crucial for large language models (LLMs) to follow instructions that involve multiple constraints. However, soft constraints are semantically related and difficult to verify through automated methods. These constraints remain a significant challenge for LLMs. To enhance the ability of LLMs to follow soft constraints, we initially design a pipeline to obtain high-quality outputs automatically. Additionally, to fully utilize the acquired data, we introduce a training paradigm based on curriculum learning. We experimentally evaluate the effectiveness of our methods in improving LLMs' soft constraint following ability and analyze the factors driving the improvements. The datasets and code are publicly available at https://github.com/Rainier-rq/FollowSoftConstraints.

[Arxiv](https://arxiv.org/abs/2501.04945)