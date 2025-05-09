# # HEXGEN-TEXT2SQL：用于智能体文本到SQL工作流的LLM推理请求调度优化

发布时间：2025年05月08日

`其他` `数据库` `数据处理`

> HEXGEN-TEXT2SQL: Optimizing LLM Inference Request Scheduling for Agentic Text-to-SQL Workflow

# 摘要

> 最近，基于大型语言模型（LLMs）的智能体范式在提升Text-to-SQL能力方面取得了显著进展，让不具备专业数据库知识的用户也能直观地进行数据查询。然而，在实际生产环境中部署这些基于智能体的LLM Text-to-SQL系统面临多重挑战，主要源于其固有的多阶段工作流程、严格的延迟限制以及企业环境中可能存在的异构GPU基础设施。现有的LLM服务框架缺乏有效机制来处理相互依赖的推理任务、动态延迟变化和资源异构性，导致性能不佳并频繁违反服务级别目标（SLO）。本文介绍了一种名为HEXGEN-TEXT2SQL的新型框架，专为在异构GPU集群上调度和执行基于智能体的多阶段LLM Text-to-SQL工作流程而设计，能够处理多租户端到端查询。HEXGEN-TEXT2SQL采用了一种分层调度方法，结合全局工作负载平衡的任务分发和局部自适应紧急程度引导的优先级设置，这一方法基于对智能体Text-to-SQL工作流程的系统性分析。此外，我们提出了一种轻量级基于仿真的方法来调整关键调度超参数，进一步增强了系统的健壮性和适应性。在现实的Text-to-SQL基准测试中的广泛评估表明，与vLLM相比，HEXGEN-TEXT2SQL在多种现实工作负载条件下显著优于现有的LLM服务框架。具体而言，HEXGEN-TEXT2SQL将延迟截止时间减少了高达1.67倍（平均：1.41倍），并将系统吞吐量提高了高达1.75倍（平均：1.65倍）。我们的代码可在https://github.com/Relaxed-System-Lab/Hexgen-Flow获取。

> Recent advances in leveraging the agentic paradigm of large language models (LLMs) utilization have significantly enhanced Text-to-SQL capabilities, enabling users without specialized database expertise to query data intuitively. However, deploying these agentic LLM-based Text-to-SQL systems in production poses substantial challenges due to their inherently multi-stage workflows, stringent latency constraints, and potentially heterogeneous GPU infrastructure in enterprise environments. Current LLM serving frameworks lack effective mechanisms for handling interdependent inference tasks, dynamic latency variability, and resource heterogeneity, leading to suboptimal performance and frequent service-level objective (SLO) violations. In this paper, we introduce HEXGEN-TEXT2SQL, a novel framework designed explicitly to schedule and execute agentic multi-stage LLM-based Text-to-SQL workflows on heterogeneous GPU clusters that handle multi-tenant end-to-end queries. HEXGEN-TEXT2SQL introduce a hierarchical scheduling approach combining global workload-balanced task dispatching and local adaptive urgency-guided prioritization, guided by a systematic analysis of agentic Text-to-SQL workflows. Additionally, we propose a lightweight simulation-based method for tuning critical scheduling hyperparameters, further enhancing robustness and adaptability. Our extensive evaluation on realistic Text-to-SQL benchmarks demonstrates that HEXGEN-TEXT2SQL significantly outperforms state-of-the-art LLM serving frameworks. Specifically, HEXGEN-TEXT2SQL reduces latency deadlines by up to 1.67$\times$ (average: 1.41$\times$) and improves system throughput by up to 1.75$\times$ (average: 1.65$\times$) compared to vLLM under diverse, realistic workload conditions. Our code is available at https://github.com/Relaxed-System-Lab/Hexgen-Flow.

[Arxiv](https://arxiv.org/abs/2505.05286)