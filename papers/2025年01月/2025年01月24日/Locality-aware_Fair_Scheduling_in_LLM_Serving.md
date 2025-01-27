# LLM 服务中的局部性感知公平调度

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLM）在推理工作负载中的应用，特别是如何通过改进调度算法来提高效率和公平性。论文提出的DLPM和D$^2$LPM算法旨在优化LLM服务的性能，这属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `人工智能` `分布式系统`

> Locality-aware Fair Scheduling in LLM Serving

# 摘要

> # 摘要
大型语言模型（LLM）推理工作负载在现代AI应用中占据主导地位，从多轮对话到文档分析。平衡公平性和效率对于管理具有不同前缀模式的多样化客户端工作负载至关重要。然而，现有的LLM服务公平调度算法，如虚拟令牌计数器（VTC），未能考虑前缀局部性，导致性能不佳。另一方面，现有LLM服务框架中的局部性感知调度算法倾向于最大化前缀缓存命中率，而忽略了客户端之间的公平共享。
本文提出了首个局部性感知公平调度算法——Deficit Longest Prefix Match (DLPM)，它能在保证公平性的同时，保持高度的前缀局部性。我们还引入了一种新算法——Double Deficit LPM (D$^2$LPM)，扩展了DLPM以适用于分布式环境，能够在公平性、局部性和负载平衡之间找到最佳平衡点。广泛的评估结果表明，DLPM和D$^2$LPM在确保公平性的同时，显著提升了吞吐量（比VTC高2.87倍）并降低了每客户端延迟（比最先进的分布式LLM服务系统低7.18倍）。

> Large language model (LLM) inference workload dominates a wide variety of modern AI applications, ranging from multi-turn conversation to document analysis. Balancing fairness and efficiency is critical for managing diverse client workloads with varying prefix patterns. Unfortunately, existing fair scheduling algorithms for LLM serving, such as Virtual Token Counter (VTC), fail to take prefix locality into consideration and thus suffer from poor performance. On the other hand, locality-aware scheduling algorithms in existing LLM serving frameworks tend to maximize the prefix cache hit rate without considering fair sharing among clients.
  This paper introduces the first locality-aware fair scheduling algorithm, Deficit Longest Prefix Match (DLPM), which can maintain a high degree of prefix locality with a fairness guarantee. We also introduce a novel algorithm, Double Deficit LPM (D$^2$LPM), extending DLPM for the distributed setup that can find a balance point among fairness, locality, and load-balancing. Our extensive evaluation demonstrates the superior performance of DLPM and D$^2$LPM in ensuring fairness while maintaining high throughput (up to 2.87$\times$ higher than VTC) and low per-client (up to 7.18$\times$ lower than state-of-the-art distributed LLM serving system) latency.

[Arxiv](https://arxiv.org/abs/2501.14312)