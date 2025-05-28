# SpecExtend：针对长序列推测解码的即插即用增强方法

发布时间：2025年05月27日

`LLM应用

摘要讨论了Speculative decoding技术在加速大型语言模型推理中的应用，提出了SpecExtend工具来优化长序列的处理。这属于对LLM应用的优化和改进，因此归类为LLM应用。` `计算效率`

> SpecExtend: A Drop-in Enhancement for Speculative Decoding of Long Sequences

# 摘要

> Speculative decoding 是一种广泛用于加速大型语言模型 (LLMs) 推理的技术，但其在处理长输入时会因注意力成本增加和草稿准确性降低而导致性能下降。我们推出了 SpecExtend，一个无需额外训练的即插即用增强工具，旨在提升长序列上 Speculative decoding 的性能。SpecExtend 在草稿和目标模型中集成了高效的注意力机制（如 FlashAttention 和 Hybrid Tree Attention），从而降低所有阶段的延迟。为了进一步提高草稿的准确性和速度，我们提出了 Cross-model Retrieval，这是一种新型 KV 缓存更新策略，利用目标模型的注意力分数动态选择与草稿模型相关的上下文。在三个长上下文理解数据集上的广泛评估表明，SpecExtend 能够将标准树形推测解码加速 2.22 倍，适用于长达 16K 个令牌的输入，为长序列的推测解码提供了一个有效的解决方案。代码可在 https://github.com/jycha98/SpecExtend 获取。

> Speculative decoding is a widely adopted technique for accelerating inference in large language models (LLMs), but its performance degrades on long inputs due to increased attention cost and reduced draft accuracy. We introduce SpecExtend, a drop-in enhancement that improves the performance of speculative decoding on long sequences without any additional training. SpecExtend integrates efficient attention mechanisms such as FlashAttention and Hybrid Tree Attention into both the draft and target models, reducing latency across all stages. To improve draft accuracy and speed, we propose Cross-model Retrieval, a novel KV cache update strategy that uses the target model's attention scores to dynamically select relevant context for the draft model. Extensive evaluations on three long-context understanding datasets show that SpecExtend accelerates standard tree-based speculative decoding by up to 2.22x for inputs up to 16K tokens, providing an effective solution for speculative decoding of long sequences. The code is available at https://github.com/jycha98/SpecExtend .

[Arxiv](https://arxiv.org/abs/2505.20776)