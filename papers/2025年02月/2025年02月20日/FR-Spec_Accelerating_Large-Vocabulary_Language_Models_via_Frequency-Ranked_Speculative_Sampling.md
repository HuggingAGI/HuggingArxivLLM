# FR-Spec：基于频率排序的推测采样加速大词汇量语言模型

FR-Spec 提出了一种创新的频率排序推测采样方法，旨在加速大词汇量语言模型的运行效率。通过分析词汇频率分布，FR-Spec 能够更高效地进行推测采样，从而在保持高准确性的同时显著提升模型推理速度。实验结果表明，FR-Spec 在多种大规模语言模型上均实现了显著的加速效果。

发布时间：2025年02月20日

`LLM应用`

> FR-Spec: Accelerating Large-Vocabulary Language Models via Frequency-Ranked Speculative Sampling

# 摘要

> 推测采样已成为加速大型语言模型自回归生成的关键技术，其通过草稿-验证机制实现每个前向传递生成多标记。尽管现有先进方法采用单层和LM头作为草稿模型实现了显著的层压缩，但其效率提升在大词汇量模型（如Llama-3-8B，128k标记）上大幅下降。为此，我们提出FR-Spec，一种基于频率排序的推测采样框架，通过词汇空间压缩优化候选选择。通过将草稿搜索限定在频率优先的标记子集，我们的方法将LM头计算开销减少75%，同时保持输出分布等效。实验结果显示，与EAGLE-2相比，FR-Spec实现了平均1.12×的加速。

> Speculative sampling has emerged as an important technique for accelerating the auto-regressive generation process of large language models (LLMs) by utilizing a draft-then-verify mechanism to produce multiple tokens per forward pass. While state-of-the-art speculative sampling methods use only a single layer and a language modeling (LM) head as the draft model to achieve impressive layer compression, their efficiency gains are substantially reduced for large-vocabulary LLMs, such as Llama-3-8B with a vocabulary of 128k tokens. To address this, we present FR-Spec, a frequency-ranked speculative sampling framework that optimizes draft candidate selection through vocabulary space compression. By constraining the draft search to a frequency-prioritized token subset, our method reduces LM Head computation overhead by 75% while ensuring the equivalence of the final output distribution. Experiments across multiple datasets demonstrate an average of 1.12$\times$ speedup over the state-of-the-art speculative sampling method EAGLE-2.

[Arxiv](https://arxiv.org/abs/2502.14856)