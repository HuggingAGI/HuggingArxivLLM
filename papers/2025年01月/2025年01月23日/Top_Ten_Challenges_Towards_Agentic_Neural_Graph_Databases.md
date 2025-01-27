# # 智能体神经图数据库的十大挑战

发布时间：2025年01月23日

`Agent

理由：这篇论文主要讨论了智能神经图数据库（Agentic NGDBs）的扩展功能，包括自主查询构建、神经查询执行和持续学习等核心能力。这些功能强调了系统的自主性和适应性，符合“Agent”分类中关于智能体（Agent）的定义，即能够自主执行任务、学习和适应的系统。因此，这篇论文应被分类为“Agent”。` `图数据库` `数据管理`

> Top Ten Challenges Towards Agentic Neural Graph Databases

# 摘要

> # 摘要
Neo4j 和 TigerGraph 等图数据库（GDBs）擅长处理互连数据，但在高级推理能力上有所欠缺。神经图数据库（NGDBs）通过引入图神经网络（GNNs）来弥补这一不足，能够对不完整或噪声数据进行预测分析和推理。然而，NGDBs 依赖预定义查询，缺乏自主性和适应性。本文提出的智能神经图数据库（Agentic NGDBs）扩展了 NGDBs 的功能，具备三大核心能力：自主查询构建、神经查询执行和持续学习。我们总结了实现 Agentic NGDBs 的十大挑战，包括语义单元表示、溯因推理、可扩展查询执行以及与大型语言模型（LLMs）等基础模型的集成。通过攻克这些挑战，Agentic NGDBs 将为现代数据驱动应用打造智能、自我优化的系统，推动适应性和自主数据管理解决方案的发展。

> Graph databases (GDBs) like Neo4j and TigerGraph excel at handling interconnected data but lack advanced inference capabilities. Neural Graph Databases (NGDBs) address this by integrating Graph Neural Networks (GNNs) for predictive analysis and reasoning over incomplete or noisy data. However, NGDBs rely on predefined queries and lack autonomy and adaptability. This paper introduces Agentic Neural Graph Databases (Agentic NGDBs), which extend NGDBs with three core functionalities: autonomous query construction, neural query execution, and continuous learning. We identify ten key challenges in realizing Agentic NGDBs: semantic unit representation, abductive reasoning, scalable query execution, and integration with foundation models like large language models (LLMs). By addressing these challenges, Agentic NGDBs can enable intelligent, self-improving systems for modern data-driven applications, paving the way for adaptable and autonomous data management solutions.

[Arxiv](https://arxiv.org/abs/2501.14224)