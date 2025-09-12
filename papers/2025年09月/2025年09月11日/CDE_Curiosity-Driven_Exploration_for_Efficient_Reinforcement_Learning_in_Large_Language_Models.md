# CDE：好奇心驱动的探索：面向大型语言模型的高效强化学习

发布时间：2025年09月11日

`强化学习` `基础理论`

> CDE: Curiosity-Driven Exploration for Efficient Reinforcement Learning in Large Language Models

# 摘要

> 基于可验证奖励的强化学习（RLVR）是提升大型语言模型（LLMs）推理能力的强大范式。然而，现有RLVR方法的探索效果欠佳，易导致过早收敛与熵崩溃。为应对这一挑战，我们提出好奇心驱动探索（CDE）框架——该框架借助模型自身的内在好奇心引导探索过程。我们通过行动者（actor）与评论家（critic）的双重信号来量化好奇心：对行动者，采用其生成响应的困惑度；对评论家，则利用多头架构的价值估计方差。这两种信号在RLVR框架中作为探索奖励，共同引导模型学习。理论分析表明，行动者侧奖励本质上能惩罚过度自信导致的错误，并提升正确响应的多样性；此外，我们还将评论家侧奖励与强化学习中成熟的基于计数探索奖励关联起来。实证结果显示，在AIME基准测试中，采用GRPO/PPO时，我们的方法较标准RLVR提升约3个百分点。进一步分析还发现了RLVR中的校准崩溃机制，这为理解大型语言模型的常见失效模式提供了新视角。

> Reinforcement Learning with Verifiable Rewards (RLVR) is a powerful paradigm for enhancing the reasoning ability of Large Language Models (LLMs). Yet current RLVR methods often explore poorly, leading to premature convergence and entropy collapse. To address this challenge, we introduce Curiosity-Driven Exploration (CDE), a framework that leverages the model's own intrinsic sense of curiosity to guide exploration. We formalize curiosity with signals from both the actor and the critic: for the actor, we use perplexity over its generated response, and for the critic, we use the variance of value estimates from a multi-head architecture. Both signals serve as an exploration bonus within the RLVR framework to guide the model. Our theoretical analysis shows that the actor-wise bonus inherently penalizes overconfident errors and promotes diversity among correct responses; moreover, we connect the critic-wise bonus to the well-established count-based exploration bonus in RL. Empirically, our method achieves an approximate +3 point improvement over standard RLVR using GRPO/PPO on AIME benchmarks. Further analysis identifies a calibration collapse mechanism within RLVR, shedding light on common LLM failure modes.

[Arxiv](https://arxiv.org/abs/2509.09675)