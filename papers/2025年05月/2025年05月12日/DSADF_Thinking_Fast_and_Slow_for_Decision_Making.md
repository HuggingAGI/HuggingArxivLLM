# DSADF：快与慢的思考，决策之道

发布时间：2025年05月12日

`Agent

摘要中提到的论文主要研究如何通过结合强化学习（Reinforcement Learning, RL）和视觉语言模型（Vision Language Models, VLMs）来增强智能体的泛化能力和决策效率。论文提出了一个双系统自适应决策框架（DSADF），旨在整合快速直觉决策和深度分析推理，以提升智能体在复杂环境中的决策能力。这一研究的核心是智能体的改进和优化，因此归类为Agent。` `人工智能` `视频游戏`

> DSADF: Thinking Fast and Slow for Decision Making

# 摘要

> 强化学习（Reinforcement Learning, RL）智能体在规则明确的环境中表现出色，但受限于试错学习机制，在动态环境中的策略推广能力不足。近期研究尝试通过大语言模型（Large Language Models, LLMs）或视觉语言模型（Vision Language Models, VLMs）来增强RL智能体的泛化能力，主要通过策略优化指导或注入先验知识。然而，现有方法往往忽视了RL智能体与基础模型之间的协同优化，导致陌生环境下的决策合理性欠佳，并存在效率瓶颈。如何充分利用基础模型的推理能力和RL智能体的快速响应能力，构建双系统间高效互动机制，仍是亟待解决的科学问题。

受Kahneman的快思考（System 1）与慢思考（System 2）理论启发，我们证明了直觉与深度推理的平衡能在复杂环境中实现敏捷决策。本研究提出了一种双系统自适应决策框架（Dual-System Adaptive Decision Framework, DSADF），由两个互补模块组成：System 1包含一个快速直觉决策的RL智能体和记忆空间，而System 2则由VLM驱动，专注于深度分析推理。DSADF通过整合两个系统的优势，实现了高效且自适应的决策过程。在视频游戏环境Crafter和Housekeep中的实证研究表明，我们提出的方法显著提升了在已知和未知任务中的决策能力，验证了其有效性。

> Although Reinforcement Learning (RL) agents are effective in well-defined environments, they often struggle to generalize their learned policies to dynamic settings due to their reliance on trial-and-error interactions. Recent work has explored applying Large Language Models (LLMs) or Vision Language Models (VLMs) to boost the generalization of RL agents through policy optimization guidance or prior knowledge. However, these approaches often lack seamless coordination between the RL agent and the foundation model, leading to unreasonable decision-making in unfamiliar environments and efficiency bottlenecks. Making full use of the inferential capabilities of foundation models and the rapid response capabilities of RL agents and enhancing the interaction between the two to form a dual system is still a lingering scientific question. To address this problem, we draw inspiration from Kahneman's theory of fast thinking (System 1) and slow thinking (System 2), demonstrating that balancing intuition and deep reasoning can achieve nimble decision-making in a complex world. In this study, we propose a Dual-System Adaptive Decision Framework (DSADF), integrating two complementary modules: System 1, comprising an RL agent and a memory space for fast and intuitive decision making, and System 2, driven by a VLM for deep and analytical reasoning. DSADF facilitates efficient and adaptive decision-making by combining the strengths of both systems. The empirical study in the video game environment: Crafter and Housekeep demonstrates the effectiveness of our proposed method, showing significant improvements in decision abilities for both unseen and known tasks.

[Arxiv](https://arxiv.org/abs/2505.08189)