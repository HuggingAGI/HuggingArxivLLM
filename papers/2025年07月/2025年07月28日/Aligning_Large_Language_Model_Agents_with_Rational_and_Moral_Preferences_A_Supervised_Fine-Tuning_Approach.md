# 对齐大型语言模型代理的理性与道德偏好：一种监督微调方法

发布时间：2025年07月28日

`Agent` `自动驾驶`

> Aligning Large Language Model Agents with Rational and Moral Preferences: A Supervised Fine-Tuning Approach

# 摘要

> 理解大型语言模型（LLM）代理在战略互动中的行为至关重要，因为这些系统越来越多地自主参与具有经济和道德影响的决策。我们通过经典的经济博弈评估LLM偏好，发现其行为与人类行为存在显著差异。例如，GPT-4o等模型表现出过度合作和有限的激励敏感性，而推理模型如o3-mini则更倾向于符合收益最大化的策略。我们提出了一种基于经济推理合成数据集的监督微调管道，旨在使LLM代理与经济偏好对齐，并重点关注两种简化的偏好结构：第一种是效用仅取决于个人收益（ homo economicus），第二种是效用还取决于康德普遍化原则（ homo moralis）。我们发现，基于小数据集的微调能够将LLM代理行为转向相应的经济代理。我们进一步评估了微调后的代理在两个应用场景中的行为：涉及自动驾驶汽车的道德困境和竞争市场中的算法定价。这些例子展示了通过结构化偏好结构实现的不同规范性目标如何影响市场和道德结果。这项研究贡献了一种可复制、成本高效且经济基础扎实的管道，通过道德经济原则对齐AI偏好。

> Understanding how large language model (LLM) agents behave in strategic interactions is essential as these systems increasingly participate autonomously in economically and morally consequential decisions. We evaluate LLM preferences using canonical economic games, finding substantial deviations from human behavior. Models like GPT-4o show excessive cooperation and limited incentive sensitivity, while reasoning models, such as o3-mini, align more consistently with payoff-maximizing strategies. We propose a supervised fine-tuning pipeline that uses synthetic datasets derived from economic reasoning to align LLM agents with economic preferences, focusing on two stylized preference structures. In the first, utility depends only on individual payoffs (homo economicus), while utility also depends on a notion of Kantian universalizability in the second preference structure (homo moralis). We find that fine-tuning based on small datasets shifts LLM agent behavior toward the corresponding economic agent. We further assess the fine-tuned agents' behavior in two applications: Moral dilemmas involving autonomous vehicles and algorithmic pricing in competitive markets. These examples illustrate how different normative objectives embedded via realizations from structured preference structures can influence market and moral outcomes. This work contributes a replicable, cost-efficient, and economically grounded pipeline to align AI preferences using moral-economic principles.

[Arxiv](https://arxiv.org/abs/2507.20796)