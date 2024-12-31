# 使用 Certaindex 高效服务 LLM 推理程序

发布时间：2024年12月30日

`LLM应用` `服务系统`

> Efficiently Serving LLM Reasoning Programs with Certaindex

# 摘要

> 大型语言模型（LLMs）的迅猛发展释放了其在诸如数学问题求解、代码生成和法律分析等高级推理任务方面的能力。此进展的关键在于推理时的推理算法，其通过探寻多种解决路径来优化输出，但这也导致了计算需求的增加和响应延迟。现有的服务系统难以适应这些算法的扩展特性或查询的不同难度，致使资源利用低效，延迟目标无法达成。
    我们推出了 Dynasor 系统，用于优化 LLM 推理查询的推理时计算。与传统引擎不同，Dynasor 会在推理查询中跟踪和调度请求，并运用 Certaindex（一种依据模型确定性衡量统计推理进展的代理）来动态引导计算分配。Dynasor 使调度与推理进展相适配：为难题分配更多计算资源，为简单问题减少计算，提前终止无望的查询，从而平衡准确性、延迟和成本。在各类数据集和算法中，Dynasor 在批处理中能减少高达 50%的计算量，在在线服务中能保持 3.3 倍更高的查询率或实现 4.7 倍更严格的延迟服务水平目标。

> The rapid evolution of large language models (LLMs) has unlocked their capabilities in advanced reasoning tasks like mathematical problem-solving, code generation, and legal analysis. Central to this progress are inference-time reasoning algorithms, which refine outputs by exploring multiple solution paths, at the cost of increasing compute demands and response latencies. Existing serving systems fail to adapt to the scaling behaviors of these algorithms or the varying difficulty of queries, leading to inefficient resource use and unmet latency targets.
  We present Dynasor, a system that optimizes inference-time compute for LLM reasoning queries. Unlike traditional engines, Dynasor tracks and schedules requests within reasoning queries and uses Certaindex, a proxy that measures statistical reasoning progress based on model certainty, to guide compute allocation dynamically. Dynasor co-adapts scheduling with reasoning progress: it allocates more compute to hard queries, reduces compute for simpler ones, and terminates unpromising queries early, balancing accuracy, latency, and cost. On diverse datasets and algorithms, Dynasor reduces compute by up to 50% in batch processing and sustaining 3.3x higher query rates or 4.7x tighter latency SLOs in online serving.

[Arxiv](https://arxiv.org/abs/2412.20993)