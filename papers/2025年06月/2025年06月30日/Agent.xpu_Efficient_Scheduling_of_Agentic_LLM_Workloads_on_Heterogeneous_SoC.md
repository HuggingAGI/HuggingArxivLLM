# Agent.xpu：在异构片上系统上实现智能体LLM负载的高效调度

发布时间：2025年06月30日

`LLM应用` `设备端` `异构计算`

> Agent.xpu: Efficient Scheduling of Agentic LLM Workloads on Heterogeneous SoC

# 摘要

> 智能体大型语言模型（LLMs）在个人设备上的普及催生了一类新型工作负载，这类工作负载具有目标二元性。用户发起的响应式任务要求即时、低延迟的响应，而主动式任务则在后台静默运行，注重吞吐量。现有的设备端LLM引擎，专为孤立推理设计，在消费级异构SoC（包含CPU、集成GPU和NPU）上，无法高效管理这些并发且相互冲突的请求。本文推出Agent.xpu，一个针对内存统一异构SoC上智能体LLM工作负载的高效服务系统。通过专用离线分析，Agent.xpu首先构建异构执行图，融合并切分模型内核，以实现基于亲和力引导的弹性加速器映射和预测性内核标注。在运行时，其在线调度器通过细粒度内核级抢占，确保响应式任务的即时响应。为了最大化SoC利用率，它采用松弛感知内核回填， Opportunistically追加主动式任务，并通过带宽感知分发缓解NPU与iGPU之间的资源竞争。在Intel Core Ultra SoC上的评估表明，与最先进的推理引擎相比，Agent.xpu使响应式任务的延迟降低了4.6×，同时将主动式任务的吞吐量提升了1.6×-6.8×。

> The proliferation of agentic Large Language Models (LLMs) on personal devices introduces a new class of workloads characterized by a dichotomy of objectives. Reactive tasks, initiated by users, demand immediate, low-latency responses, while proactive tasks operate invisibly and prioritize throughput. Existing on-device LLM engines, designed for isolated inferences, fail to efficiently manage these concurrent and conflicting requests on consumer-grade heterogeneous SoCs with CPU, integrated GPU, and NPU. This paper introduces Agent.xpu, an efficient serving system for agentic LLM workloads on memory-unified heterogeneous SoCs. With dedicated offline profiling, Agent.xpu first constructs a heterogeneous execution graph, which fuses and chunks model kernels for affinity-guided, elastic accelerator mapping with predictive kernel annotation. At runtime, its online scheduler enables fine-grained, kernel-level preemption to guarantee the responsiveness of reactive tasks. To maximize SoC utilization, it adopts slack-aware kernel backfill to opportunistically append proactive tasks, and mitigates NPU-iGPU contention via bandwidth-aware dispatch. Evaluation on an Intel Core Ultra SoC shows that Agent.xpu achieves 4.6$\times$ lower latency for reactive tasks and sustains 1.6$\times$-6.8$\times$ higher throughput for proactive tasks compared to state-of-the-art inference engines.

[Arxiv](https://arxiv.org/abs/2506.24045)