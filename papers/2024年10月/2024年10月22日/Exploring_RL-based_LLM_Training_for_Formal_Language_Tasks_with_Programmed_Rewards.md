# 探索基于强化学习的LLM训练在形式语言任务中的应用，结合编程奖励机制

发布时间：2024年10月22日

`LLM应用

理由：这篇论文探讨了使用近端策略优化（PPO）进行直接强化学习（RL）来对齐大型语言模型（LLMs）与下游任务的可行性。具体来说，它研究了在形式语言任务（如数学和编程）中，通过编程明确的奖励信号进行学习的方法。这表明该研究主要关注如何将LLMs应用于特定任务（如情感对齐、算术和游戏合成），并通过强化学习来优化这些应用。因此，这篇论文属于“LLM应用”类别。` `人工智能`

> Exploring RL-based LLM Training for Formal Language Tasks with Programmed Rewards

# 摘要

> # 摘要
近端策略优化（PPO）常用于从人类反馈中进行强化学习，以对齐大型语言模型（LLMs）与下游任务。本文探讨了使用PPO进行直接强化学习（RL）的可行性，即通过编程明确的奖励信号进行学习，而非通过中介奖励模型间接学习。我们聚焦于形式语言任务，如数学和编程，这些任务中可编程奖励函数以自动评估生成输出的质量。我们将此方法应用于情感对齐、简单算术及复杂游戏合成任务。情感对齐任务复现了先前研究，验证了实验设置。结果显示，纯RL训练在形式语言任务中颇具挑战，即使简单算术任务也难获成功。我们提出了一种新的批量熵正则化项以辅助探索，尽管训练尚未完全稳定。研究表明，直接RL训练LLMs更适合于较小的调整，如对齐，而非全新任务的学习，即使奖励信号可通过编程明确表达。

> Proximal Policy Optimization (PPO) is commonly used in Reinforcement Learning from Human Feedback to align large language models (LLMs) with downstream tasks. This paper investigates the feasibility of using PPO for direct reinforcement learning (RL) from explicitly programmed reward signals, as opposed to indirect learning from human feedback via an intermediary reward model. We focus on tasks expressed through formal languages, such as mathematics and programming, where explicit reward functions can be programmed to automatically assess the quality of generated outputs. We apply this approach to a sentiment alignment task, a simple arithmetic task, and a more complex game synthesis task. The sentiment alignment task replicates prior research and serves to validate our experimental setup. Our results show that pure RL-based training for the two formal language tasks is challenging, with success being limited even for the simple arithmetic task. We propose a novel batch-entropy regularization term to aid exploration, although training is not yet entirely stable. Our findings suggest that direct RL training of LLMs may be more suitable for relatively minor changes, such as alignment, than for learning new tasks altogether, even if an informative reward signal can be expressed programmatically.

[Arxiv](https://arxiv.org/abs/2410.17126)