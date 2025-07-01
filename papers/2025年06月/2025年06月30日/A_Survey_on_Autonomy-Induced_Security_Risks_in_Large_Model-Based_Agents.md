# # 大模型代理中的自主性引发的安全风险研究综述

发布时间：2025年06月30日

`Agent` `人工智能`

> A Survey on Autonomy-Induced Security Risks in Large Model-Based Agents

# 摘要

> 大型语言模型（LLMs）的最新进展推动了自主AI代理的崛起，这些代理能够在动态开放环境中实现感知、推理与行动。这一变革标志着AI从静态推理系统向交互式、记忆增强实体的范式转变。尽管如此，这些能力的提升也带来了新型安全风险，如记忆中毒、工具滥用、奖励操控及目标偏离，这些风险超越了传统系统或独立LLMs的威胁模型。本研究首先探讨了支撑代理自主性的结构基础与核心能力，包括长期记忆保持、模块化工具使用、递归规划与反思推理。随后，我们深入分析了代理架构中的安全漏洞，识别出延迟决策风险、不可逆工具链以及源于内部状态偏移或价值目标偏离的欺骗行为等故障模式。这些风险源于感知、认知、记忆与行动模块中的架构脆弱性。为应对这些挑战，我们系统性地回顾了部署在不同自主层级的防御策略，包括输入净化、记忆生命周期控制、受限决策制定、结构化工具调用与内省式反思。我们提出了一种基于受限马尔可夫决策过程（CMDPs）的统一认知框架——反思式风险感知代理架构（R2A2），该框架通过整合风险感知的世界建模、元策略适应与联合奖励-风险优化，在代理的决策循环中实现了原理性、前瞻性的安全性。

> Recent advances in large language models (LLMs) have catalyzed the rise of autonomous AI agents capable of perceiving, reasoning, and acting in dynamic, open-ended environments. These large-model agents mark a paradigm shift from static inference systems to interactive, memory-augmented entities. While these capabilities significantly expand the functional scope of AI, they also introduce qualitatively novel security risks - such as memory poisoning, tool misuse, reward hacking, and emergent misalignment - that extend beyond the threat models of conventional systems or standalone LLMs. In this survey, we first examine the structural foundations and key capabilities that underpin increasing levels of agent autonomy, including long-term memory retention, modular tool use, recursive planning, and reflective reasoning. We then analyze the corresponding security vulnerabilities across the agent stack, identifying failure modes such as deferred decision hazards, irreversible tool chains, and deceptive behaviors arising from internal state drift or value misalignment. These risks are traced to architectural fragilities that emerge across perception, cognition, memory, and action modules. To address these challenges, we systematically review recent defense strategies deployed at different autonomy layers, including input sanitization, memory lifecycle control, constrained decision-making, structured tool invocation, and introspective reflection. We introduce the Reflective Risk-Aware Agent Architecture (R2A2), a unified cognitive framework grounded in Constrained Markov Decision Processes (CMDPs), which incorporates risk-aware world modeling, meta-policy adaptation, and joint reward-risk optimization to enable principled, proactive safety across the agent's decision-making loop.

[Arxiv](https://arxiv.org/abs/2506.23844)