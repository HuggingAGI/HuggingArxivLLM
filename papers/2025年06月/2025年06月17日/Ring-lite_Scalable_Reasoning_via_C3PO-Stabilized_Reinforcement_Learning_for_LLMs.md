# Ring-lite：基于 C3PO 稳定强化学习的大语言模型可扩展推理

发布时间：2025年06月17日

`LLM理论` `大型语言模型`

> Ring-lite: Scalable Reasoning via C3PO-Stabilized Reinforcement Learning for LLMs

# 摘要

> 我们推出了Ring-lite，一款基于专家混合模型（MoE）的大型语言模型，通过强化学习（RL）优化，实现高效且稳健的推理能力。基于拥有168亿参数（其中27.5亿参数被激活）的公开模型Ling-lite，Ring-lite在AIME、LiveCodeBench、GPQA-Diamond等高挑战性基准测试中达到了与顶尖小型推理模型相当的性能，而仅需激活三分之一的参数。为了实现这一突破，我们引入了一种结合蒸馏与强化学习的联合训练流程，揭示了MoE强化学习训练中的独特挑战。首先，我们在强化学习训练中发现了优化不稳定的问题，并提出了约束上下文计算策略优化（C3PO），通过算法-系统协同设计提升训练稳定性和计算效率。其次，我们发现基于熵损失而非验证指标选择蒸馏检查点，能够在后续强化学习训练中实现更优的性能-效率平衡。最后，我们开发了一种两阶段训练范式，有效协调多领域数据整合，解决混合数据集训练中的领域冲突问题。模型、数据集和代码即将发布。

> We present Ring-lite, a Mixture-of-Experts (MoE)-based large language model optimized via reinforcement learning (RL) to achieve efficient and robust reasoning capabilities. Built upon the publicly available Ling-lite model, a 16.8 billion parameter model with 2.75 billion activated parameters, our approach matches the performance of state-of-the-art (SOTA) small-scale reasoning models on challenging benchmarks (e.g., AIME, LiveCodeBench, GPQA-Diamond) while activating only one-third of the parameters required by comparable models. To accomplish this, we introduce a joint training pipeline integrating distillation with RL, revealing undocumented challenges in MoE RL training. First, we identify optimization instability during RL training, and we propose Constrained Contextual Computation Policy Optimization(C3PO), a novel approach that enhances training stability and improves computational throughput via algorithm-system co-design methodology. Second, we empirically demonstrate that selecting distillation checkpoints based on entropy loss for RL training, rather than validation metrics, yields superior performance-efficiency trade-offs in subsequent RL training. Finally, we develop a two-stage training paradigm to harmonize multi-domain data integration, addressing domain conflicts that arise in training with mixed dataset. We will release the model, dataset, and code.

[Arxiv](https://arxiv.org/abs/2506.14731)