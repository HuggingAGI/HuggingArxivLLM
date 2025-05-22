# ConvSearch-R1：利用强化学习提升对话搜索中的推理驱动查询重写

发布时间：2025年05月21日

`LLM应用` `对话式搜索系统`

> ConvSearch-R1: Enhancing Query Reformulation for Conversational Search with Reasoning via Reinforcement Learning

# 摘要

> 对话式搜索系统需要处理上下文依赖的查询，这些查询常包含歧义、遗漏和共指。对话式查询重构（CQR）通过将这些查询转换为适合现成检索器的自包含形式来应对这一挑战。然而，现有的CQR方法存在两个关键限制：对昂贵的人工标注或大型语言模型的外部监督的高度依赖，以及重写模型与下游检索器之间的对齐不足。我们提出了ConvSearch-R1，这是第一个完全消除对外部重写监督依赖的自驱动框架，通过强化学习直接利用检索信号优化重构。我们的创新两阶段方法结合了自驱动策略预热，通过检索引导的自蒸馏解决冷启动问题，随后是带有专门设计的排名激励奖励塑造机制的检索引导强化学习，解决了传统检索指标中的稀疏性问题。在TopiOCQA和QReCC数据集上的广泛实验表明，ConvSearch-R1显著优于之前的最先进方法，在具有挑战性的TopiOCQA数据集上实现了超过10%的改进，同时使用较小的3B参数模型且无需任何外部监督。

> Conversational search systems require effective handling of context-dependent queries that often contain ambiguity, omission, and coreference. Conversational Query Reformulation (CQR) addresses this challenge by transforming these queries into self-contained forms suitable for off-the-shelf retrievers. However, existing CQR approaches suffer from two critical constraints: high dependency on costly external supervision from human annotations or large language models, and insufficient alignment between the rewriting model and downstream retrievers. We present ConvSearch-R1, the first self-driven framework that completely eliminates dependency on external rewrite supervision by leveraging reinforcement learning to optimize reformulation directly through retrieval signals. Our novel two-stage approach combines Self-Driven Policy Warm-Up to address the cold-start problem through retrieval-guided self-distillation, followed by Retrieval-Guided Reinforcement Learning with a specially designed rank-incentive reward shaping mechanism that addresses the sparsity issue in conventional retrieval metrics. Extensive experiments on TopiOCQA and QReCC datasets demonstrate that ConvSearch-R1 significantly outperforms previous state-of-the-art methods, achieving over 10% improvement on the challenging TopiOCQA dataset while using smaller 3B parameter models without any external supervision.

[Arxiv](https://arxiv.org/abs/2505.15776)