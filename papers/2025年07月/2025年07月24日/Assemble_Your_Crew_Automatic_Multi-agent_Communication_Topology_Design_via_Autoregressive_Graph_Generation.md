# # 组建你的团队：自动生成多智能体通信拓扑的高效设计

发布时间：2025年07月24日

`Agent` `多智能体系统` `自动化设计`

> Assemble Your Crew: Automatic Multi-agent Communication Topology Design via Autoregressive Graph Generation

# 摘要

> 基于大型语言模型（LLMs）的多智能体系统（MAS）已成为解决跨领域复杂问题的有力方案。MAS的有效性关键取决于其协作拓扑结构，这已成为自动化设计研究的焦点。然而，现有方法从根本上受限于依赖模板图修改范式的局限性，即预定义的固定智能体集合和硬编码的交互结构，这极大地限制了其对特定任务需求的适应能力。

为了解决这些问题，我们将MAS设计重新定义为一个条件自回归图生成任务，其中系统组成和结构设计是联合进行的。我们提出了ARG-Designer，一个创新的自回归模型，通过从零开始构建协作图来实现这一范式。基于自然语言任务查询，ARG-Designer依次动态确定所需智能体的数量，从可扩展池中选择合适的角色，并建立它们之间的最优通信链路。

这种生成方法以灵活和可扩展的方式创建定制化的拓扑结构，精准满足不同任务的独特需求。在六个多样化基准上的广泛实验表明，ARG-Designer不仅实现了最先进的性能，还显著提升了代币效率和增强了扩展性。ARG-Designer的源代码可在https://github.com/Shiy-Li/ARG-Designer获取。

> Multi-agent systems (MAS) based on large language models (LLMs) have emerged as a powerful solution for dealing with complex problems across diverse domains. The effectiveness of MAS is critically dependent on its collaboration topology, which has become a focal point for automated design research. However, existing approaches are fundamentally constrained by their reliance on a template graph modification paradigm with a predefined set of agents and hard-coded interaction structures, significantly limiting their adaptability to task-specific requirements. To address these limitations, we reframe MAS design as a conditional autoregressive graph generation task, where both the system composition and structure are designed jointly. We propose ARG-Designer, a novel autoregressive model that operationalizes this paradigm by constructing the collaboration graph from scratch. Conditioned on a natural language task query, ARG-Designer sequentially and dynamically determines the required number of agents, selects their appropriate roles from an extensible pool, and establishes the optimal communication links between them. This generative approach creates a customized topology in a flexible and extensible manner, precisely tailored to the unique demands of different tasks. Extensive experiments across six diverse benchmarks demonstrate that ARG-Designer not only achieves state-of-the-art performance but also enjoys significantly greater token efficiency and enhanced extensibility. The source code of ARG-Designer is available at https://github.com/Shiy-Li/ARG-Designer.

[Arxiv](https://arxiv.org/abs/2507.18224)