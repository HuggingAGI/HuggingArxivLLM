# RewardAnything：通用型原则遵循奖励模型

发布时间：2025年06月04日

`LLM理论` `大型语言模型` `奖励建模`

> RewardAnything: Generalizable Principle-Following Reward Models

# 摘要

> 奖励模型（Reward Models）在大型语言模型优化中至关重要，但传统方法存在局限性。它们通常基于固定偏好数据集训练，导致对单一隐含偏好分布的僵化对齐，难以适应多样化的现实需求，例如从任务的简洁性到详细解释。传统方法通过收集任务特定偏好数据并重新训练奖励模型，资源消耗巨大且常导致有偏奖励，限制了实际应用。

我们提出通用且遵循原则的奖励模型，突破这一限制。奖励模型应理解和遵循动态提供的奖励原则的自然语言规范，类似于大型语言模型中的指令遵循。为此，我们开发了RABench，一个专注于跨多样化原则通用性的基准测试，用于评估奖励模型。评估显示，当前奖励模型的通用性较差。

作为解决方案，我们推出RewardAnything，一种新型奖励模型，经过设计和训练，可以明确遵循自然语言原则。在传统奖励模型基准上，通过指定一个明确定义的原则，RewardAnything实现了SotA性能。RABench的结果表明，无需重新训练即可很好地适应新原则。此外，RewardAnything与现有RLHF方法无缝集成，我们通过案例研究展示了如何仅使用自然语言原则自动且高效地对齐大型语言模型。

> Reward Models, essential for guiding Large Language Model optimization, are typically trained on fixed preference datasets, resulting in rigid alignment to single, implicit preference distributions. This prevents adaptation to diverse real-world needs-from conciseness in one task to detailed explanations in another. The standard practice of collecting task-specific preference data and retraining reward models is resource-intensive, often producing biased rewards, and limits practical application. We introduce generalizable, principle-following reward models. We propose that RMs should understand and adhere to dynamically provided natural language specifications of reward principles, similar to instruction-following in LLMs. To measure this capability, we develop RABench, a comprehensive benchmark for RMs focusing on generalization across diverse principles. Evaluations on RABench reveal poor generalization of current RMs. As a solution, we present RewardAnything, a novel RM designed and trained to explicitly follow natural language principles. We achieve SotA performance with RewardAnything in traditional RM benchmark simply by specifying a well-defined principle, and results on RABench show we excel in adapting to novel principles without retraining. Furthermore, RewardAnything integrates seamlessly with existing RLHF methods and we show by a case study on how to automatically and efficiently align LLMs with only natural language principles.

[Arxiv](https://arxiv.org/abs/2506.03637)