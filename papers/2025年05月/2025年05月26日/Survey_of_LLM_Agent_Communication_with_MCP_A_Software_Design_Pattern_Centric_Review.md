# 大型语言模型 (LLM) 代理通信综述：基于MCP的软件设计模式为中心的审查

发布时间：2025年05月26日

`Agent` `投资银行`

> Survey of LLM Agent Communication with MCP: A Software Design Pattern Centric Review

# 摘要

> 本研究深入探讨了经典软件设计模式在提升大型语言模型 (LLM) 驱动的智能体AI系统通信可靠性和可扩展性方面的作用，尤其聚焦于模型上下文协议 (MCP)。研究分析了基于LLM的智能体架构从孤立运行到复杂多智能体协作的演变过程，并针对这一过程中出现的关键通信挑战进行了深入探讨。本研究重新审视了中介者、观察者、发布-订阅和代理等成熟设计模式，分析了它们在MCP兼容框架下构建智能体交互结构的相关性。为了更清晰地阐述这些机制，文章提供了概念图示和形式化模型，详细描绘了通信路径并优化了数据流。此外，研究还探讨了适用于不同智能体自主程度和系统复杂度的架构变体。通过实时金融处理和投资银行业的实际应用案例，文章展示了这些模式和MCP如何满足特定的运营需求。最后，文章总结了当前面临的开放挑战、潜在的安全风险以及推动健壮、互操作且可扩展的多智能体LLM生态系统发展的前景方向。

> This survey investigates how classical software design patterns can enhance the reliability and scalability of communication in Large Language Model (LLM)-driven agentic AI systems, focusing particularly on the Model Context Protocol (MCP). It examines the foundational architectures of LLM-based agents and their evolution from isolated operation to sophisticated, multi-agent collaboration, addressing key communication hurdles that arise in this transition. The study revisits well-established patterns, including Mediator, Observer, Publish-Subscribe, and Broker, and analyzes their relevance in structuring agent interactions within MCP-compliant frameworks. To clarify these dynamics, the article provides conceptual schematics and formal models that map out communication pathways and optimize data flow. It further explores architectural variations suited to different degrees of agent autonomy and system complexity. Real-world applications in domains such as real-time financial processing and investment banking are discussed, illustrating how these patterns and MCP can meet specific operational demands. The article concludes by outlining open challenges, potential security risks, and promising directions for advancing robust, interoperable, and scalable multi-agent LLM ecosystems.

[Arxiv](https://arxiv.org/abs/2506.05364)