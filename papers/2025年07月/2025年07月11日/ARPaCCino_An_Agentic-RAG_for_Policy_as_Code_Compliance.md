# ARPaCCino：一个智能体增强检索生成框架，用于策略即代码的合规性。

发布时间：2025年07月11日

`RAG` `云计算` `IT基础设施`

> ARPaCCino: An Agentic-RAG for Policy as Code Compliance

# 摘要

> 策略即代码（PaC）是一种将安全与合规策略编码为机器可读格式的范式，可在基础设施即代码（IaC）环境中实现自动化执行。然而，其采用受到了策略语言复杂性和配置错误风险的限制。我们提出了ARPaCCino，一个结合大型语言模型（LLMs）、增强生成式检索（RAG）和工具化验证的智能系统，用于自动化生成和验证PaC规则。基于自然语言描述的目标策略，ARPaCCino可生成正式的Rego规则，评估IaC合规性，并迭代优化IaC配置以确保符合性。凭借其模块化智能架构和与外部工具及知识库的集成，ARPaCCino支持跨多种技术的策略验证，包括小众或新兴的IaC框架。基于Terraform的案例研究实验表明，即使使用较小规模的开源权重LLMs，ARPaCCino也能有效生成语法和语义均正确的策略，识别不合规的基础设施，并应用纠正性修改。研究结果凸显了智能RAG架构在提升PaC工作流自动化水平、可靠性和可及性方面的潜力。

> Policy as Code (PaC) is a paradigm that encodes security and compliance policies into machine-readable formats, enabling automated enforcement in Infrastructure as Code (IaC) environments. However, its adoption is hindered by the complexity of policy languages and the risk of misconfigurations. In this work, we present ARPaCCino, an agentic system that combines Large Language Models (LLMs), Retrieval-Augmented-Generation (RAG), and tool-based validation to automate the generation and verification of PaC rules. Given natural language descriptions of the desired policies, ARPaCCino generates formal Rego rules, assesses IaC compliance, and iteratively refines the IaC configurations to ensure conformance. Thanks to its modular agentic architecture and integration with external tools and knowledge bases, ARPaCCino supports policy validation across a wide range of technologies, including niche or emerging IaC frameworks. Experimental evaluation involving a Terraform-based case study demonstrates ARPaCCino's effectiveness in generating syntactically and semantically correct policies, identifying non-compliant infrastructures, and applying corrective modifications, even when using smaller, open-weight LLMs. Our results highlight the potential of agentic RAG architectures to enhance the automation, reliability, and accessibility of PaC workflows.

[Arxiv](https://arxiv.org/abs/2507.10584)