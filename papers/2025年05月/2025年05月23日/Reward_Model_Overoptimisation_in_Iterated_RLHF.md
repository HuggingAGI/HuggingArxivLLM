# 奖励模型在迭代式强化学习从人类反馈中的过度优化

发布时间：2025年05月23日

`LLM理论` `人工智能` `机器学习`

> Reward Model Overoptimisation in Iterated RLHF

# 摘要

> 从人类反馈中强化学习（RLHF）是使大型语言模型与人类偏好保持一致的常用方法。然而，RLHF常常受到奖励模型过度优化的困扰，即模型过度拟合奖励函数，导致生成的策略无法泛化，只能利用奖励函数的独特性和特殊性。一种常见的缓解策略是迭代RLHF，其中奖励模型会反复重新训练，使用更新的人类反馈，并重新优化策略。尽管这种方法的应用日益广泛，但在此设置下过度优化的动态仍不为人所理解。本研究首次对迭代RLHF中的过度优化进行了全面研究。我们系统地分析了关键设计选择——奖励模型训练数据如何在迭代间传递，优化中使用哪种奖励函数，以及策略如何初始化。通过受控的AlpacaFarm基准测试，我们发现过度优化往往会随着迭代的进行而减少，因为奖励模型越来越接近真实偏好。然而，性能提升会随着时间的推移而减弱，虽然从基础策略重新初始化是稳健的，但它限制了优化的灵活性。其他初始化策略往往无法从早期的过度优化中恢复。这些发现为构建更稳定和可泛化的RLHF管道提供了可操作的见解。

> Reinforcement learning from human feedback (RLHF) is a widely used method for aligning large language models with human preferences. However, RLHF often suffers from reward model overoptimisation, in which models overfit to the reward function, resulting in non-generalisable policies that exploit the idiosyncrasies and peculiarities of the reward function. A common mitigation is iterated RLHF, in which reward models are repeatedly retrained with updated human feedback and policies are re-optimised. Despite its increasing adoption, the dynamics of overoptimisation in this setting remain poorly understood. In this work, we present the first comprehensive study of overoptimisation in iterated RLHF. We systematically analyse key design choices - how reward model training data is transferred across iterations, which reward function is used for optimisation, and how policies are initialised. Using the controlled AlpacaFarm benchmark, we observe that overoptimisation tends to decrease over successive iterations, as reward models increasingly approximate ground-truth preferences. However, performance gains diminish over time, and while reinitialising from the base policy is robust, it limits optimisation flexibility. Other initialisation strategies often fail to recover from early overoptimisation. These findings offer actionable insights for building more stable and generalisable RLHF pipelines.

[Arxiv](https://arxiv.org/abs/2505.18126)