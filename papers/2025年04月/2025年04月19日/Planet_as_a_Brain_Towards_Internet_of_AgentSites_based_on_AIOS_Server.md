# 行星如大脑：迈向基于AIOS服务器的智能体站点互联网

发布时间：2025年04月19日

`Agent` `智能体互联网` `分布式系统`

> Planet as a Brain: Towards Internet of AgentSites based on AIOS Server

# 摘要

> # 摘要
互联网正经历一场从“网站互联网”到“智能体站点互联网”的历史性变革。传统网站曾是信息托管和传播的基础，如今，智能体站点成为互联网的核心，每个智能体站点都承载着一个或多个AI智能体，它们接收任务、处理问题并提供可执行的解决方案。这一转变标志着数字格局的重大转变，代表着下一代在线生态系统。

在本文中，我们介绍AIOS Server，一个用于托管智能体并实现全球范围内去中心化智能体协作的运行时框架。AIOS Server通过Model Context Protocol (MCP) 和 JSON-RPC 提供通信协议，支持智能体与智能体之间或人与智能体之间的交互。每个AIOS节点作为一个服务器来托管和执行智能体，同时支持点对点协调，无需依赖集中式编排。基于AIOS Server，我们推出了全球首个实际部署的智能体互联网（AIOS-IoA），包括用于智能体注册和发现的AgentHub，以及用于交互式通信的AgentChat，访问地址为https://planet.aios.foundation。基于分布式哈希表（DHT）和流言协议的智能体发现机制，成为智能体互联网的搜索引擎。这项工作为构建智能体互联网提供了实用基础——一个新的范式，其中自主智能体成为网络中的核心成员。实现代码可在https://github.com/agiresearch/AIOS.Server获取，并将集成到AIOS主分支https://github.com/agiresearch/AIOS中。


> The internet is undergoing a historical transformation from the "Internet of Websites" to the "Internet of AgentSites." While traditional Websites served as the foundation for information hosting and dissemination, a new frontier is emerging where AgentSites serve as the hubs of the internet, where each AgentSite hosts one or more AI agents that receive tasks, address them, and deliver actionable solutions, marking a significant shift in the digital landscape and representing the next generation of online ecosystems. Under this vision, AIOS, the AI Agent Operating System, serves as the server for the development, deployment and execution of AI agents, which is a fundamental infrastructure for the Internet of Agentsites.
  In this paper, we introduce AIOS Server, a runtime framework to host agents and enable global-scale collaboration among decentralized agents. AIOS Server provides a communication protocol leveraging the Model Context Protocol (MCP) and JSON-RPC to enable agent-agent or human-agent interactions. Each AIOS node operates as a server to host and execute agents, while supporting peer-to-peer coordination without reliance on centralized orchestration. Based on AIOS Server, we further present the world's first practically deployed Internet of Agentsites (AIOS-IoA), including AgentHub for agent registration and discovery and AgentChat for interactive communication, at https://planet.aios.foundation. The agent discovery mechanism based on Distributed Hash Tables (DHT) and a Gossip protocol serves as the search engine for the internet of agentsites. This work provides a practical foundation for building the Internet of Agentsites-a new paradigm where autonomous agents become first-class citizens of the web. The implementation is available at https://github.com/agiresearch/AIOS.Server and will be integrated into the AIOS main branch at https://github.com/agiresearch/AIOS.

[Arxiv](https://arxiv.org/abs/2504.14411)