# Patchwork：一个统一的RAG服务框架

发布时间：2025年05月01日

`RAG` `人工智能` `服务端`

> Patchwork: A Unified Framework for RAG Serving

# 摘要

> 检索增强生成（RAG）作为一种新兴范式，通过整合外部知识源来提升大型语言模型的可靠性。然而，这些系统在高效部署方面面临重大技术挑战，因为它们本质上是由大型语言模型、数据库和专用处理组件组成的异构计算流水线。我们引入Patchwork，这是一个全面的端到端RAG服务框架，旨在解决这些效率瓶颈。Patchwork的架构带来了三个关键创新：首先，它提供了一个灵活的规范接口，使用户能够实现自定义的RAG流水线。其次，它将这些流水线部署为分布式推理系统，同时针对各个RAG组件的独特可扩展性特点进行优化。第三，Patchwork集成了一个在线调度机制，持续监控请求负载和执行进度，通过策略性地优先处理请求和自动扩展资源，动态最小化SLO违规。我们对四种不同RAG实现的实验评估表明，与商业替代方案相比，Patchwork实现了显著的性能提升，吞吐量提高了48%以上，同时将SLO违规减少了约24%。

> Retrieval Augmented Generation (RAG) has emerged as a new paradigm for enhancing Large Language Model reliability through integration with external knowledge sources. However, efficient deployment of these systems presents significant technical challenges due to their inherently heterogeneous computational pipelines comprising LLMs, databases, and specialized processing components. We introduce Patchwork, a comprehensive end-to-end RAG serving framework designed to address these efficiency bottlenecks. Patchwork's architecture offers three key innovations: First, it provides a flexible specification interface enabling users to implement custom RAG pipelines. Secondly, it deploys these pipelines as distributed inference systems while optimizing for the unique scalability characteristics of individual RAG components. Third, Patchwork incorporates an online scheduling mechanism that continuously monitors request load and execution progress, dynamically minimizing SLO violations through strategic request prioritization and resource auto-scaling. Our experimental evaluation across four distinct RAG implementations demonstrates that Patchwork delivers substantial performance improvements over commercial alternatives, achieving throughput gains exceeding 48% while simultaneously reducing SLO violations by ~24%.

[Arxiv](https://arxiv.org/abs/2505.07833)