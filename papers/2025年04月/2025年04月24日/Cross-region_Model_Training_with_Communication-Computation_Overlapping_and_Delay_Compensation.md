# 跨区域模型训练：通信计算重叠与延迟补偿

发布时间：2025年04月24日

`LLM理论

摘要讨论了大型语言模型（LLMs）的训练优化，特别是跨区域训练中的通信延迟问题。作者提出了一种新的分布式训练框架CoCoDC，结合通信-计算重叠与延迟补偿策略，以优化训练效率和模型收敛性。这属于LLM训练方法的理论研究，因此归类为LLM理论。` `分布式计算` `大规模模型训练`

> Cross-region Model Training with Communication-Computation Overlapping and Delay Compensation

# 摘要

> 训练大型语言模型（LLMs）需要大量计算资源，通常需要跨区域数据中心协作（即跨区域训练）。然而，广域网中的高通信延迟严重制约了传统分布式训练的效率。虽然DiLoCo等方法减少了通信频率，但它们面临阻塞同步的难题。Streaming DiLoCo通过通信与计算重叠缓解了这一问题，但延迟全局更新和部分同步导致了更新陈旧和模型不一致，尤其在需要激进重叠以掩盖高延迟时，严重影响了收敛性。为此，我们提出了CoCoDC——一个结合通信-计算重叠与延迟补偿的新型分布式训练框架。在CoCoDC框架中，我们开发了基于泰勒展开的延迟补偿策略，有效缓解更新陈旧问题，并设计了自适应传输策略，通过动态调度模型片段同步优化带宽使用，加速收敛。大量实验表明，CoCoDC在最终准确性和训练速度方面均优于DiLoCo和Streaming DiLoCo。具体而言，与Streaming DiLoCo相比，CoCoDC将训练达到相当困惑度所需的步骤减少了高达21.0%。本研究为实现可扩展、高效的跨区域LLM训练提供了有效解决方案。

> Training large language models (LLMs) requires massive computational resources, often necessitating the aggregation of geographically distributed data centers (\ie, cross-region training). However, the high communication latency in wide-area networks severely degrades the efficiency of traditional distributed training. While methods like DiLoCo reduce communication frequency, they suffer from blocking synchronization. Streaming DiLoCo alleviates this issue via communication-computation overlapping but introduces update staleness and model inconsistency due to delayed global updates and partial synchronization. These factors impair convergence, especially when aggressive overlap is needed to mask high latency. We propose CoCoDC, a novel distributed training framework with communication-computation overlapping and delay compensation, to explicitly tackle these challenges. Within the CoCoDC framework, we specifically develop a novel Delay Compensation strategy based on Taylor expansion to effectively mitigate the staleness and an Adaptive Transmission strategy that dynamically schedules model fragment synchronization to optimize bandwidth usage and accelerate convergence. Extensive experiments highlight the superior performance of CoCoDC over both DiLoCo and Streaming DiLoCo regarding final accuracy and training speed. Specifically, CoCoDC reduces the training steps needed to reach a comparable perplexity by up to 21.0% compared to Streaming DiLoCo. Our work provides an effective solution for scalable and efficient cross-region LLM training.

[Arxiv](https://arxiv.org/abs/2504.17672)