# 本文综述了智能体互操作性领域的四项核心协议，包括模型上下文协议（MCP）、智能体通信协议（ACP）、智能体间协议（A2A）以及智能体网络协议（ANP）。

发布时间：2025年05月04日

`Agent` `自主代理` `通信协议`

> A survey of agent interoperability protocols: Model Context Protocol (MCP), Agent Communication Protocol (ACP), Agent-to-Agent Protocol (A2A), and Agent Network Protocol (ANP)

# 摘要

> 大型语言模型 (LLM) 驱动的自主代理需要健壮且标准化的协议来集成工具、共享上下文数据，并在异构系统之间协调任务。临时集成在扩展性、安全性以及跨领域通用性方面面临挑战。本文综述了四种新兴的代理通信协议：模型上下文协议 (MCP)、代理通信协议 (ACP)、代理对代理协议 (A2A) 以及代理网络协议 (ANP)，每种协议针对不同的部署环境解决了互操作性问题。

MCP 提供了一个基于 JSON-RPC 的客户端-服务器接口，用于安全工具调用和类型化数据交换。ACP 通过多部分消息和异步流式传输引入了原生 REST 消息传递，支持多模态代理响应。A2A 通过基于能力的代理卡片实现了点对点任务外包，助力企业级工作流的实现。ANP 利用去中心化标识符 (DIDs) 和 JSON-LD 图支持开放网络中的代理发现和安全协作。

这些协议在交互模式、发现机制、通信模式以及安全模型等多个维度进行了比较。基于比较分析，本文提出了一条分阶段的采用路线图：从 MCP 开始实现工具访问，随后通过 ACP 支持多模态消息传递，利用 A2A 实现协作任务执行，并最终扩展至 ANP 以支持去中心化的代理市场。这项工作为设计安全、互操作且可扩展的 LLM 驱动代理生态系统提供了全面的基础。


> Large language model (LLM)-powered autonomous agents demand robust, standardized protocols to integrate tools, share contextual data, and coordinate tasks across heterogeneous systems. Ad-hoc integrations are difficult to scale, secure, and generalize across domains. This survey examines four emerging agent communication protocols: Model Context Protocol (MCP), Agent Communication Protocol (ACP), Agent-to-Agent Protocol (A2A), and Agent Network Protocol (ANP), each addressing interoperability in distinct deployment contexts. MCP provides a JSON-RPC client-server interface for secure tool invocation and typed data exchange. ACP introduces REST-native messaging via multi-part messages and asynchronous streaming to support multimodal agent responses. A2A enables peer-to-peer task outsourcing through capability-based Agent Cards, facilitating enterprise-scale workflows. ANP supports open-network agent discovery and secure collaboration using decentralized identifiers (DIDs) and JSON-LD graphs. The protocols are compared across multiple dimensions, including interaction modes, discovery mechanisms, communication patterns, and security models. Based on the comparative analysis, a phased adoption roadmap is proposed: beginning with MCP for tool access, followed by ACP for multimodal messaging, A2A for collaborative task execution, and extending to ANP for decentralized agent marketplaces. This work provides a comprehensive foundation for designing secure, interoperable, and scalable ecosystems of LLM-powered agents.

[Arxiv](https://arxiv.org/abs/2505.02279)