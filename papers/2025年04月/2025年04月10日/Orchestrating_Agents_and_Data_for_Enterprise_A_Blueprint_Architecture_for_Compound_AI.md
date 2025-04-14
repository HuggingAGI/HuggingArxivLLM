# # 为企业编排智能体与数据：复合型AI的蓝图架构
为企业编排智能体与数据，构建复合型AI的蓝图架构

发布时间：2025年04月10日

`LLM应用`

> Orchestrating Agents and Data for Enterprise: A Blueprint Architecture for Compound AI

# 摘要

> 大型语言模型（LLMs）凭借其跨任务的卓越能力，引发了工业界的广泛关注。然而，大规模部署LLMs面临诸多挑战，包括与现有应用和基础设施的集成、企业专有数据与模型的利用，以及成本、质量、响应速度等多维度要求的满足。为应对这些挑战，AI系统正经历从单体模型向化合物AI系统的转变，旨在构建更强大、多样化和可靠的解决方案。然而，尽管提出了智能体工作流、编程模型和扩展LLM能力等概念，但整体架构的清晰愿景仍未成型。本文为企业应用提出了一种协调智能体与数据的化合物AI系统'蓝图架构'。在该架构中，'流'作为核心协调概念，用于在智能体间协调数据与指令的流动。企业专有模型与API被映射为'智能体'，并在'智能体注册表'中定义，提供元数据与学习表示，支持搜索与规划。智能体通过'数据注册表'利用多模态企业数据。'规划器'根据服务质量要求（如成本、准确性和延迟）分解、映射和优化任务与查询。本文以企业人力资源领域为例，展示了该架构的实现，并探讨了'智能体AI'在企业中的机遇与挑战。

> Large language models (LLMs) have gained significant interest in industry due to their impressive capabilities across a wide range of tasks. However, the widespread adoption of LLMs presents several challenges, such as integration into existing applications and infrastructure, utilization of company proprietary data, models, and APIs, and meeting cost, quality, responsiveness, and other requirements. To address these challenges, there is a notable shift from monolithic models to compound AI systems, with the premise of more powerful, versatile, and reliable applications. However, progress thus far has been piecemeal, with proposals for agentic workflows, programming models, and extended LLM capabilities, without a clear vision of an overall architecture. In this paper, we propose a 'blueprint architecture' for compound AI systems for orchestrating agents and data for enterprise applications. In our proposed architecture the key orchestration concept is 'streams' to coordinate the flow of data and instructions among agents. Existing proprietary models and APIs in the enterprise are mapped to 'agents', defined in an 'agent registry' that serves agent metadata and learned representations for search and planning. Agents can utilize proprietary data through a 'data registry' that similarly registers enterprise data of various modalities. Tying it all together, data and task 'planners' break down, map, and optimize tasks and queries for given quality of service (QoS) requirements such as cost, accuracy, and latency. We illustrate an implementation of the architecture for a use-case in the HR domain and discuss opportunities and challenges for 'agentic AI' in the enterprise.

[Arxiv](https://arxiv.org/abs/2504.08148)