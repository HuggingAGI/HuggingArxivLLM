# LLM驱动工作流中的难度感知智能体编排

发布时间：2025年09月13日

`Agent` `基础理论`

> Difficulty-Aware Agent Orchestration in LLM-Powered Workflows

# 摘要

> 基于大型语言模型（LLM）的智能体系统在各类任务中已展现出强大能力。然而，现有的多智能体框架常依赖静态或任务级工作流，这会导致对简单查询过度处理，或在复杂查询上表现欠佳，同时还忽略了异构LLM之间的效率与性能权衡。为解决这些问题，我们提出难度感知智能体编排（Difficulty-Aware Agentic Orchestration，DAAO）——一个动态框架，它能根据每个输入查询的难度调整工作流深度、算子选择和LLM分配。DAAO包含三个相互关联的模块：用于难度估计的变分自编码器（VAE）、模块化算子分配器，以及兼顾成本与性能的LLM路由器。通过利用异构LLM并动态定制工作流，DAAO实现了细粒度且针对特定查询的推理策略。在六项基准测试中，DAAO在准确性和推理效率上均超越了以往的多智能体系统。我们将在论文发表时公开代码及实现细节。

> Large Language Model (LLM)-based agentic systems have shown strong capabilities across various tasks. However, existing multi-agent frameworks often rely on static or task-level workflows, which either over-process simple queries or underperform on complex ones, while also neglecting the efficiency-performance trade-offs across heterogeneous LLMs. To address these limitations, we propose Difficulty-Aware Agentic Orchestration (DAAO), a dynamic framework that adapts workflow depth, operator selection, and LLM assignment based on the difficulty of each input query. DAAO comprises three interdependent modules: a variational autoencoder (VAE) for difficulty estimation, a modular operator allocator, and a cost- and performance-aware LLM router. By leveraging heterogeneous LLMs and dynamically tailoring workflows, DAAO enables fine-grained, query-specific reasoning strategies. DAAO outperforms prior multi-agent systems in both accuracy and inference efficiency across six benchmarks. We will release our code and implementation details upon publication.

[Arxiv](https://arxiv.org/abs/2509.11079)