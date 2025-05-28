# # 语言模型蒸馏：从时序差分模仿学习视角出发

发布时间：2025年05月24日

`LLM理论` `机器学习`

> Language Model Distillation: A Temporal Difference Imitation Learning Perspective

# 摘要

> 大型语言模型推动了众多自然语言处理 (NLP) 任务的显著进步，但其庞大的规模也带来了高昂的计算成本。为此，蒸馏技术应运而生，将这些大型模型压缩为更高效的小型模型。现有的许多语言模型蒸馏方法可被视为模仿学习或逆向强化学习中的行为复制。这一视角启发了后续研究，这些研究进一步探索了 (逆) 强化学习技术，包括行为复制和时间差分学习方法的各种变体。与提出新的时间差分方法不同，我们提出了一种基于教师模型分布稀疏性的通用时间差分蒸馏框架。具体而言，语言模型通常将大部分概率质量集中分配给一小部分标记。基于这一观察，我们设计了一个在精简动作空间（词汇表子集）上运行的时间差分学习框架，并展示了如何从中推导出实用算法以及性能的显著提升。

> Large language models have led to significant progress across many NLP tasks, although their massive sizes often incur substantial computational costs. Distillation has become a common practice to compress these large and highly capable models into smaller, more efficient ones. Many existing language model distillation methods can be viewed as behavior cloning from the perspective of imitation learning or inverse reinforcement learning. This viewpoint has inspired subsequent studies that leverage (inverse) reinforcement learning techniques, including variations of behavior cloning and temporal difference learning methods. Rather than proposing yet another specific temporal difference method, we introduce a general framework for temporal difference-based distillation by exploiting the distributional sparsity of the teacher model. Specifically, it is often observed that language models assign most probability mass to a small subset of tokens. Motivated by this observation, we design a temporal difference learning framework that operates on a reduced action space (a subset of vocabulary), and demonstrate how practical algorithms can be derived and the resulting performance improvements.

[Arxiv](https://arxiv.org/abs/2505.20335)