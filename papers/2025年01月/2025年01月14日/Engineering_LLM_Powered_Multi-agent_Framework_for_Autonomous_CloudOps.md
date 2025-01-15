# 基于LLM的多智能体框架：自主云运维的工程实践

发布时间：2025年01月14日

`Agent

理由：这篇论文主要介绍了一个名为MOYA的多代理框架，该框架结合了生成式人工智能（GenAI）和人工控制，用于自动化管理和优化云基础设施。论文的重点在于多代理系统的设计和实现，以及其在复杂工作流中的应用。因此，这篇论文应归类为Agent。` `云计算` `自动化管理`

> Engineering LLM Powered Multi-agent Framework for Autonomous CloudOps

# 摘要

> # 云操作（CloudOps）
云操作（CloudOps）是一个快速崛起的领域，专注于云基础设施的自动化管理与优化，这对在复杂云环境中运营的组织至关重要。MontyCloud Inc. 作为该领域的领军企业，利用自主机器人管理云合规性、安全性和持续运营。为了让平台更易用且高效，我们引入了生成式人工智能（GenAI）技术。
在为 MontyCloud 系统开发基于 GenAI 的自主 CloudOps 解决方案时，我们遇到了诸多挑战，包括：i) 多样化的数据源；ii) 多流程的编排；以及 iii) 复杂工作流的自动化处理。为此，我们推出了 MOYA，一个多代理框架，它巧妙结合了 GenAI 的自主性与必要的人工控制。该框架整合了多种内外部系统，并在任务编排、安全性和错误处理等方面进行了优化，同时通过检索增强生成（RAG）技术提供精准、可靠的洞察。通过从业者的实践验证和自动化测试，我们的多代理系统在复杂工作流中展现出比非代理方法更高的准确性、响应速度和效率。

> Cloud Operations (CloudOps) is a rapidly growing field focused on the automated management and optimization of cloud infrastructure which is essential for organizations navigating increasingly complex cloud environments. MontyCloud Inc. is one of the major companies in the CloudOps domain that leverages autonomous bots to manage cloud compliance, security, and continuous operations. To make the platform more accessible and effective to the customers, we leveraged the use of GenAI.
  Developing a GenAI-based solution for autonomous CloudOps for the existing MontyCloud system presented us with various challenges such as i) diverse data sources; ii) orchestration of multiple processes; and iii) handling complex workflows to automate routine tasks. To this end, we developed MOYA, a multi-agent framework that leverages GenAI and balances autonomy with the necessary human control. This framework integrates various internal and external systems and is optimized for factors like task orchestration, security, and error mitigation while producing accurate, reliable, and relevant insights by utilizing Retrieval Augmented Generation (RAG). Evaluations of our multi-agent system with the help of practitioners as well as using automated checks demonstrate enhanced accuracy, responsiveness, and effectiveness over non-agentic approaches across complex workflows.

[Arxiv](https://arxiv.org/abs/2501.08243)