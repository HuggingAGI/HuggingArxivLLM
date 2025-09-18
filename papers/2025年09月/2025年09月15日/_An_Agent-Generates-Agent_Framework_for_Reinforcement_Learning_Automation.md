# : 面向强化学习自动化的智能体生成智能体框架

发布时间：2025年09月15日

`Agent` `基础理论`

> : An Agent-Generates-Agent Framework for Reinforcement Learning Automation

# 摘要

> 传统强化学习智能体的开发往往需要深厚的专业知识和漫长的迭代，结果常常是失败率高且普及难度大。本文提出【数学公式】——一种创新的"智能体生成智能体"框架，它借助智能的LLM驱动生成，实现了强化学习智能体设计的全自动化。该系统无需人工介入，可自主将自然语言任务描述和环境代码转化为全面且高性能的强化学习解决方案。【数学公式】的核心是革命性的双智能体架构：生成器智能体作为自主AI设计师，负责分析任务并生成可执行的强化学习智能体；目标智能体则是最终自动生成的强化学习智能体。该框架将强化学习开发拆解为两个明确阶段——MDP建模与算法优化，以实现更精准、高效的智能体生成。依托模型上下文协议，【数学公式】构建了统一框架，能标准化不同环境与算法下智能体的创建过程，同时融入自适应训练管理和智能反馈分析以实现持续优化。在MuJoCo、MetaDrive、MPE、SMAC等众多基准测试中的大量实验证实，【数学公式】在所有任务上均持续优于人工设计方案，性能提升最高达55%，且平均增益显著。通过实现真正的端到端闭环自动化，这项研究开创了"智能体设计并优化其他智能体"的全新范式，为自动化AI系统带来了根本性突破。

> Reinforcement learning agent development traditionally requires extensive expertise and lengthy iterations, often resulting in high failure rates and limited accessibility. This paper introduces $Agent^2$, a novel agent-generates-agent framework that achieves fully automated RL agent design through intelligent LLM-driven generation. The system autonomously transforms natural language task descriptions and environment code into comprehensive, high-performance reinforcement learning solutions without human intervention. $Agent^2$ features a revolutionary dual-agent architecture. The Generator Agent serves as an autonomous AI designer that analyzes tasks and generates executable RL agents, while the Target Agent is the resulting automatically generated RL agent. The framework decomposes RL development into two distinct stages: MDP modeling and algorithmic optimization, enabling more targeted and effective agent generation. Built on the Model Context Protocol, $Agent^2$ provides a unified framework that standardizes intelligent agent creation across diverse environments and algorithms, while incorporating adaptive training management and intelligent feedback analysis for continuous improvement. Extensive experiments on a wide range of benchmarks, including MuJoCo, MetaDrive, MPE, and SMAC, demonstrate that $Agent^2$ consistently outperforms manually designed solutions across all tasks, achieving up to 55% performance improvement and substantial gains on average. By enabling truly end-to-end, closed-loop automation, this work establishes a new paradigm in which intelligent agents design and optimize other agents, marking a fundamental breakthrough for automated AI systems.

[Arxiv](https://arxiv.org/abs/2509.13368)