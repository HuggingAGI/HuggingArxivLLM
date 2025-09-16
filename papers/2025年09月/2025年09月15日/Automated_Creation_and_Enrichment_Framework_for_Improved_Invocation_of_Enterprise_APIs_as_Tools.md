# 旨在提升企业API工具调用效果的自动化构建与增强框架

发布时间：2025年09月15日

`Agent` `工业与制造`

> Automated Creation and Enrichment Framework for Improved Invocation of Enterprise APIs as Tools

# 摘要

> 大型语言模型（LLMs）的最新进展推动了智能体的发展，这些智能体能够进行复杂推理并与外部工具交互。在企业场景中，这类通常由应用程序编程接口（APIs）支持的工具，其有效使用受到文档质量差、输入输出模式复杂及操作数量繁多的制约。这些挑战不仅增加了工具选择的难度，还导致有效载荷生成的准确性下降高达25%。为此，我们提出ACE——一个自动化工具创建与增强框架，可将企业APIs转化为LLM兼容工具。ACE的核心功能包括：（i）生成增强版工具规范，包含参数描述和示例，以提升选择与调用准确性；（ii）集成动态筛选机制，在运行时过滤相关工具，在确保可扩展性的同时降低提示复杂度。我们在专有及开源APIs上对该框架进行了验证，并演示了其与智能体框架的集成效果。据我们所知，ACE是首个端到端框架，可自动完成LLM智能体所需企业API工具的创建、增强与动态选择。

> Recent advancements in Large Language Models (LLMs) has lead to the development of agents capable of complex reasoning and interaction with external tools. In enterprise contexts, the effective use of such tools that are often enabled by application programming interfaces (APIs), is hindered by poor documentation, complex input or output schema, and large number of operations. These challenges make tool selection difficult and reduce the accuracy of payload formation by up to 25%. We propose ACE, an automated tool creation and enrichment framework that transforms enterprise APIs into LLM-compatible tools. ACE, (i) generates enriched tool specifications with parameter descriptions and examples to improve selection and invocation accuracy, and (ii) incorporates a dynamic shortlisting mechanism that filters relevant tools at runtime, reducing prompt complexity while maintaining scalability. We validate our framework on both proprietary and open-source APIs and demonstrate its integration with agentic frameworks. To the best of our knowledge, ACE is the first end-to-end framework that automates the creation, enrichment, and dynamic selection of enterprise API tools for LLM agents.

[Arxiv](https://arxiv.org/abs/2509.11626)