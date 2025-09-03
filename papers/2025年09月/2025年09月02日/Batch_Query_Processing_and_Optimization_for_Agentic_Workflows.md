# 智能体工作流的批查询处理与优化

发布时间：2025年09月02日

`Agent` `基础理论`

> Batch Query Processing and Optimization for Agentic Workflows

# 摘要

> 在智能体工作流中，大型语言模型（LLMs）融合了多步推理、工具调用能力以及多专业智能体间的协同合作。现有的LLM服务引擎仅孤立地优化单次调用，而多智能体框架则侧重于流程编排，却忽略了系统级的性能规划。这导致重复提示、上下文重叠和并发执行问题频发，造成大量冗余计算和GPU利用率低下，在批处理分析场景中尤为突出。为此，我们提出了Halo系统，它将批处理查询的处理与优化机制引入智能体LLM工作流。Halo将每个工作流抽象为结构化查询计划DAG，并为批处理查询构建整合图，从而揭示可共享的计算部分。Halo通过成本模型统筹预填充和解码成本、缓存重用及GPU部署，并以此为指导进行计划级优化，最大限度减少冗余执行。其运行时集成了自适应批处理、KV缓存共享与迁移技术，并通过计算-通信重叠机制，显著提升硬件效率。六项基准测试结果显示，Halo在批处理推理中提速高达18.6倍，在线服务吞吐量提升4.7倍，且能轻松应对数万个查询及复杂图结构的工作负载。所有性能提升均未以牺牲输出质量为代价。通过将查询优化与LLM服务深度融合，Halo为数据分析和决策应用打造了高效的智能体工作流。

> Large Language Models (LLMs) in agentic workflows combine multi-step reasoning, tool use, and collaboration across multiple specialized agents. Existing LLM serving engines optimize indi- vidual calls in isolation, while multi-agent frameworks focus on orchestration without system-level performance planning. As a result, repeated prompts, overlapping contexts, and concurrent ex- ecutions create substantial redundancy and poor GPU utilization, especially in batch analytics scenarios. We introduce Halo, a system that brings batch query processing and optimization into agentic LLM workflows. Halo represents each workflow as a structured query plan DAG and constructs a consoli- dated graph for batched queries that exposes shared computation. Guided by a cost model that jointly considers prefill and decode costs, cache reuse, and GPU placement, Halo performs plan-level op- timization to minimize redundant execution. Its runtime integrates adaptive batching, KV-cache sharing and migration, along with compute-communication overlap to maximize hardware efficiency. Evaluation across six benchmarks shows that Halo achieves up to 18.6x speedup for batch inference and 4.7x throughput im- provement under online serving, scaling to workloads of tens of thousands of queries and complex graphs. These gains are achieved without compromising output quality. By unifying query optimiza- tion with LLM serving, Halo enables efficient agentic workflows in data analytics and decision-making applications.

[Arxiv](https://arxiv.org/abs/2509.02121)