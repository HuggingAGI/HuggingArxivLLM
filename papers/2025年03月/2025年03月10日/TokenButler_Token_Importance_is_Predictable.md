# TokenButler：Token重要性预测无误

发布时间：2025年03月10日

`LLM应用` `人工智能`

> TokenButler: Token Importance is Predictable

# 摘要

> 大型语言模型 (LLMs) 依赖键值缓存 (KV Cache) 来存储标记历史记录，支持高效的解码过程。然而，随着 KV 缓存规模增长，它成为了内存和计算的主要瓶颈。但好消息是，我们有机会缓解这一问题，因为研究表明，每个解码步骤中只有少数标记真正重要。寻找这些关键标记的难点在于它们是动态变化的，且高度依赖输入查询。现有的方法要么通过永久移除标记来冒险影响质量，要么保留完整 KV 缓存但在生成时依赖检索标记块（页面），这在处理密集且上下文丰富的任务时表现不佳。此外，许多现有的 KV 缓存稀疏性方法依赖于不准确的标记重要性替代指标。为了解决这些问题，我们推出了 TokenButler，这是一种高粒度且感知查询的预测器，能够学习识别这些关键标记。通过使用参数开销不到 1.2% 的轻量级预测器进行训练，TokenButler 根据标记的上下文预测重要性对其进行优先排序。这使得困惑度和下游准确性相对于最先进的标记重要性估计方法提高了 8% 以上。我们在一个新颖的合成小上下文共指检索任务上评估了 TokenButler，展示了接近 oracle 的准确性。代码、模型和基准测试：https://github.com/abdelfattah-lab/TokenButler

> Large Language Models (LLMs) rely on the Key-Value (KV) Cache to store token history, enabling efficient decoding of tokens. As the KV-Cache grows, it becomes a major memory and computation bottleneck, however, there is an opportunity to alleviate this bottleneck, especially because prior research has shown that only a small subset of tokens contribute meaningfully to each decoding step. A key challenge in finding these critical tokens is that they are dynamic, and heavily input query-dependent. Existing methods either risk quality by evicting tokens permanently, or retain the full KV-Cache but rely on retrieving chunks (pages) of tokens at generation, failing at dense, context-rich tasks. Additionally, many existing KV-Cache sparsity methods rely on inaccurate proxies for token importance. To address these limitations, we introduce TokenButler, a high-granularity, query-aware predictor that learns to identify these critical tokens. By training a light-weight predictor with less than 1.2% parameter overhead, TokenButler prioritizes tokens based on their contextual, predicted importance. This improves perplexity & downstream accuracy by over 8% relative to SoTA methods for estimating token importance. We evaluate TokenButler on a novel synthetic small-context co-referential retrieval task, demonstrating near-oracle accuracy. Code, models and benchmarks: https://github.com/abdelfattah-lab/TokenButler

[Arxiv](https://arxiv.org/abs/2503.07518)