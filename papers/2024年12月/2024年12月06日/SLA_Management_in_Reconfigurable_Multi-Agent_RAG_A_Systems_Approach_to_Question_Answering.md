# 在可重构多智能体 RAG 中的 SLA 管理：一种问答的系统方法

发布时间：2024年12月06日

`RAG`

> SLA Management in Reconfigurable Multi-Agent RAG: A Systems Approach to Question Answering

# 摘要

> 检索增强生成（RAG）能让大型语言模型（LLMs）将推理能力与静态知识库分离，从而推广到新信息。传统的 RAG 增强探索了纵向扩展——把子任务分配给专门模块，以及横向扩展——在多个代理间复制任务，以此来提升性能。然而，现实应用有着各种各样的服务级别协议（SLAs）和服务质量（QoS）要求，这就涉及在降低成本、保证答案质量和遵循特定操作约束等目标之间进行权衡。
    在这项工作中，我们为现实世界的问答（QA）应用提出了一种面向系统的多代理 RAG 方法。通过把特定任务的非功能性需求，比如答案质量、成本和延迟等，融入系统，我们能够实现动态重新配置，以满足不同的 SLA。我们的方法将这些服务级别目标（SLOs）映射到系统级参数，从而在指定资源约束内生成最优结果。
    我们在 QA 领域开展了一个案例研究，展示了多代理 RAG 系统的动态重新编排如何有效管理答案质量和成本之间的权衡。依据查询意图和操作条件来调整系统，我们能系统地平衡性能和资源利用。这种方法能让系统满足各种查询类型的 SLO，展现了其在现实应用中的实用性。

> Retrieval Augmented Generation (RAG) enables Large Language Models (LLMs) to generalize to new information by decoupling reasoning capabilities from static knowledge bases. Traditional RAG enhancements have explored vertical scaling -- assigning subtasks to specialized modules -- and horizontal scaling -- replicating tasks across multiple agents -- to improve performance. However, real-world applications impose diverse Service Level Agreements (SLAs) and Quality of Service (QoS) requirements, involving trade-offs among objectives such as reducing cost, ensuring answer quality, and adhering to specific operational constraints.
  In this work, we present a systems-oriented approach to multi-agent RAG tailored for real-world Question Answering (QA) applications. By integrating task-specific non-functional requirements -- such as answer quality, cost, and latency -- into the system, we enable dynamic reconfiguration to meet diverse SLAs. Our method maps these Service Level Objectives (SLOs) to system-level parameters, allowing the generation of optimal results within specified resource constraints.
  We conduct a case study in the QA domain, demonstrating how dynamic re-orchestration of a multi-agent RAG system can effectively manage the trade-off between answer quality and cost. By adjusting the system based on query intent and operational conditions, we systematically balance performance and resource utilization. This approach allows the system to meet SLOs for various query types, showcasing its practicality for real-world applications.

[Arxiv](https://arxiv.org/abs/2412.06832)