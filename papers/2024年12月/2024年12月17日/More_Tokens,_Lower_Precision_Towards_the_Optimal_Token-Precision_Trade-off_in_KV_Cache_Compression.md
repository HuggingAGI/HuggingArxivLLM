# 更多令牌，更低精度：探索 KV 缓存压缩中的最优令牌与精度的权衡

发布时间：2024年12月17日

`LLM应用` `语言模型` `缓存压缩`

> More Tokens, Lower Precision: Towards the Optimal Token-Precision Trade-off in KV Cache Compression

# 摘要

> 随着大型语言模型（LLMs）处理的上下文窗口持续增多，KV 缓存的内存使用已然成为推理时的关键瓶颈。主流的 KV 压缩手段，像 KV 剪枝和 KV 量化，主要着眼于令牌或者精度维度，很少探究它们组合的效率。在本文里，我们全方位研究了 KV 缓存压缩中的令牌-精度权衡。实验证明，在 KV 缓存中以较低精度存储更多令牌，也就是量化剪枝，能够大幅提升 LLMs 的长上下文性能。另外，从一系列关键方面针对令牌-精度权衡展开的深入分析显示，量化剪枝在检索相关任务中实现了显著改进，并且在不同的输入长度下都表现出色。而且，量化剪枝在不同的 KV 剪枝方法、量化策略和模型规模中展现出了显著的稳定性。这些发现为 KV 缓存压缩中的令牌-精度权衡提供了宝贵的见解。我们打算在近期发布我们的代码。

> As large language models (LLMs) process increasing context windows, the memory usage of KV cache has become a critical bottleneck during inference. The mainstream KV compression methods, including KV pruning and KV quantization, primarily focus on either token or precision dimension and seldom explore the efficiency of their combination. In this paper, we comprehensively investigate the token-precision trade-off in KV cache compression. Experiments demonstrate that storing more tokens in the KV cache with lower precision, i.e., quantized pruning, can significantly enhance the long-context performance of LLMs. Furthermore, in-depth analysis regarding token-precision trade-off from a series of key aspects exhibit that, quantized pruning achieves substantial improvements in retrieval-related tasks and consistently performs well across varying input lengths. Moreover, quantized pruning demonstrates notable stability across different KV pruning methods, quantization strategies, and model scales. These findings provide valuable insights into the token-precision trade-off in KV cache compression. We plan to release our code in the near future.

[Arxiv](https://arxiv.org/abs/2412.12706)