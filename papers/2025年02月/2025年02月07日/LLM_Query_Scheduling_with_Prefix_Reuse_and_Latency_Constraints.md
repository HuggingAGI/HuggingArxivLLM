# LLM查询调度：前缀重用与延迟约束

发布时间：2025年02月07日

`LLM应用` `互联网服务` `云计算`

> LLM Query Scheduling with Prefix Reuse and Latency Constraints

# 摘要

> 在在线环境中高效部署大型语言模型（LLMs）需要在严格的延迟约束下优化推理性能，特别是首次生成令牌时间（TTFT）和每输出令牌时间（TPOT）。本文专注于具有前缀复用技术的LLM推理查询调度问题，该技术通过利用跨查询的共享前缀来减少计算开销。我们的研究揭示了现有先到先服务（FCFS）和最长前缀匹配（LPM）调度策略在满足延迟约束方面的未知限制。我们提出了一种基于RadixAttention的前缀复用机制的LLM查询调度形式化理论框架，该机制通过在基数树结构中存储和复用中间表示来实现前缀复用。我们的分析证明了在TTFT约束下具有前缀复用的调度问题的NP难性质，并提出了一种新型调度算法【数学公式】-LPM，该算法通过平衡前缀复用和查询处理的公平性来推广现有方法。理论保证表明，【数学公式】-LPM在现实流量模式下由数据生成模型捕获时能够实现改进的TTFT性能。在现实服务环境中的实证评估验证了我们的发现，与基线方法相比，P99 TTFT显著降低。

> The efficient deployment of large language models (LLMs) in online settings requires optimizing inference performance under stringent latency constraints, particularly the time-to-first-token (TTFT) and time-per-output-token (TPOT). This paper focuses on the query scheduling problem for LLM inference with prefix reuse, a technique that leverages shared prefixes across queries to reduce computational overhead. Our work reveals previously unknown limitations of the existing first-come-first-serve (FCFS) and longest-prefix-match (LPM) scheduling strategies with respect to satisfying latency constraints. We present a formal theoretical framework for LLM query scheduling under RadixAttention, a prefix reuse mechanism that stores and reuses intermediate representations in a radix tree structure. Our analysis establishes the NP-hardness of the scheduling problem with prefix reuse under TTFT constraints and proposes a novel scheduling algorithm, $k$-LPM, which generalizes existing methods by balancing prefix reuse and fairness in query processing. Theoretical guarantees demonstrate that $k$-LPM achieves improved TTFT performance under realistic traffic patterns captured by a data generative model. Empirical evaluations in a realistic serving setting validates our findings, showing significant reductions in P99 TTFT compared to baseline methods.

[Arxiv](https://arxiv.org/abs/2502.04677)