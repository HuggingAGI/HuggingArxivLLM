# Aime: 迈向完全自主的多智能体框架探索之路

发布时间：2025年07月16日

`Agent` `通用推理` `软件工程`

> Aime: Towards Fully-Autonomous Multi-Agent Framework

# 摘要

> 大型语言模型（LLMs）驱动的多智能体系统（MAS）正在成为解决复杂多面问题的有力范式。然而，这些系统的潜力常常受到普遍存在的“规划与执行”框架的限制，该框架存在关键缺陷： rigid plan execution, static agent capabilities, 和 inefficient communication. 这些弱点阻碍了它们在动态环境中的适应性和鲁棒性。本文介绍了Aime，这是一个旨在通过动态、反应式规划和执行来克服这些挑战的新型多智能体框架。Aime用流畅且自适应的架构取代了传统的静态工作流。其核心创新包括：(1) 动态规划器，它会根据实时执行反馈不断优化整体策略；(2) Actor Factory，它实现了动态Actor实例化，按需组装配备专门工具和知识的专用智能体；(3) 集中式进度管理模块，作为系统范围内连贯状态感知的单一真实信息源。我们在涵盖通用推理（GAIA）、软件工程（SWE-bench Verified）和实时网页导航（WebVoyager）的多样化基准测试套件上对Aime进行了实证评估。结果表明，Aime在各自领域内甚至超越了高度专业化的最先进智能体。其卓越的适应性和任务成功率确立了Aime作为多智能体协作更强大、更有效的基础。

> Multi-Agent Systems (MAS) powered by Large Language Models (LLMs) are emerging as a powerful paradigm for solving complex, multifaceted problems. However, the potential of these systems is often constrained by the prevalent plan-and-execute framework, which suffers from critical limitations: rigid plan execution, static agent capabilities, and inefficient communication. These weaknesses hinder their adaptability and robustness in dynamic environments. This paper introduces Aime, a novel multi-agent framework designed to overcome these challenges through dynamic, reactive planning and execution. Aime replaces the conventional static workflow with a fluid and adaptive architecture. Its core innovations include: (1) a Dynamic Planner that continuously refines the overall strategy based on real-time execution feedback; (2) an Actor Factory that implements Dynamic Actor instantiation, assembling specialized agents on-demand with tailored tools and knowledge; and (3) a centralized Progress Management Module that serves as a single source of truth for coherent, system-wide state awareness. We empirically evaluated Aime on a diverse suite of benchmarks spanning general reasoning (GAIA), software engineering (SWE-bench Verified), and live web navigation (WebVoyager). The results demonstrate that Aime consistently outperforms even highly specialized state-of-the-art agents in their respective domains. Its superior adaptability and task success rate establish Aime as a more resilient and effective foundation for multi-agent collaboration.

[Arxiv](https://arxiv.org/abs/2507.11988)