# BudgetThinker：借助控制令牌赋能预算感知型LLM推理

发布时间：2025年08月29日

`LLM应用` `基础理论`

> BudgetThinker: Empowering Budget-aware LLM Reasoning with Control Tokens

# 摘要

> 大型语言模型（LLMs）的最新进展通过增加测试时计算量来提升推理能力，这种策略虽有成效，却伴随着显著的延迟和资源开销，限制了其在现实世界中时间受限或成本敏感场景的应用。本文提出新型框架BudgetThinker，旨在让LLM具备预算感知推理能力，实现对思考过程长度的精准控制。我们的方法在推理时周期性插入特殊控制标记，持续向模型反馈剩余标记预算，并结合了全面的两阶段训练流程：先通过监督微调（SFT）让模型适应预算约束，再通过基于课程的强化学习（RL）阶段，利用长度感知奖励函数同时优化准确性和预算合规性。实验表明，在具有挑战性的数学基准测试中，BudgetThinker在不同推理预算下均能保持性能，且显著优于主流基线模型。该方法为开发高效可控的LLM推理提供了可扩展且有效的解决方案，让先进模型在资源受限和实时环境中部署更具实用性。

> Recent advancements in Large Language Models (LLMs) have leveraged increased test-time computation to enhance reasoning capabilities, a strategy that, while effective, incurs significant latency and resource costs, limiting their applicability in real-world time-constrained or cost-sensitive scenarios. This paper introduces BudgetThinker, a novel framework designed to empower LLMs with budget-aware reasoning, enabling precise control over the length of their thought processes. We propose a methodology that periodically inserts special control tokens during inference to continuously inform the model of its remaining token budget. This approach is coupled with a comprehensive two-stage training pipeline, beginning with Supervised Fine-Tuning (SFT) to familiarize the model with budget constraints, followed by a curriculum-based Reinforcement Learning (RL) phase that utilizes a length-aware reward function to optimize for both accuracy and budget adherence. We demonstrate that BudgetThinker significantly surpasses strong baselines in maintaining performance across a variety of reasoning budgets on challenging mathematical benchmarks. Our method provides a scalable and effective solution for developing efficient and controllable LLM reasoning, making advanced models more practical for deployment in resource-constrained and real-time environments.

[Arxiv](https://arxiv.org/abs/2508.17196)