# # 团队合作的语言：LLM 引导的多智能体强化学习信用分配

发布时间：2025年02月05日

`Agent

理由：这篇论文主要讨论了在多智能体强化学习（MARL）中如何利用大型语言模型（LLM）来生成针对特定代理的密集奖励函数，以解决信用分配问题。研究的核心是智能体（Agent）的行为和奖励机制，因此应归类为Agent。` `多智能体系统`

> Speaking the Language of Teamwork: LLM-Guided Credit Assignment in Multi-Agent Reinforcement Learning

# 摘要

> # 摘要
信用分配，即将团队成败归因于个体代理的过程，始终是多智能体强化学习（MARL）中的核心难题，尤其在奖励稀疏的环境中。传统方法如价值分解常导致次优策略，而设计符合人类直觉的密集奖励函数则复杂且耗时。本文提出了一种创新框架，利用大型语言模型（LLM）根据任务描述和团队目标生成针对特定代理的密集奖励。通过多轮查询学习基于潜力的奖励函数，我们的方法有效降低了排名误差，同时让LLM能够评估每个代理对整体任务的贡献。大量实验表明，与现有MARL基线相比，我们的方法在收敛速度和策略回报上均表现出色。

> Credit assignment, the process of attributing credit or blame to individual agents for their contributions to a team's success or failure, remains a fundamental challenge in multi-agent reinforcement learning (MARL), particularly in environments with sparse rewards. Commonly-used approaches such as value decomposition often lead to suboptimal policies in these settings, and designing dense reward functions that align with human intuition can be complex and labor-intensive. In this work, we propose a novel framework where a large language model (LLM) generates dense, agent-specific rewards based on a natural language description of the task and the overall team goal. By learning a potential-based reward function over multiple queries, our method reduces the impact of ranking errors while allowing the LLM to evaluate each agent's contribution to the overall task. Through extensive experiments, we demonstrate that our approach achieves faster convergence and higher policy returns compared to state-of-the-art MARL baselines.

[Arxiv](https://arxiv.org/abs/2502.03723)