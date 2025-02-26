# 彩票 LLM 假设：重新思考 LLM 压缩应保留哪些能力？

发布时间：2025年02月24日

`LLM理论

摘要讨论了模型压缩和键值缓存压缩，提出了彩票LLM假说，探讨了LLM的理论结构和性能优化，属于理论层面的研究。` `大型语言模型` `模型压缩`

> The Lottery LLM Hypothesis, Rethinking What Abilities Should LLM Compression Preserve?

# 摘要

> 为了降低大型语言模型 (LLMs) 的计算和存储成本，模型压缩和键值缓存压缩 (KV cache compression) 成为了研究热点。然而，当前方法主要关注于保持压缩后 LLM 的性能，通常通过在常识问答和基础算术推理等任务上的困惑度或简单准确率来衡量。在这篇博客中，我们将简要回顾与检索增强生成、多步推理、外部工具以及计算表达性相关的 LLM 近期进展，所有这些都极大地提升了 LLM 的性能。然后，我们提出了一种彩票 LLM 假说，认为对于给定的 LLM 和任务，存在一个更小的彩票 LLM，在多步推理和外部工具的帮助下，能够达到与原始 LLM 相同的性能。基于对当前 LLM 进展的回顾，我们讨论并总结了彩票 LLM 和 KV 缓存压缩必须具备的关键能力，这些能力在现有方法中尚未得到充分重视。

> Motivated by reducing the computational and storage costs of LLMs, model compression and KV cache compression have attracted much attention from researchers. However, current methods predominantly emphasize maintaining the performance of compressed LLMs, as measured by perplexity or simple accuracy on tasks of common sense knowledge QA and basic arithmetic reasoning. In this blog, we present a brief review of recent advancements in LLMs related to retrieval-augmented generation, multi-step reasoning, external tools, and computational expressivity, all of which substantially enhance LLM performance. Then, we propose a lottery LLM hypothesis suggesting that for a given LLM and task, there exists a smaller lottery LLM capable of producing the same performance as the original LLM with the assistance of multi-step reasoning and external tools. Based on the review of current progress in LLMs, we discuss and summarize the essential capabilities that the lottery LLM and KV cache compression must possess, which are currently overlooked in existing methods.

[Arxiv](https://arxiv.org/abs/2502.17535)