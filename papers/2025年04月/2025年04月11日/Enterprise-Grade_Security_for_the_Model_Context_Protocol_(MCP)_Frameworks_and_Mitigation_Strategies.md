# # 模型上下文协议（MCP）的企业级安全：框架与缓解策略
模型上下文协议（MCP）的企业级安全：框架与缓解策略

发布时间：2025年04月11日

`LLM应用` `AI安全` `企业安全`

> Enterprise-Grade Security for the Model Context Protocol (MCP): Frameworks and Mitigation Strategies

# 摘要

> Anthropic 提出的模型上下文协议（MCP）为 AI 系统提供了一个标准化的框架，使其能够实时与外部数据源和工具进行交互。尽管 MCP 在 AI 集成和能力扩展方面具有显著优势，但它也带来了新型安全挑战，需要进行严格分析和缓解。本文基于对 MCP 架构的基础研究和初步安全评估，提供了企业级的缓解框架和详细的技术实现策略。通过系统化的威胁建模和对 MCP 实施的分析，以及对潜在攻击向量（包括工具中毒等复杂威胁）的分析，我们为 MCP 实施者和采用者提供了可操作的安全模式。这项研究的主要贡献在于将理论上的安全问题转化为一个实用的、可实施的框架，并提供可操作的控制措施，从而为企业安全地采用和管理集成 AI 系统提供了重要指导。

> The Model Context Protocol (MCP), introduced by Anthropic, provides a standardized framework for artificial intelligence (AI) systems to interact with external data sources and tools in real-time. While MCP offers significant advantages for AI integration and capability extension, it introduces novel security challenges that demand rigorous analysis and mitigation. This paper builds upon foundational research into MCP architecture and preliminary security assessments to deliver enterprise-grade mitigation frameworks and detailed technical implementation strategies. Through systematic threat modeling and analysis of MCP implementations and analysis of potential attack vectors, including sophisticated threats like tool poisoning, we present actionable security patterns tailored for MCP implementers and adopters. The primary contribution of this research lies in translating theoretical security concerns into a practical, implementable framework with actionable controls, thereby providing essential guidance for the secure enterprise adoption and governance of integrated AI systems.

[Arxiv](https://arxiv.org/abs/2504.08623)