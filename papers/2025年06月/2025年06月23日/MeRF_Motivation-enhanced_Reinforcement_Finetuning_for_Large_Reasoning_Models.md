# MeRF：助力大型推理模型的动机增强强化微调

发布时间：2025年06月23日

`LLM理论` `人工智能`

> MeRF: Motivation-enhanced Reinforcement Finetuning for Large Reasoning Models

# 摘要

> 可验证奖励的强化学习（RLVR）为大型语言模型（LLMs）解决复杂推理任务提供了强大支持。然而，现有方法忽视了LLMs的上下文学习能力，这一能力在Chain-of-Thought（CoT）提示的成功中得到了充分体现。为此，我们提出动机增强的强化微调（MeRF），通过“告诉LLMs游戏规则”的方式，将强化学习与上下文学习相结合，提升LLMs的推理能力。具体来说，MeRF将奖励规范直接注入提示，作为模型的上下文动机，使其在明确优化目标的前提下改进响应。这一方法充分利用了LLMs的上下文学习能力，将生成与优化相结合，从而激励模型从内在动机和外部奖励两方面生成期望输出。在Knights and Knaves（K&K）逻辑推理基准测试中，	exttt{MeRF}相比基线方法取得了显著性能提升。此外，消融研究表明，上下文动机与外部奖励函数的一致性越高，性能提升越稳定，同时模型也展现出通过强化学习适应误导性动机的能力。

> Reinforcement Learning with Verifiable Rewards (RLVR) has emerged as a powerful learn-to-reason paradigm for Large Language Models (LLMs) to tackle complex reasoning tasks. However, existing RLVR methods overlook one of the most distinctive capabilities of LLMs, their in-context learning ability, as prominently demonstrated by the success of Chain-of-Thought (CoT) prompting. This motivates us to explore how reinforcement learning can be effectively combined with in-context learning to better improve the reasoning capabilities of LLMs. In this paper, we introduce Motivation-enhanced Reinforcement Finetuning} (MeRF), an intuitive yet effective method enhancing reinforcement learning of LLMs by involving ``telling LLMs the rules of the game''. Specifically, MeRF directly injects the reward specification into the prompt, which serves as an in-context motivation for model to improve its responses with awareness of the optimization objective. This simple modification leverages the in-context learning ability of LLMs aligning generation with optimization, thereby incentivizing the model to generate desired outputs from both inner motivation and external reward. Empirical evaluations on the Knights and Knaves~(K&K) logic puzzle reasoning benchmark demonstrate that \texttt{MeRF} achieves substantial performance gains over baselines. Moreover, ablation studies show that performance improves with greater consistency between the in-context motivation and the external reward function, while the model also demonstrates an ability to adapt to misleading motivations through reinforcement learning.

[Arxiv](https://arxiv.org/abs/2506.18485)