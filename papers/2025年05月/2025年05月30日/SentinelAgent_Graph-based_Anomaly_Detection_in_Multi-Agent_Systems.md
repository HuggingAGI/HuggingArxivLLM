# SentinelAgent：多智能体系统中的图结构异常检测

发布时间：2025年05月30日

`Agent` `人工智能` `办公自动化`

> SentinelAgent: Graph-based Anomaly Detection in Multi-Agent Systems

# 摘要

> 大型语言模型（LLM）为基础的多智能体系统（MAS）的兴起，带来了新的安全与可靠性挑战。尽管这些系统在分解和协调复杂任务方面展现出巨大潜力，但它们也面临来自提示操纵、不安全工具使用以及突发智能体协同失调等多方面的风险。现有的保护机制仅提供部分防护，主要集中在输入输出层面，未能有效应对MAS中的系统性或多点故障。在本研究中，我们提出了一种专为MAS设计的系统级异常检测框架，将结构建模与运行时行为监督相结合。我们的方法包含两个组成部分。首先，我们提出了一种基于图的框架，将智能体交互建模为动态执行图，从而实现节点、边和路径层面的语义异常检测。其次，我们引入了一种可插拔的SentinelAgent，这是一种由LLM驱动的监督智能体，能够根据安全策略和上下文推理，观察、分析并干预MAS的执行。通过将抽象的检测逻辑与可执行的防护措施相结合，我们的方法不仅能够检测单点故障和提示注入，还能够识别多智能体合谋和潜在的利用路径。我们通过两个案例研究验证了我们的框架，包括一个电子邮件助手和微软的Magentic-One系统，展示了其检测隐蔽风险并提供可解释的根本原因归属的能力。我们的工作为构建更加可信、可监控和安全的基于智能体的AI生态系统奠定了基础。

> The rise of large language model (LLM)-based multi-agent systems (MAS) introduces new security and reliability challenges. While these systems show great promise in decomposing and coordinating complex tasks, they also face multi-faceted risks across prompt manipulation, unsafe tool usage, and emergent agent miscoordination. Existing guardrail mechanisms offer only partial protection, primarily at the input-output level, and fall short in addressing systemic or multi-point failures in MAS. In this work, we present a system-level anomaly detection framework tailored for MAS, integrating structural modeling with runtime behavioral oversight. Our approach consists of two components. First, we propose a graph-based framework that models agent interactions as dynamic execution graphs, enabling semantic anomaly detection at node, edge, and path levels. Second, we introduce a pluggable SentinelAgent, an LLM-powered oversight agent that observes, analyzes, and intervenes in MAS execution based on security policies and contextual reasoning. By bridging abstract detection logic with actionable enforcement, our method detects not only single-point faults and prompt injections but also multi-agent collusion and latent exploit paths. We validate our framework through two case studies, including an email assistant and Microsoft's Magentic-One system, demonstrating its ability to detect covert risks and provide explainable root-cause attribution. Our work lays the foundation for more trustworthy, monitorable, and secure agent-based AI ecosystems.

[Arxiv](https://arxiv.org/abs/2505.24201)