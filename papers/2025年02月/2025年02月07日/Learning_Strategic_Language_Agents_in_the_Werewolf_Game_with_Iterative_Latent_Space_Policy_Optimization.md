# 策略性语言智能体的学习在狼人杀游戏中通过迭代潜在空间策略优化方法

发布时间：2025年02月07日

`LLM应用` `社交游戏`

> Learning Strategic Language Agents in the Werewolf Game with Iterative Latent Space Policy Optimization

# 摘要

> 基于大型语言模型（LLM）的代理在开放对话和多步骤决策领域取得了显著进展。然而，将这些代理应用于如狼人杀等需要策略性决策和自由语言互动的社交推理游戏，仍面临诸多挑战。传统基于反事实遗憾最小化（CFR）或强化学习（RL）的方法依赖预定义动作空间，难以应对无约束文本动作空间的语言游戏。同时，纯LLM代理常受内在偏见影响，且需庞大数据集进行微调。我们提出潜在空间策略优化（LSPO），一种迭代框架，通过将自由文本映射至离散潜在空间，使CFR和RL等方法能更高效地学习战略策略。随后，我们将学到的策略转换为自然语言对话，并通过直接偏好优化（DPO）微调LLM。通过迭代交替这两个阶段，LSPO代理逐步提升战略推理与语言沟通能力。实验结果表明，该方法在狼人杀游戏中每轮迭代均提升代理表现，超越现有代理，展现了其在自由语言决策中的巨大潜力。

> Large language model (LLM)-based agents have recently shown impressive progress in a variety of domains, including open-ended conversation and multi-step decision-making. However, applying these agents to social deduction games such as Werewolf, which requires both strategic decision-making and free-form language interaction, remains non-trivial. Traditional methods based on Counterfactual Regret Minimization (CFR) or reinforcement learning (RL) typically depend on a predefined action space, making them unsuitable for language games with unconstrained text action space. Meanwhile, pure LLM-based agents often suffer from intrinsic biases and require prohibitively large datasets for fine-tuning. We propose Latent Space Policy Optimization (LSPO), an iterative framework that addresses these challenges by first mapping free-form text to a discrete latent space, where methods like CFR and RL can learn strategic policy more effectively. We then translate the learned policy back into natural language dialogues, which are used to fine-tune an LLM via Direct Preference Optimization (DPO). By iteratively alternating between these stages, our LSPO agent progressively enhances both strategic reasoning and language communication. Experiment results on the Werewolf game show that our method improves the agent's performance in each iteration and outperforms existing Werewolf agents, underscoring its promise for free-form language decision-making.

[Arxiv](https://arxiv.org/abs/2502.04686)