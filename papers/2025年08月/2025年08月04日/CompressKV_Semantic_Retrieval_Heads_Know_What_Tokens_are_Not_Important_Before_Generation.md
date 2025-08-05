# CompressKV：语义检索头提前识别生成中不重要的token

发布时间：2025年08月04日

`LLM应用

理由：这篇论文探讨了如何优化大型语言模型（LLMs）中的KV缓存压缩方法，以解决长上下文处理带来的内存和效率挑战。它提出了一种创新的方法，通过识别不同注意力头的功能差异来优化缓存策略，从而提高模型性能。这直接涉及到了LLM的应用和优化，因此归类为LLM应用。` `计算机科学` `人工智能`

> CompressKV: Semantic Retrieval Heads Know What Tokens are Not Important Before Generation

# 摘要

> 近期，大型语言模型（LLMs）在长上下文处理方面取得了显著进展，但 KV 缓存规模的不断扩大也带来了内存和执行效率方面的严峻挑战。目前大多数 KV 缓存压缩方法依赖于基于分组查询注意力（GQA）的 LLM 中所有注意力头的启发式令牌移除策略，但这种方法忽略了不同注意力头的功能差异，导致关键令牌被移除，从而降低了 LLM 的性能。
    为了解决这一问题，我们提出了一种创新方法：不再像之前的工作那样使用 GQA 基础模型中所有注意力头来确定重要令牌，而是首先识别出每一层中不仅能够检索提示的初始和最终令牌，还能够检索文本中的重要令牌并关注其周围语义上下文的注意力头。随后，我们利用这些注意力头来确定重要令牌并保留其对应的 KV 缓存对。此外，我们对每一层的缓存移除错误进行单独分析，并引入了一种分层自适应的 KV 缓存分配策略。实验结果表明，在 LongBench 和 Needle-in-a-Haystack 基准测试中，提出的 CompressKV 方法在各种内存预算下始终优于现有最优方法。我们的代码已公开发布在：https://github.com/TUDa-HWAI/CompressKV.git。

> Recent advances in large language models (LLMs) have significantly boosted long-context processing. However, the increasing key-value (KV) cache size poses critical challenges to memory and execution efficiency. Most KV cache compression methods rely on heuristic token eviction using all attention heads in Grouped Query Attention (GQA)-based LLMs. This method ignores the different functionalities of attention heads, leading to the eviction of critical tokens and thus degrades the performance of LLMs.
  To address the issue above, instead of using all the attention heads in GQA-based LLMs to determine important tokens as in the previous work, we first identify the attention heads in each layer that are not only capable of retrieving the initial and final tokens of a prompt, but also capable of retrieving important tokens within the text and attending to their surrounding semantic context. Afterwards, we exploit such heads to determine the important tokens and retain their corresponding KV cache pairs. Furthermore, we analyze the cache eviction error of each layer individually and introduce a layer-adaptive KV cache allocation strategy. Experimental results demonstrate the proposed CompressKV consistently outperforms state-of-the-art approaches under various memory budgets on LongBench and Needle-in-a-Haystack benchmarks. Our code is publicly available at: https://github.com/TUDa-HWAI/CompressKV.git.

[Arxiv](https://arxiv.org/abs/2508.02401)