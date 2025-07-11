# PLAN-TUNING：通过后训练的语言模型学习逐步规划以解决复杂问题

发布时间：2025年07月10日

`LLM应用` `人工智能`

> PLAN-TUNING: Post-Training Language Models to Learn Step-by-Step Planning for Complex Problem Solving

# 摘要

> 近期研究发现，将复杂问题分解为简单子任务--这是人类自然规划的核心能力--能够显著提升大型语言模型 (LLMs) 的性能。然而，如何在模型微调阶段利用这些规划结构来提升小型开源 LLM 的性能，仍然是一个未被充分探索的领域。为此，我们提出了 PLAN-TUNING，一个统一的微调框架，它通过（i）从大规模 LLM 中提取合成的任务分解（即“规划轨迹”），并（ii）通过监督学习和强化学习目标对小型模型进行微调，模仿这些规划过程以提升复杂推理能力。在 GSM8k 和 MATH 基准测试中，经过规划微调的模型比强基线模型平均提升了约【数学公式】。此外，在跨领域数据集上，规划微调模型表现出更好的泛化能力，分别在 OlympiadBench 和 AIME 2024 上平均提升了约【数学公式】和【数学公式】。我们的详细分析展示了规划轨迹如何提升复杂推理能力，证明了 PLAN-TUNING 是一种有效的策略，能够显著提升小型 LLM 的任务特定性能。

> Recently, decomposing complex problems into simple subtasks--a crucial part of human-like natural planning--to solve the given problem has significantly boosted the performance of large language models (LLMs). However, leveraging such planning structures during post-training to boost the performance of smaller open-source LLMs remains underexplored. Motivated by this, we introduce PLAN-TUNING, a unified post-training framework that (i) distills synthetic task decompositions (termed "planning trajectories") from large-scale LLMs and (ii) fine-tunes smaller models via supervised and reinforcement-learning objectives designed to mimic these planning processes to improve complex reasoning. On GSM8k and the MATH benchmarks, plan-tuned models outperform strong baselines by an average $\sim7\%$. Furthermore, plan-tuned models show better generalization capabilities on out-of-domain datasets, with average $\sim10\%$ and $\sim12\%$ performance improvements on OlympiadBench and AIME 2024, respectively. Our detailed analysis demonstrates how planning trajectories improves complex reasoning capabilities, showing that PLAN-TUNING is an effective strategy for improving task-specific performance of smaller LLMs.

[Arxiv](https://arxiv.org/abs/2507.07495)