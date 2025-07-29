# 迈向人工超级智能的自发展智能体研究综述

发布时间：2025年07月28日

`Agent`

> A Survey of Self-Evolving Agents: On Path to Artificial Super Intelligence

# 摘要

> 大型语言模型（LLMs）展现了强大的能力，但本质上仍然静态，无法根据新任务、知识领域或动态交互场景调整其内部参数。随着LLMs越来越多地部署在开放性和交互性环境中，这种静态特性已成为关键瓶颈。我们需要能够实时自适应推理、行动和演进的智能体。这一范式转变——从扩展静态模型到开发自进化智能体——引发了对支持从数据、交互和经验中持续学习与适应的架构和方法的日益浓厚的兴趣。

本文综述了自进化智能体的首个系统性、全面性研究，围绕三个基础维度展开——进化什么、何时进化、如何进化。我们考察了智能体组件（如模型、记忆、工具、架构）的进化机制，按阶段（如单任务时间内、跨任务时间）对适应方法进行了分类，并分析了引导进化适应的算法和架构设计（如标量奖励、文本反馈、单智能体和多智能体系统）。此外，我们分析了专门针对自进化智能体的评估指标和基准，突出了在编码、教育和医疗等领域的应用，并指出了安全、可扩展性和协同进化机制等关键挑战与研究方向。

通过为理解和设计自进化智能体提供结构化框架，本综述为推进自适应智能体系统的研究和实际部署奠定了路线图。最终，这将为实现人工超级智能（ASI）指明方向，其中智能体能够自主进化，在广泛的任务中达到或超越人类水平的智能。

> Large Language Models (LLMs) have demonstrated strong capabilities but remain fundamentally static, unable to adapt their internal parameters to novel tasks, evolving knowledge domains, or dynamic interaction contexts. As LLMs are increasingly deployed in open-ended, interactive environments, this static nature has become a critical bottleneck, necessitating agents that can adaptively reason, act, and evolve in real time. This paradigm shift -- from scaling static models to developing self-evolving agents -- has sparked growing interest in architectures and methods enabling continual learning and adaptation from data, interactions, and experiences. This survey provides the first systematic and comprehensive review of self-evolving agents, organized around three foundational dimensions -- what to evolve, when to evolve, and how to evolve. We examine evolutionary mechanisms across agent components (e.g., models, memory, tools, architecture), categorize adaptation methods by stages (e.g., intra-test-time, inter-test-time), and analyze the algorithmic and architectural designs that guide evolutionary adaptation (e.g., scalar rewards, textual feedback, single-agent and multi-agent systems). Additionally, we analyze evaluation metrics and benchmarks tailored for self-evolving agents, highlight applications in domains such as coding, education, and healthcare, and identify critical challenges and research directions in safety, scalability, and co-evolutionary dynamics. By providing a structured framework for understanding and designing self-evolving agents, this survey establishes a roadmap for advancing adaptive agentic systems in both research and real-world deployments, ultimately shedding lights to pave the way for the realization of Artificial Super Intelligence (ASI), where agents evolve autonomously, performing at or beyond human-level intelligence across a wide array of tasks.

[Arxiv](https://arxiv.org/abs/2507.21046)