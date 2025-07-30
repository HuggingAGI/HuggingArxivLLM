# # **探索多智能体系统统一的定量安全基准测试**

发布时间：2025年07月23日

`Agent` `多智能体系统`

> Towards Unifying Quantitative Security Benchmarking for Multi Agent Systems

# 摘要

> 演进中的AI系统正越来越多地采用多智能体架构，其中自主智能体通过协议协作、共享信息并分派任务。这种互联性虽强大，却引入了新型安全风险。其中一个风险是级联风险：一个智能体的漏洞可能引发连锁反应，通过利用智能体间的信任机制，波及其他智能体。我们与OWASP发起的智能体AI漏洞评分系统计划同步，定义了一种新的攻击向量——智能体级联注入（Agent Cascading Injection），该向量与智能体影响链（Agent Impact Chain）和影响范围（Blast Radius）类似，能在智能体网络中运行。在ACI攻击中，恶意输入或工具利用被注入一个智能体后，会导致其他信任其输出的智能体发生连锁妥协，并放大下游影响。我们通过一个对抗性目标方程和关键变量（如被妥协智能体、注入漏洞、污染观测等）形式化了这种攻击，揭示了局部漏洞如何升级为系统性故障。随后，我们分析了ACI的属性——传播链、放大因子和智能体间复合效应——并将其映射到OWASP新兴的智能体AI风险类别（如影响链和编排利用）。最后，我们论证了ACI突显了定量基准框架评估智能体间通信协议安全性的迫切需求。我们提出了针对多智能体系统（如Google的A2A和Anthropic的MCP架构）的级联信任失效压力测试方法，为可衡量、标准化的智能体间安全评估奠定了基础。我们的工作为工程师提供了必要工具，用于评估系统韧性、基于数据驱动的架构权衡以及抵御新一代智能体威胁的强健防御机制。

> Evolving AI systems increasingly deploy multi-agent architectures where autonomous agents collaborate, share information, and delegate tasks through developing protocols. This connectivity, while powerful, introduces novel security risks. One such risk is a cascading risk: a breach in one agent can cascade through the system, compromising others by exploiting inter-agent trust. In tandem with OWASP's initiative for an Agentic AI Vulnerability Scoring System we define an attack vector, Agent Cascading Injection, analogous to Agent Impact Chain and Blast Radius, operating across networks of agents. In an ACI attack, a malicious input or tool exploit injected at one agent leads to cascading compromises and amplified downstream effects across agents that trust its outputs. We formalize this attack with an adversarial goal equation and key variables (compromised agent, injected exploit, polluted observations, etc.), capturing how a localized vulnerability can escalate into system-wide failure. We then analyze ACI's properties -- propagation chains, amplification factors, and inter-agent compound effects -- and map these to OWASP's emerging Agentic AI risk categories (e.g. Impact Chain and Orchestration Exploits). Finally, we argue that ACI highlights a critical need for quantitative benchmarking frameworks to evaluate the security of agent-to-agent communication protocols. We outline a methodology for stress-testing multi-agent systems (using architectures such as Google's A2A and Anthropic's MCP) against cascading trust failures, developing upon groundwork for measurable, standardized agent-to-agent security evaluation. Our work provides the necessary apparatus for engineers to benchmark system resilience, make data-driven architectural trade-offs, and develop robust defenses against a new generation of agentic threats.

[Arxiv](https://arxiv.org/abs/2507.21146)