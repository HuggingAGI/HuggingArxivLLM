# MeRF: 针对大型推理模型的动机增强型强化微调

发布时间：2025年06月23日

`LLM应用` `人工智能` `逻辑推理`

> MeRF: Motivation-enhanced Reinforcement Finetuning for Large Reasoning Models

# 摘要

> 基于可验证奖励的强化学习（RLVR）已成为一种强大的学习推理范式，帮助大型语言模型（LLMs）应对复杂的推理任务。然而，现有的RLVR方法忽视了LLMs最突出的能力之一——其上下文学习能力，这一点在链式思维（CoT）提示的成功中得到了充分体现。这促使我们探索如何将强化学习与上下文学习有效结合，以更好地提升LLMs的推理能力。

本文中，我们引入了动机增强的强化微调方法（MeRF），这是一种直观且有效的方法，通过让LLMs了解“游戏规则”来增强其强化学习效果。具体来说，MeRF直接将奖励规范注入到提示中，这为模型提供了一个上下文动机，使其在明确优化目标的情况下改进其响应。这一简单的修改利用了LLMs的上下文学习能力，将生成与优化相统一，从而激励模型通过内部动机和外部奖励的双重驱动生成期望的输出。

在骑士与无赖（Knights and Knaves, K&K）逻辑推理基准测试中的实证评估表明，	exttt{MeRF}相较于基线方法取得了显著的性能提升。此外，消融研究表明，当上下文动机与外部奖励函数之间具有一致性时，模型性能会进一步提升，而模型也展示出通过强化学习适应误导性动机的能力。

> Reinforcement Learning with Verifiable Rewards (RLVR) has emerged as a powerful learn-to-reason paradigm for Large Language Models (LLMs) to tackle complex reasoning tasks. However, existing RLVR methods overlook one of the most distinctive capabilities of LLMs, their in-context learning ability, as prominently demonstrated by the success of Chain-of-Thought (CoT) prompting. This motivates us to explore how reinforcement learning can be effectively combined with in-context learning to better improve the reasoning capabilities of LLMs. In this paper, we introduce Motivation-enhanced Reinforcement Finetuning} (MeRF), an intuitive yet effective method enhancing reinforcement learning of LLMs by involving ``telling LLMs the rules of the game''. Specifically, MeRF directly injects the reward specification into the prompt, which serves as an in-context motivation for model to improve its responses with awareness of the optimization objective. This simple modification leverages the in-context learning ability of LLMs aligning generation with optimization, thereby incentivizing the model to generate desired outputs from both inner motivation and external reward. Empirical evaluations on the Knights and Knaves~(K&K) logic puzzle reasoning benchmark demonstrate that \texttt{MeRF} achieves substantial performance gains over baselines. Moreover, ablation studies show that performance improves with greater consistency between the in-context motivation and the external reward function, while the model also demonstrates an ability to adapt to misleading motivations through reinforcement learning.

[Arxiv](https://arxiv.org/abs/2506.18485)