# EFIM：提升LLM填充任务服务效率，优化键值缓存复用技术

发布时间：2025年05月27日

`LLM应用` `性能优化`

> EFIM: Efficient Serving of LLMs for Infilling Tasks with Improved KV Cache Reuse

# 摘要

> 大型语言模型 (LLMs) 在文本补全任务中发挥着重要作用，这类任务需要多次与相似上下文交互，以预测或生成缺失信息。为减少重复计算，跨请求键值 (KV) 缓存复用技术成为多轮交互服务的关键方法。然而，在文本补全任务中，KV 缓存复用受限于提示格式的结构，通常由前缀和后缀组成。随着另一部分的逐步生成，前缀或后缀的 KV 缓存常被无效化。为解决此问题，我们提出了 EFIM，一种 FIM 的转换提示格式，释放 KV 缓存复用的性能潜力。尽管转换后的提示解决了低效问题，却暴露了当前 LLMs 中的子词生成难题。因此，我们引入了分段分词训练方法，在数据处理阶段将文本拆分为多个片段后再进行分词。实验表明，采用 EFIM 的 LLM 服务可将延迟降低 52%，吞吐量提升 98%，同时保持原有补全能力。EFIM 的源代码可在 https://github.com/gty111/EFIM 获取。

> Large language models (LLMs) are often used for infilling tasks, which involve predicting or generating missing information in a given text. These tasks typically require multiple interactions with similar context. To reduce the computation of repeated historical tokens, cross-request key-value (KV) cache reuse, a technique that stores and reuses intermediate computations, has become a crucial method in multi-round interactive services. However, in infilling tasks, the KV cache reuse is often hindered by the structure of the prompt format, which typically consists of a prefix and suffix relative to the insertion point. Specifically, the KV cache of the prefix or suffix part is frequently invalidated as the other part (suffix or prefix) is incrementally generated. To address the issue, we propose EFIM, a transformed prompt format of FIM to unleash the performance potential of KV cache reuse. Although the transformed prompt can solve the inefficiency, it exposes subtoken generation problems in current LLMs, where they have difficulty generating partial words accurately. Therefore, we introduce a fragment tokenization training method which splits text into multiple fragments before tokenization during data processing. Experiments on two representative LLMs show that LLM serving with EFIM can lower the latency by 52% and improve the throughput by 98% while maintaining the original infilling capability.EFIM's source code is publicly available at https://github.com/gty111/EFIM.

[Arxiv](https://arxiv.org/abs/2505.21889)