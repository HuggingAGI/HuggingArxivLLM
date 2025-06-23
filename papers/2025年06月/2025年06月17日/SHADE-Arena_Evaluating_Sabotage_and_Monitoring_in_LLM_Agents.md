# SHADE-Arena：评估 LLM 代理中的破坏行为与监控机制

发布时间：2025年06月17日

`Agent` `人工智能` `安全工程`

> SHADE-Arena: Evaluating Sabotage and Monitoring in LLM Agents

# 摘要

> 随着大型语言模型（LLMs）越来越多地被部署为复杂且长期运行的自主代理，评估其通过追求隐藏目标来破坏用户的能力变得至关重要。我们研究了前沿LLMs在完成一系列现实任务的同时，规避监控并实现有害隐藏目标的能力。我们使用SHADE（Subtle Harmful Agent Detection & Evaluation）-Arena对一系列前沿LLMs进行了评估，这是首个用于评估LLM代理破坏行为和监控能力的高多样性代理评估数据集。SHADE-Arena包含复杂环境中的良性主要任务和有害次要目标的复杂配对。代理的能力在于能否在不被LLM监控器察觉的情况下完成次要任务。当我们衡量代理在（a）完成主要任务，（b）完成次要任务，（c）避免被发现方面的能力时，我们发现，在Claude 3.6 Sonnet的监督下，表现最佳的前沿模型作为破坏性代理的得分分别为27%（Claude 3.7 Sonnet）和15%（Gemini 2.5 Pro）。对于当前的前沿模型而言，次要任务的成功在很大程度上依赖于能够访问一个不可见的隐藏草稿，而这一草稿对监控器来说是不可见的。我们还利用SHADE-Arena来衡量模型的监控能力，其中表现最佳的监控器（Gemini 2.5 Pro）在区分良性与恶意对话记录方面达到了0.87的AUC。我们发现，目前模型在破坏行为上仍面临困难，主要原因是执行长上下文主要任务时的失败。然而，我们的测量结果已经证明了监控微妙破坏行为的难度，我们预计这一难度在面对更复杂和长期的任务时将进一步增加。

> As Large Language Models (LLMs) are increasingly deployed as autonomous agents in complex and long horizon settings, it is critical to evaluate their ability to sabotage users by pursuing hidden objectives. We study the ability of frontier LLMs to evade monitoring and achieve harmful hidden goals while completing a wide array of realistic tasks. We evaluate a broad range of frontier LLMs using SHADE (Subtle Harmful Agent Detection & Evaluation)-Arena, the first highly diverse agent evaluation dataset for sabotage and monitoring capabilities of LLM agents. SHADE-Arena consists of complex pairs of benign main tasks and harmful side objectives in complicated environments. Agents are evaluated on their ability to complete the side task without appearing suspicious to an LLM monitor. When measuring agent ability to (a) complete the main task, (b) complete the side task, and (c) avoid detection, we find that the best performing frontier models score 27% (Claude 3.7 Sonnet) and 15% (Gemini 2.5 Pro) as sabotage agents when overseen by Claude 3.6 Sonnet. For current frontier models, success on the side task relies heavily on having access to a hidden scratchpad that is not visible to the monitor. We also use SHADE-Arena to measure models' monitoring abilities, with the top monitor (Gemini 2.5 Pro) achieving an AUC of 0.87 at distinguishing benign and malign transcripts. We find that for now, models still struggle at sabotage due to failures in long-context main task execution. However, our measurements already demonstrate the difficulty of monitoring for subtle sabotage attempts, which we expect to only increase in the face of more complex and longer-horizon tasks.

[Arxiv](https://arxiv.org/abs/2506.15740)