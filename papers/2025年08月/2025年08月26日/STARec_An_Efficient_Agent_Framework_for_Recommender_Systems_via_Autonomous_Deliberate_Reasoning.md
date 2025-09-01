# STARec：基于自主审慎推理的推荐系统高效智能体框架

发布时间：2025年08月26日

`Agent` `零售与电商`

> STARec: An Efficient Agent Framework for Recommender Systems via Autonomous Deliberate Reasoning

# 摘要

> 现代推荐系统虽在应对信息过载中发挥关键作用，却仍受限于静态用户建模和被动决策范式的根本局限。当前基于大型语言模型（LLM）的智能体因过度依赖启发式模式匹配而继承了这些缺陷，导致推荐易出现浅层相关偏差、因果推理能力受限，且在稀疏数据场景中表现脆弱。为此，我们提出STARec——一个慢思考增强型智能体框架，为推荐系统赋予自主审慎的推理能力。每个用户被建模为具备并行认知机制的智能体：快速响应模块处理即时交互，慢速推理模块则进行思维链推理。为培养智能体内在的慢思考能力，我们提出锚定强化训练——一种两阶段训练范式，将高级推理模型的结构化知识蒸馏与偏好对齐的奖励塑造相结合。该混合方法帮助智能体掌握基础能力（如偏好总结、推理生成），同时通过模拟反馈循环实现动态策略调整。在MovieLens 1M和Amazon CDs基准数据集上的实验显示，即便仅使用0.4%的完整训练数据，STARec仍较最先进的基线模型取得显著性能提升。

> While modern recommender systems are instrumental in navigating information abundance, they remain fundamentally limited by static user modeling and reactive decision-making paradigms. Current large language model (LLM)-based agents inherit these shortcomings through their overreliance on heuristic pattern matching, yielding recommendations prone to shallow correlation bias, limited causal inference, and brittleness in sparse-data scenarios. We introduce STARec, a slow-thinking augmented agent framework that endows recommender systems with autonomous deliberative reasoning capabilities. Each user is modeled as an agent with parallel cognitions: fast response for immediate interactions and slow reasoning that performs chain-of-thought rationales. To cultivate intrinsic slow thinking, we develop anchored reinforcement training - a two-stage paradigm combining structured knowledge distillation from advanced reasoning models with preference-aligned reward shaping. This hybrid approach scaffolds agents in acquiring foundational capabilities (preference summarization, rationale generation) while enabling dynamic policy adaptation through simulated feedback loops. Experiments on MovieLens 1M and Amazon CDs benchmarks demonstrate that STARec achieves substantial performance gains compared with state-of-the-art baselines, despite using only 0.4% of the full training data.

[Arxiv](https://arxiv.org/abs/2508.18812)