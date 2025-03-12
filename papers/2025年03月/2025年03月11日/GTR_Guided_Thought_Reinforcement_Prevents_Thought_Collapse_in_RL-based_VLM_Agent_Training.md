# GTR: 引导式思维强化预防强化学习视觉语言模型智能体训练中的思考坍塌现象

发布时间：2025年03月11日

`LLM应用` `视觉语言模型` `视觉推理`

> GTR: Guided Thought Reinforcement Prevents Thought Collapse in RL-based VLM Agent Training

# 摘要

> 基于可验证结果奖励的强化学习（RLVR）在大型语言模型（LLMs）中成功实现了链式思维推理（CoT）的扩展。然而，其在视觉语言模型（VLM）中进行视觉环境目标导向推理的效果仍有待验证。本研究通过复杂卡牌游戏（如24点）和ALFWorld中的具身任务实验发现：仅基于行动结果的奖励机制会导致VLM中的“思维坍塌”现象，表现为推理多样性丧失、与状态无关且不完整，最终引发无效行动。为解决这一问题，我们提出了一种过程引导的自动化校正器，并构建了简单可扩展的GTR（引导式思维强化）框架，无需密集人工标注即可同时训练推理与行动。实验表明，GTR显著提升了LLaVA-7b模型在视觉环境中的表现与泛化能力，使其任务成功率相较于现有最优模型提升了3-5倍，且模型规模更小。

> Reinforcement learning with verifiable outcome rewards (RLVR) has effectively scaled up chain-of-thought (CoT) reasoning in large language models (LLMs). Yet, its efficacy in training vision-language model (VLM) agents for goal-directed action reasoning in visual environments is less established. This work investigates this problem through extensive experiments on complex card games, such as 24 points, and embodied tasks from ALFWorld. We find that when rewards are based solely on action outcomes, RL fails to incentivize CoT reasoning in VLMs, instead leading to a phenomenon we termed thought collapse, characterized by a rapid loss of diversity in the agent's thoughts, state-irrelevant and incomplete reasoning, and subsequent invalid actions, resulting in negative rewards. To counteract thought collapse, we highlight the necessity of process guidance and propose an automated corrector that evaluates and refines the agent's reasoning at each RL step. This simple and scalable GTR (Guided Thought Reinforcement) framework trains reasoning and action simultaneously without the need for dense, per-step human labeling. Our experiments demonstrate that GTR significantly enhances the performance and generalization of the LLaVA-7b model across various visual environments, achieving 3-5 times higher task success rates compared to SoTA models with notably smaller model sizes.

[Arxiv](https://arxiv.org/abs/2503.08525)