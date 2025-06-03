# 大型语言模型代理在网络协议中的功能漏洞检测

发布时间：2025年05月31日

`LLM应用` `网络协议` `工具开发`

> An LLM Agent for Functional Bug Detection in Network Protocols

# 摘要

> 功能正确性是确保网络协议实现可靠与安全的关键。当协议实现与RFC文档规定的行为出现偏差时，可能导致路由错误、认证绕过甚至服务中断等严重后果。由于检测这些功能缺陷需要对规范文档和源代码进行深度语义分析，传统静态分析工具难以胜任。为此，我们提出了RFCScan——一个基于大型语言模型（LLMs）的自主工具，通过检查协议实现与RFC规范的一致性来发现功能缺陷。RFCScan的设计灵感来源于人工审核流程，包含两个核心组件：索引模块和检测模块。索引模块通过层次化总结协议代码的语义特征，生成语义索引，帮助检测模块缩小排查范围。检测模块则采用按需检索策略，逐步收集相关数据结构和函数，精准定位与RFC规范的潜在不一致。我们在六种实际网络协议实现中对RFCScan进行了评估。结果表明，RFCScan以81.9%的准确率识别出47个功能缺陷，其中20个已被开发人员确认或修复。

> Functional correctness is critical for ensuring the reliability and security of network protocol implementations. Functional bugs, instances where implementations diverge from behaviors specified in RFC documents, can lead to severe consequences, including faulty routing, authentication bypasses, and service disruptions. Detecting these bugs requires deep semantic analysis across specification documents and source code, a task beyond the capabilities of traditional static analysis tools. This paper introduces RFCScan, an autonomous agent that leverages large language models (LLMs) to detect functional bugs by checking conformance between network protocol implementations and their RFC specifications. Inspired by the human auditing procedure, RFCScan comprises two key components: an indexing agent and a detection agent. The former hierarchically summarizes protocol code semantics, generating semantic indexes that enable the detection agent to narrow down the scanning scope. The latter employs demand-driven retrieval to iteratively collect additional relevant data structures and functions, eventually identifying potential inconsistencies with the RFC specifications effectively. We evaluate RFCScan across six real-world network protocol implementations. RFCScan identifies 47 functional bugs with 81.9% precision, of which 20 bugs have been confirmed or fixed by developers.

[Arxiv](https://arxiv.org/abs/2506.00714)