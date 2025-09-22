# 思维图驱动的奖励进化：一种面向强化学习的双层语言模型框架

发布时间：2025年09月19日

`强化学习` `工业与制造`

> Reward Evolution with Graph-of-Thoughts: A Bi-Level Language Model Framework for Reinforcement Learning

# 摘要

> 在强化学习（RL）中，设计有效的奖励函数一直是个棘手难题，往往需要大量人类专业知识和反复优化。近年来，研究开始借助大型语言模型（LLMs）实现奖励函数自动化设计，但这类方法存在幻觉问题、依赖人工反馈、难以处理复杂多步骤任务等局限。为此，我们提出了基于图思维的奖励进化框架（RE-GoT）——一种新颖的双层框架，它通过结构化图推理增强LLM能力，并集成视觉语言模型（VLMs）实现自动化轨迹评估。RE-GoT首先将任务分解为文本属性图，以实现全面分析和奖励函数生成，随后利用VLM的视觉反馈迭代优化奖励，全程无需人工介入。在10个RoboGen任务和4个ManiSkill2任务上的大量实验显示，RE-GoT性能持续优于现有基于LLM的基线方法：在RoboGen上，平均任务成功率提升32.25%，复杂多步骤任务的表现尤为突出；在ManiSkill2上，四个不同操作任务的平均成功率高达93.73%，不仅大幅超越此前基于LLM的方法，甚至优于专家设计的奖励函数。研究结果表明，将LLM、VLM与图思维推理相结合，为RL中奖励函数的自主进化提供了可扩展且高效的解决方案。

> Designing effective reward functions remains a major challenge in reinforcement learning (RL), often requiring considerable human expertise and iterative refinement. Recent advances leverage Large Language Models (LLMs) for automated reward design, but these approaches are limited by hallucinations, reliance on human feedback, and challenges with handling complex, multi-step tasks. In this work, we introduce Reward Evolution with Graph-of-Thoughts (RE-GoT), a novel bi-level framework that enhances LLMs with structured graph-based reasoning and integrates Visual Language Models (VLMs) for automated rollout evaluation. RE-GoT first decomposes tasks into text-attributed graphs, enabling comprehensive analysis and reward function generation, and then iteratively refines rewards using visual feedback from VLMs without human intervention. Extensive experiments on 10 RoboGen and 4 ManiSkill2 tasks demonstrate that RE-GoT consistently outperforms existing LLM-based baselines. On RoboGen, our method improves average task success rates by 32.25%, with notable gains on complex multi-step tasks. On ManiSkill2, RE-GoT achieves an average success rate of 93.73% across four diverse manipulation tasks, significantly surpassing prior LLM-based approaches and even exceeding expert-designed rewards. Our results indicate that combining LLMs and VLMs with graph-of-thoughts reasoning provides a scalable and effective solution for autonomous reward evolution in RL.

[Arxiv](https://arxiv.org/abs/2509.16136)