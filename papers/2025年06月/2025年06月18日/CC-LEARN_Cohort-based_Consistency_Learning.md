# CC-LEARN：基于群体的一致性学习

发布时间：2025年06月18日

`LLM理论` `人工智能`

> CC-LEARN: Cohort-based Consistency Learning

# 摘要

> 大型语言模型在众多任务中表现出色，但在一致性和鲁棒性推理方面仍面临挑战。为此，我们提出了基于群体一致性的学习框架（Cohort-based Consistency Learning，CC-Learn），一个通过训练相似问题群体（基于共享程序化抽象）来提升大型语言模型推理可靠性的强化学习框架。为了实现群体级别的推理一致性，我们定义了一个复合目标函数，其中包括群体准确率、有效问题分解的检索奖励以及对简单或无效查询的拒绝惩罚，这些都可以被强化学习直接优化，而传统的监督微调方法无法做到这一点。通过优化这一奖励函数，模型能够为所有群体成员采用统一的推理模式。在具有挑战性的推理基准测试（包括ARC挑战集和策略问答数据集）中，CC-Learn相较于预训练和监督微调模型，在准确性和推理稳定性方面均有显著提升。这些结果表明，基于群体的强化学习能够有效增强大型语言模型的推理一致性。

> Large language models excel at many tasks but still struggle with consistent, robust reasoning. We introduce Cohort-based Consistency Learning (CC-Learn), a reinforcement learning framework that improves the reliability of LLM reasoning by training on cohorts of similar questions derived from shared programmatic abstractions. To enforce cohort-level consistency, we define a composite objective combining cohort accuracy, a retrieval bonus for effective problem decomposition, and a rejection penalty for trivial or invalid lookups that reinforcement learning can directly optimize, unlike supervised fine-tuning. Optimizing this reward guides the model to adopt uniform reasoning patterns across all cohort members. Experiments on challenging reasoning benchmarks (including ARC-Challenge and StrategyQA) show that CC-Learn boosts both accuracy and reasoning stability over pretrained and SFT baselines. These results demonstrate that cohort-level RL effectively enhances reasoning consistency in LLMs.

[Arxiv](https://arxiv.org/abs/2506.15662)