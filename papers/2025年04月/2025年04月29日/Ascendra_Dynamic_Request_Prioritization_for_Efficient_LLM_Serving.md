# Ascendra：智能请求调度，提升LLM服务效率

发布时间：2025年04月29日

`LLM应用` `云计算` `资源管理`

> Ascendra: Dynamic Request Prioritization for Efficient LLM Serving

# 摘要

> 大语言模型（LLMs）的迅猛发展推动了对更高效服务策略的迫切需求。这里的效率特指满足服务级别目标（SLO）的请求比例，特别是首次生成Token的时间（TTFT）和Token生成间隔时间（TBT）。然而，现有系统往往顾此失彼，难以同时兼顾这两个指标。我们推出了一款名为Ascendra的LLM服务系统，它能够同时满足TTFT和TBT的SLO要求。Ascendra的核心设计理念在于：请求的紧急性会随着截止时间的临近而发生变化。为此，Ascendra将GPU资源划分为两类实例——低优先级和高优先级。低优先级实例通过非顺序处理请求来提升吞吐量，但可能引发请求饥饿问题。为了解决这一难题，Ascendra采用了一个性能模型来预测可能无法按时完成的请求，并主动将其转移至高优先级实例。高优先级实例经过优化设计，能够以低延迟处理临近截止时间的紧急请求。这种分区架构使Ascendra在高吞吐量和低延迟之间实现了完美平衡。通过大量测试表明，相较于vLLM和Sarathi-Serve，Ascendra的系统吞吐量提升了1.7倍，同时完美满足了TTFT和TBT的SLO要求。

> The rapid advancement of Large Language Models (LLMs) has driven the need for more efficient serving strategies. In this context, efficiency refers to the proportion of requests that meet their Service Level Objectives (SLOs), particularly for Time To First Token (TTFT) and Time Between Tokens (TBT). However, existing systems often prioritize one metric at the cost of the other. We present Ascendra, an LLM serving system designed to meet both TTFT and TBT SLOs simultaneously. The core insight behind Ascendra is that a request's urgency evolves as it approaches its deadline. To leverage this, Ascendra partitions GPU resources into two types of instances: low-priority and high-priority. Low-priority instances maximize throughput by processing requests out of arrival order, but at the risk of request starvation. To address this, Ascendra employs a performance model to predict requests at risk of missing their SLOs and proactively offloads them to high-priority instances. High-priority instances are optimized for low-latency execution and handle urgent requests nearing their deadlines. This partitioned architecture enables Ascendra to effectively balance high throughput and low latency. Extensive evaluation shows that Ascendra improves system throughput by up to 1.7x compared to vLLM and Sarathi-Serve while meeting both TTFT and TBT SLOs.

[Arxiv](https://arxiv.org/abs/2504.20828)