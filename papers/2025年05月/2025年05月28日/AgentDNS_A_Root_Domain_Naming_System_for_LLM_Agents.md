# # AgentDNS：大型语言模型代理的根域名系统

发布时间：2025年05月28日

`Agent

理由：这篇论文探讨了大型语言模型（LLM）代理之间的协作和通信问题，提出了一个名为AgentDNS的系统来解决跨供应商服务发现的挑战。该系统类似于传统的DNS，旨在让LLM代理能够自主发现和调用第三方服务。这属于Agent技术的发展和应用，因此归类于Agent。` `信息技术` `互联网服务`

> AgentDNS: A Root Domain Naming System for LLM Agents

# 摘要

> 大型语言模型 (LLM) 代理的快速发展凸显了跨供应商服务发现、互操作性和通信的关键挑战。尽管模型上下文协议和代理间协议在标准化代理与工具的互操作性以及多代理通信方面取得了显著进展，但跨不同供应商的服务发现仍缺乏标准化解决方案。为此，我们提出了 AgentDNS，一个根域名命名和服务发现系统，旨在让 LLM 代理能够跨组织和技术边界自主发现、解析并安全调用第三方服务。AgentDNS 受传统 DNS 启发，提供服务注册、语义发现、安全调用和统一计费的结构化机制。通过详细阐述 AgentDNS 的架构、核心功能及应用场景，我们展示了其在现实场景中简化多代理协作的潜力。源代码即将发布于 https://github.com/agentdns。


> The rapid evolution of Large Language Model (LLM) agents has highlighted critical challenges in cross-vendor service discovery, interoperability, and communication. Existing protocols like model context protocol and agent-to-agent protocol have made significant strides in standardizing interoperability between agents and tools, as well as communication among multi-agents. However, there remains a lack of standardized protocols and solutions for service discovery across different agent and tool vendors. In this paper, we propose AgentDNS, a root domain naming and service discovery system designed to enable LLM agents to autonomously discover, resolve, and securely invoke third-party agent and tool services across organizational and technological boundaries. Inspired by the principles of the traditional DNS, AgentDNS introduces a structured mechanism for service registration, semantic service discovery, secure invocation, and unified billing. We detail the architecture, core functionalities, and use cases of AgentDNS, demonstrating its potential to streamline multi-agent collaboration in real-world scenarios. The source code will be published on https://github.com/agentdns.

[Arxiv](https://arxiv.org/abs/2505.22368)