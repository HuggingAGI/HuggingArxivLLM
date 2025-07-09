# StepHint：多层级分步提示提升强化学习推理能力

发布时间：2025年07月03日

`LLM理论` `算法优化` `模型训练`

> StepHint: Multi-level Stepwise Hints Enhance Reinforcement Learning to Reason

# 摘要

> 可验证奖励的强化学习（RLVR）是提升大型语言模型（LLMs）复杂推理能力的有力工具。然而，当前RLVR方法面临两大挑战：近错奖励问题和探索停滞问题。针对这些问题，我们提出了StepHint这一创新算法，通过多层次分步提示帮助模型更高效地探索解空间。StepHint从更强模型中提取有效推理链，并通过自适应划分方法将其拆分为推理步骤。初始步骤作为提示提供给模型，同时多层级提示（每层包含不同步数）辅助模型探索。这种方法既引导模型聚焦于有潜力的解子空间，又保留了其独立探索的灵活性。通过提供提示，StepHint有效缓解了近错奖励问题，显著提升了训练效率。此外，外部推理路径助力模型突破“舒适区”，缓解探索停滞问题。实验结果表明，StepHint在六个数学基准测试中超越了现有增强方法，并在跨领域任务中展现了卓越的泛化能力。

> Reinforcement learning with verifiable rewards (RLVR) is a promising approach for improving the complex reasoning abilities of large language models (LLMs). However, current RLVR methods face two significant challenges: the near-miss reward problem, where a small mistake can invalidate an otherwise correct reasoning process, greatly hindering training efficiency; and exploration stagnation, where models tend to focus on solutions within their ``comfort zone,'' lacking the motivation to explore potentially more effective alternatives. To address these challenges, we propose StepHint, a novel RLVR algorithm that utilizes multi-level stepwise hints to help models explore the solution space more effectively. StepHint generates valid reasoning chains from stronger models and partitions these chains into reasoning steps using our proposed adaptive partitioning method. The initial few steps are used as hints, and simultaneously, multiple-level hints (each comprising a different number of steps) are provided to the model. This approach directs the model's exploration toward a promising solution subspace while preserving its flexibility for independent exploration. By providing hints, StepHint mitigates the near-miss reward problem, thereby improving training efficiency. Additionally, the external reasoning pathways help the model develop better reasoning abilities, enabling it to move beyond its ``comfort zone'' and mitigate exploration stagnation. StepHint outperforms competitive RLVR enhancement methods across six mathematical benchmarks, while also demonstrating superior generalization and excelling over baselines on out-of-domain benchmarks.

[Arxiv](https://arxiv.org/abs/2507.02841)