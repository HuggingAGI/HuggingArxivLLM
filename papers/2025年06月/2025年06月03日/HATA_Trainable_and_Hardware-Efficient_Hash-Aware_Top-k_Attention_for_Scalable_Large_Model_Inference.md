# HATA：用于可扩展大模型推理的可训练、硬件高效哈希感知 Top-k 注意力机制

发布时间：2025年06月03日

`LLM理论` `计算机科学`

> HATA: Trainable and Hardware-Efficient Hash-Aware Top-k Attention for Scalable Large Model Inference

# 摘要

> 大型语言模型（LLMs）已成为研究热点，但注意力模块仍是LLM推理的主要瓶颈，即使采用KVCache等技术优化。尽管基于注意力稀疏性的top-$k$注意力机制被提出以加速推理，但效率与准确性的平衡始终难以把握。本文提出HATA（Hash-Aware Top-$k$ Attention），一种创新方法，通过系统性地整合低开销哈希学习技术，优化Top-$k$注意力过程。与现有方法专注于高代价的qk分数绝对估计不同，HATA以低成本将查询和键映射为二进制哈希码，获取qk分数的相对顺序，从而高效实现top-k注意力。实验结果表明，HATA在保持模型准确性的同时，推理速度提升高达7.2倍。此外，HATA在多个主流LLM模型和多样化任务中，均优于现有先进top-$k$注意力方法，在准确性和效率上表现更优。HATA的开源代码可在GitHub上获取：https://github.com/gpzlx1/HATA。

> Large Language Models (LLMs) have emerged as a pivotal research area, yet the attention module remains a critical bottleneck in LLM inference, even with techniques like KVCache to mitigate redundant computations. While various top-$k$ attention mechanisms have been proposed to accelerate LLM inference by exploiting the inherent sparsity of attention, they often struggled to strike a balance between efficiency and accuracy. In this paper, we introduce HATA (Hash-Aware Top-$k$ Attention), a novel approach that systematically integrates low-overhead learning-to-hash techniques into the Top-$k$ attention process. Different from the existing top-k attention methods which are devoted to seeking an absolute estimation of qk score, typically with a great cost, HATA maps queries and keys into binary hash codes, and acquires the relative qk score order with a quite low cost, which is sufficient for realizing top-k attention. Extensive experiments demonstrate that HATA achieves up to 7.2$\times$ speedup compared to vanilla full attention while maintaining model accuracy. In addition, HATA outperforms the state-of-the-art top-$k$ attention methods in both accuracy and efficiency across multiple mainstream LLM models and diverse tasks. HATA is open source at https://github.com/gpzlx1/HATA.

[Arxiv](https://arxiv.org/abs/2506.02572)