# Judge Decoding: 加速推测采样，超越模型对齐

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的推理速度问题，并提出了一种新的推测解码技术来加速自回归生成。论文的核心在于理论上的创新，即通过调整验证机制来识别正确但未对齐的回复，并展示了LLMs在评估答案方面的能力。这些内容主要涉及LLM的理论研究和优化方法，因此归类为“LLM理论”。` `推理加速`

> Judge Decoding: Faster Speculative Sampling Requires Going Beyond Model Alignment

# 摘要

> 大型语言模型（LLMs）的性能与其规模密切相关，网络规模的增长导致推理速度变慢。推测解码技术通过快速草稿模型提出候选标记，并在目标模型下并行验证这些标记，以加速自回归生成。然而，这种方法虽然能保证目标输出的再现，却带来了显著的代价：许多高质量的草稿标记被拒绝，即使它们是有效的延续。我们展示了即使是GPT-4o这样的强大草稿模型和人类文本，在标准验证方案下也难以实现高接受率，这严重限制了当前推测解码方法的速度提升潜力。因此，我们提出了一个问题：能否调整验证机制以识别正确但未对齐的回复？为此，我们借鉴了LLM-as-a-judge框架，展示了LLMs能够以多种方式评估答案。我们设计了一个数据集，通过在嵌入之上训练一个紧凑模块来产生当前延续的“判断”，从而在目标模型中激发相同的能力。我们在Llama-3.1系列上展示了这一策略，其中8b/405B-Judge在Llama-405B上实现了9倍的加速，同时在大量基准测试中保持了质量。这些优势在优化的推理框架中依然存在，我们的方法在2和8个H100上分别达到了141 tokens/s和129 tokens/s的速度。

> The performance of large language models (LLMs) is closely linked to their underlying size, leading to ever-growing networks and hence slower inference. Speculative decoding has been proposed as a technique to accelerate autoregressive generation, leveraging a fast draft model to propose candidate tokens, which are then verified in parallel based on their likelihood under the target model. While this approach guarantees to reproduce the target output, it incurs a substantial penalty: many high-quality draft tokens are rejected, even when they represent objectively valid continuations. Indeed, we show that even powerful draft models such as GPT-4o, as well as human text cannot achieve high acceptance rates under the standard verification scheme. This severely limits the speedup potential of current speculative decoding methods, as an early rejection becomes overwhelmingly likely when solely relying on alignment of draft and target.
  We thus ask the following question: Can we adapt verification to recognize correct, but non-aligned replies? To this end, we draw inspiration from the LLM-as-a-judge framework, which demonstrated that LLMs are able to rate answers in a versatile way. We carefully design a dataset to elicit the same capability in the target model by training a compact module on top of the embeddings to produce ``judgements" of the current continuation. We showcase our strategy on the Llama-3.1 family, where our 8b/405B-Judge achieves a speedup of 9x over Llama-405B, while maintaining its quality on a large range of benchmarks. These benefits remain present even in optimized inference frameworks, where our method reaches up to 141 tokens/s for 8B/70B-Judge and 129 tokens/s for 8B/405B on 2 and 8 H100s respectively.

[Arxiv](https://arxiv.org/abs/2501.19309)