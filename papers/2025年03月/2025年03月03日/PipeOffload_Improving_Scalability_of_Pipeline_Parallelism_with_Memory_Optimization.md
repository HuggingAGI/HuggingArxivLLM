# PipeOffload：内存优化提升管道并行的可扩展性

发布时间：2025年03月03日

`LLM应用` `人工智能` `高性能计算`

> PipeOffload: Improving Scalability of Pipeline Parallelism with Memory Optimization

# 摘要

> 流水线并行（PP）是训练大型语言模型（LLMs）的常用方法，但其可扩展性常受限于高激活内存消耗，特别是在PP程度增加时。本文通过探索PP中的内存卸载策略，提出了解决这一问题的新思路。实证研究表明，在标准配置下，至少有一半甚至全部的激活内存可被卸载，且几乎无额外开销。针对无法完全卸载的情况，我们提出了一种选择性卸载策略，能以超线性方式降低峰值激活内存。我们还结合其他技术，综合优化吞吐量和内存使用。实验结果表明，每设备的激活内存随着阶段数增加而减少，使PP比TP更具优势，甚至在内存消耗更低的情况下实现高达19%的加速。我们的实现已开源，链接为\href{https://github.com/sail-sg/zero-bubble-pipeline-parallelism}{此地址}。

> Pipeline parallelism (PP) is widely used for training large language models (LLMs), yet its scalability is often constrained by high activation memory consumption as the number of in-flight microbatches grows with the degree of PP. In this paper, we focus on addressing this challenge by leveraging the under-explored memory offload strategy in PP. With empirical study, we discover that in the majority of standard configurations, at least half, and potentially all, of the activations can be offloaded with negligible overhead. In the cases where full overload is not possible, we introduce a novel selective offload strategy that decreases peak activation memory in a better-than-linear manner. Furthermore, we integrate memory offload with other techniques to jointly consider overall throughput and memory limitation. Our experiments proves that the per-device activation memory effectively reduces with the total number of stages, making PP a stronger alternative than TP, offering up to a 19\% acceleration with even lower memory consumption. The implementation is open-sourced at \href{https://github.com/sail-sg/zero-bubble-pipeline-parallelism}{this url}.

[Arxiv](https://arxiv.org/abs/2503.01328)