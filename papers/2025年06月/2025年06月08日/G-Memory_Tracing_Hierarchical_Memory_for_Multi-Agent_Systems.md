# G-Memory：分层记忆追踪在多智能体系统中的应用

发布时间：2025年06月08日

`Agent

理由：论文讨论了多智能体系统（MAS）中的记忆机制，并提出了一种新的记忆系统G-Memory，旨在改进智能体之间的协作和记忆管理。这主要涉及智能体系统的设计与优化，因此归类为Agent。` `多智能体系统` `知识工程`

> G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems

# 摘要

> 大型语言模型 (LLM) 驱动的多智能体系统 (MAS) 展现出了远超单一 LLM 智能体的认知与执行能力，然而其自我进化能力却因欠发达的记忆架构而受到限制。经过深入观察，我们发现现有 MAS 记忆机制存在两大问题：(1) 极度过简化，完全忽视了智能体间协作轨迹的复杂性；(2) 缺乏跨试验和针对特定智能体的定制化能力，这与单智能体开发的表达记忆形成了鲜明对比。为填补这一空白，我们引入了 G-Memory，一个受组织记忆理论启发的分层式 MAS 代理记忆系统。该系统通过三层图结构管理 MAS 的长程交互：见解图、查询图和交互图。当接收到新的用户查询时，G-Memory 会进行双向记忆遍历，检索既能跨试验利用知识的「高层、可泛化见解」，又能紧凑编码先前协作经验的「精细、浓缩交互轨迹」。在任务执行过程中，整个层级架构通过吸收新的协作轨迹而不断进化，推动智能体团队的持续演进。我们在五个基准测试、三种 LLM 基础模型以及三种主流 MAS 框架上进行了广泛实验，结果显示 G-Memory 将具身行动的成功率和知识问答的准确性分别提升了高达 20.89% 和 10.12%，且无需对原框架进行任何修改。我们的代码已开源，可在 https://github.com/bingreeky/GMemory 获取。


> Large language model (LLM)-powered multi-agent systems (MAS) have demonstrated cognitive and execution capabilities that far exceed those of single LLM agents, yet their capacity for self-evolution remains hampered by underdeveloped memory architectures. Upon close inspection, we are alarmed to discover that prevailing MAS memory mechanisms (1) are overly simplistic, completely disregarding the nuanced inter-agent collaboration trajectories, and (2) lack cross-trial and agent-specific customization, in stark contrast to the expressive memory developed for single agents. To bridge this gap, we introduce G-Memory, a hierarchical, agentic memory system for MAS inspired by organizational memory theory, which manages the lengthy MAS interaction via a three-tier graph hierarchy: insight, query, and interaction graphs. Upon receiving a new user query, G-Memory performs bi-directional memory traversal to retrieve both $\textit{high-level, generalizable insights}$ that enable the system to leverage cross-trial knowledge, and $\textit{fine-grained, condensed interaction trajectories}$ that compactly encode prior collaboration experiences. Upon task execution, the entire hierarchy evolves by assimilating new collaborative trajectories, nurturing the progressive evolution of agent teams. Extensive experiments across five benchmarks, three LLM backbones, and three popular MAS frameworks demonstrate that G-Memory improves success rates in embodied action and accuracy in knowledge QA by up to $20.89\%$ and $10.12\%$, respectively, without any modifications to the original frameworks. Our codes are available at https://github.com/bingreeky/GMemory.

[Arxiv](https://arxiv.org/abs/2506.07398)