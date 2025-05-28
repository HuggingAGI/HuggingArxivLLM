# Lookahead Q-Cache：伪查询助力 KV 缓存一致性淘汰

发布时间：2025年05月24日

`LLM应用` `计算资源管理`

> Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query

# 摘要

> 大型语言模型 (LLMs) 通过键值缓存 (KV cache) 减少冗余计算来加速解码。然而，随着文本序列增长，KV缓存的内存占用显著增加，这对高效部署提出了挑战。现有方法在预填充阶段使用注意力分数来修剪标记，导致与实际推理查询不一致，尤其是在内存预算紧张时。本文提出了一种名为Lookahead Q-Cache (LAQ) 的新型替换框架，通过生成低成本的伪预览查询来更好地逼近真实的解码阶段查询。通过将这些预览查询作为重要性估计的观察窗口，LAQ实现了与实际推理场景更一致且准确的KV缓存替换。实验结果表明，LAQ在LongBench和Needle-in-a-Haystack基准测试中优于现有方法，在有限缓存预算下LongBench的性能提升了1~4个点。此外，LAQ与现有方法互补，可以灵活组合以进一步提升性能。

> Large language models (LLMs) rely on key-value cache (KV cache) to accelerate decoding by reducing redundant computations. However, the KV cache memory usage grows substantially with longer text sequences, posing challenges for efficient deployment. Existing KV cache eviction methods prune tokens using prefilling-stage attention scores, causing inconsistency with actual inference queries, especially under tight memory budgets. In this paper, we propose Lookahead Q-Cache (LAQ), a novel eviction framework that generates low-cost pseudo lookahead queries to better approximate the true decoding-stage queries. By using these lookahead queries as the observation window for importance estimation, LAQ achieves more consistent and accurate KV cache eviction aligned with real inference scenarios. Experimental results on LongBench and Needle-in-a-Haystack benchmarks show that LAQ outperforms existing methods across various budget levels, achieving a 1 $\sim$ 4 point improvement on LongBench under limited cache budget. Moreover, LAQ is complementary to existing approaches and can be flexibly combined to yield further improvements.

[Arxiv](https://arxiv.org/abs/2505.20334)