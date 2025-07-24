# # 并行与适应的结合：多智能体LLM系统中的可扩展文档理解

发布时间：2025年07月22日

`Agent

理由：这篇论文主要探讨了多智能体系统中协作任务的完成，提出了新的协调框架，重点在于智能体之间的动态任务分配和反馈机制，属于智能体（Agent）领域的研究。` `多智能体系统` `协作系统`

> Parallelism Meets Adaptiveness: Scalable Documents Understanding in Multi-Agent LLM Systems

# 摘要

> 大型语言模型（LLM）代理在协作任务的完成上展现出越来越大的潜力。然而，现有的多代理框架通常依赖于静态工作流、固定角色以及有限的跨代理通信，这在开放性和高复杂度领域中限制了它们的有效性。本文提出了一种协调框架，通过三个核心机制实现适应性：动态任务分配、双向反馈和平行评估。该框架使代理能够根据置信度和工作负载重新分配任务，通过交换结构化的反馈意见迭代优化输出结果，并在高模糊性子任务中进行关键性的竞争，由评估器驱动选择最合适的结果。我们通过模块化架构实现这些原则，并在事实覆盖、连贯性和效率方面显著优于静态和部分自适应的基线模型。我们的研究结果突显了在多代理LLM系统中融入适应性和结构化竞争所带来的显著优势。

> Large language model (LLM) agents have shown increasing promise for collaborative task completion. However, existing multi-agent frameworks often rely on static workflows, fixed roles, and limited inter-agent communication, reducing their effectiveness in open-ended, high-complexity domains. This paper proposes a coordination framework that enables adaptiveness through three core mechanisms: dynamic task routing, bidirectional feedback, and parallel agent evaluation. The framework allows agents to reallocate tasks based on confidence and workload, exchange structured critiques to iteratively improve outputs, and crucially compete on high-ambiguity subtasks with evaluator-driven selection of the most suitable result. We instantiate these principles in a modular architecture and demonstrate substantial improvements in factual coverage, coherence, and efficiency over static and partially adaptive baselines. Our findings highlight the benefits of incorporating both adaptiveness and structured competition in multi-agent LLM systems.

[Arxiv](https://arxiv.org/abs/2507.17061)