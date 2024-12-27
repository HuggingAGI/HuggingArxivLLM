# 是全注意力的神奇妙方还是无奈妥协？有关基于要点标记的上下文压缩的全面研究

发布时间：2024年12月23日

`LLM应用` `大型语言模型`

> A Silver Bullet or a Compromise for Full Attention? A Comprehensive Study of Gist Token-based Context Compression

# 摘要

> 在这项工作中，我们深入探究了基于要点的上下文压缩方法，旨在提升大型语言模型处理长上下文的能力。我们聚焦于两个关键问题：其一，这些方法在多大程度上能够取代全注意力模型？其二，压缩会引发哪些潜在的失败模式？通过大量实验，我们发现，基于要点的压缩在检索增强生成和长文档问答等任务中能实现近乎无损的性能，但在合成召回等任务中却面临挑战。此外，我们还明确了三种关键的失败模式，即边界丢失、意外丢失和途中丢失。为了缓解这些问题，我们提出了两项有效的策略：细粒度自动编码，可增强原始标记信息的重建；分段标记重要性估计，能依据标记依赖关系调整优化。我们的工作为理解基于要点标记的上下文压缩提供了宝贵的见解，并为提升压缩能力给出了实用的策略。

> In this work, we provide a thorough investigation of gist-based context compression methods to improve long-context processing in large language models. We focus on two key questions: (1) How well can these methods replace full attention models? and (2) What potential failure patterns arise due to compression? Through extensive experiments, we show that while gist-based compression can achieve near-lossless performance on tasks like retrieval-augmented generation and long-document QA, it faces challenges in tasks like synthetic recall. Furthermore, we identify three key failure patterns: lost by the boundary, lost if surprise, and lost along the way. To mitigate these issues, we propose two effective strategies: fine-grained autoencoding, which enhances the reconstruction of original token information, and segment-wise token importance estimation, which adjusts optimization based on token dependencies. Our work provides valuable insights into the understanding of gist token-based context compression and offers practical strategies for improving compression capabilities.

[Arxiv](https://arxiv.org/abs/2412.17483)