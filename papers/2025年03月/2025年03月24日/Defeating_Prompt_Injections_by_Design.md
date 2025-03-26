# 通过设计防御提示注入攻击

发布时间：2025年03月24日

`Agent` `智能体系统`

> Defeating Prompt Injections by Design

# 摘要

> 大型语言模型 (LLMs) 越来越广泛地应用于与外部环境交互的智能体系统中。然而，当处理不可信数据时，LLM 智能体容易受到提示注入攻击。本文中，我们提出了一种名为 CaMeL 的健壮防御方法，它在 LLM 周围创建了一个保护系统层，即使底层模型可能易受攻击，也能保障其安全。CaMeL 通过从可信查询中显式提取控制流和数据流来运行，因此 LLM 检索到的不可信数据永远不会对程序流程产生影响。为了进一步提高安全性，CaMeL 依赖一种能力概念，以防止通过未经授权的数据流外泄私人数据。我们在最近的智能体安全基准测试 AgentDojo [NeurIPS 2024] 上，通过解决具有可证明安全性的 67% 的任务，验证了 CaMeL 的有效性。

> Large Language Models (LLMs) are increasingly deployed in agentic systems that interact with an external environment. However, LLM agents are vulnerable to prompt injection attacks when handling untrusted data. In this paper we propose CaMeL, a robust defense that creates a protective system layer around the LLM, securing it even when underlying models may be susceptible to attacks. To operate, CaMeL explicitly extracts the control and data flows from the (trusted) query; therefore, the untrusted data retrieved by the LLM can never impact the program flow. To further improve security, CaMeL relies on a notion of a capability to prevent the exfiltration of private data over unauthorized data flows. We demonstrate effectiveness of CaMeL by solving $67\%$ of tasks with provable security in AgentDojo [NeurIPS 2024], a recent agentic security benchmark.

[Arxiv](https://arxiv.org/abs/2503.18813)