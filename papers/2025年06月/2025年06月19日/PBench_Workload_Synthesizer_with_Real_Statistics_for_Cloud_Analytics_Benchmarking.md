# PBench：基于真实统计数据的云分析基准测试工作负载合成器

发布时间：2025年06月19日

`其他

理由：这篇论文主要关注于工作负载合成方法，利用大型语言模型（LLMs）来生成额外的工作负载组件。虽然LLMs被用作工具，但论文的主要贡献在于工作负载合成和性能评估，而不是研究LLMs本身或其应用。因此，它更适合归类为“其他”。` `云计算` `数据分析`

> PBench: Workload Synthesizer with Real Statistics for Cloud Analytics Benchmarking

# 摘要

> 云服务提供商通常使用标准基准测试（如TPC-H和TPC-DS）来评估和优化云数据分析系统。然而，这些基准测试依赖于固定的查询模式，无法捕捉到真实云工作负载的执行统计信息。尽管一些云数据库供应商最近发布了真实的工作负载日志，但这些日志本身并不足以构成基准测试，因为它们通常缺乏原始SQL查询及其底层数据库等关键组件。

为了解决这一问题，本文提出了一种新的基于真实统计的工作负载合成方法，旨在生成能够模拟真实云工作负载执行统计信息（包括关键性能指标和算子分布）的合成工作负载。我们提出了PBench，这是一种新型的工作负载合成器，通过从现有基准测试中选择和组合工作负载组件（即查询和数据库）来构建合成工作负载。

本文研究了PBench中的三个关键挑战：
1. 通过引入一种基于多目标优化的组件选择方法，解决了性能指标和算子分布之间的平衡问题。
2. 设计了一种逐步细化工作负载时间戳的方法，以捕捉真实工作负载的时间动态特性。
3. 提出了一种组件增强方法，利用大型语言模型（LLMs）生成额外的工作负载组件，同时保持统计保真性。

我们在真实云工作负载日志上对PBench进行了评估，结果表明，与现有最先进的方法相比，PBench将近似误差降低了6倍。

> Cloud service providers commonly use standard benchmarks like TPC-H and TPC-DS to evaluate and optimize cloud data analytics systems. However, these benchmarks rely on fixed query patterns and fail to capture the real execution statistics of production cloud workloads. Although some cloud database vendors have recently released real workload traces, these traces alone do not qualify as benchmarks, as they typically lack essential components like the original SQL queries and their underlying databases. To overcome this limitation, this paper introduces a new problem of workload synthesis with real statistics, which aims to generate synthetic workloads that closely approximate real execution statistics, including key performance metrics and operator distributions, in real cloud workloads. To address this problem, we propose PBench, a novel workload synthesizer that constructs synthetic workloads by judiciously selecting and combining workload components (i.e., queries and databases) from existing benchmarks. This paper studies the key challenges in PBench. First, we address the challenge of balancing performance metrics and operator distributions by introducing a multi-objective optimization-based component selection method. Second, to capture the temporal dynamics of real workloads, we design a timestamp assignment method that progressively refines workload timestamps. Third, to handle the disparity between the original workload and the candidate workload, we propose a component augmentation approach that leverages large language models (LLMs) to generate additional workload components while maintaining statistical fidelity. We evaluate PBench on real cloud workload traces, demonstrating that it reduces approximation error by up to 6x compared to state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2506.16379)