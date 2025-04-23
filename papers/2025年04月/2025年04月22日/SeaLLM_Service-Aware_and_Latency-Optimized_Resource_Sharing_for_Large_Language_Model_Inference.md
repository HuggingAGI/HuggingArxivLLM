# SeaLLM: 服务感知与延迟优化的大型语言模型推理资源共享方案

发布时间：2025年04月22日

`LLM应用` `云计算` `资源管理`

> SeaLLM: Service-Aware and Latency-Optimized Resource Sharing for Large Language Model Inference

# 摘要

> 不同架构和规模的大型语言模型 (LLMs) 已经被开发出来。然而，为每个 LLM 分配专用 GPU 会导致资源浪费和服务低效，因为 LLM 请求的需求各不相同。我们发现，现有的共享系统要么不考虑 LLM 服务的自回归特性，要么只关注提高吞吐量，这会损害共享性能，尤其是在服务延迟方面。为此，我们提出了 SeaLLM，它能够实现服务感知且延迟优化的 LLM 共享。SeaLLM 通过以下三个方面的改进提升了整体共享性能：(1) 一种利用 LLM 服务特性的延迟优化调度算法，(2) 一个确定放置计划的放置算法和一个决定替换间隔的自适应替换算法，(3) 一个统一的键值缓存，用于在 LLM 服务之间高效共享 GPU 内存。我们的实证分析表明，与现有解决方案相比，SeaLLM 将标准化延迟提升了高达【数学公式】倍，尾部延迟提升了高达【数学公式】倍，以及服务级别目标 (SLO) 达成率提升了高达【数学公式】倍。

> Large language models (LLMs) with different architectures and sizes have been developed. Serving each LLM with dedicated GPUs leads to resource waste and service inefficiency due to the varying demand of LLM requests. A common practice is to share multiple LLMs. However, existing sharing systems either do not consider the autoregressive pattern of LLM services, or only focus on improving the throughput, which impairs the sharing performance, especially the serving latency. We present SeaLLM, which enables service-aware and latency-optimized LLM sharing. SeaLLM improves the overall sharing performance by (1) a latency-optimized scheduling algorithm utilizing the characteristics of LLM services, (2) a placement algorithm to determine the placement plan and an adaptive replacement algorithm to decide the replacement interval, and (3) a unified key-value cache to share GPU memory among LLM services efficiently. Our evaluation under real-world traces and LLM services demonstrates that SeaLLM improves the normalized latency by up to $13.60\times$, the tail latency by up to $18.69\times$, and the SLO attainment by up to $3.64\times$ compared to existing solutions.

[Arxiv](https://arxiv.org/abs/2504.15720)