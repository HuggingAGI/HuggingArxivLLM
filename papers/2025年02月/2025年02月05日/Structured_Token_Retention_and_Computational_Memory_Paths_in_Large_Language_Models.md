# 大型语言模型中的结构化令牌保留与计算记忆路径

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要讨论了记忆保留机制在扩展序列处理中的重要性，并提出了结构化令牌保留（STR）和计算记忆路径（CMP）两种方法来优化内存利用和信息检索效率。这些方法涉及到大型语言模型（LLM）的内部机制和理论改进，特别是关于如何处理长序列和优化计算资源的使用。因此，这篇论文更适合归类为“LLM理论”，因为它主要关注的是LLM的理论基础和内部机制的改进。` `序列建模`

> Structured Token Retention and Computational Memory Paths in Large Language Models

# 摘要

> # 摘要
记忆保留机制在扩展序列处理的计算架构中至关重要。传统方法常采用固定保留阈值或均匀注意力权重分布，导致内存利用低效和信息过早丢失。结构化令牌保留（STR）通过动态调整令牌持久性，确保计算资源集中于语义相关元素。计算记忆路径（CMP）则通过分层内存分配进一步提升效率。与基线模型相比，STR和CMP显著提高了长序列中的令牌存活率，减少了误差传播。实验表明，计算开销降低，推理速度提升，且上下文一致性不受影响。令牌分布分析显示，结构化内存分配优化了信息检索效率。STR和CMP在开源模型中的应用展示了其在生成文本处理、长上下文理解和可扩展序列建模中的广泛适用性。

> Memory retention mechanisms play a central role in determining the efficiency of computational architectures designed for processing extended sequences. Conventional methods for token management often impose fixed retention thresholds or rely on uniform attention weight distributions, leading to inefficient memory utilization and premature information loss in extended sequence modeling. Structured Token Retention (STR) introduces a probabilistic selection framework that dynamically adjusts token persistence based on contextual significance, ensuring that computational resources are allocated to semantically relevant elements. Computational Memory Paths (CMP) extend this framework through hierarchical memory allocation, refining retention efficiency through structured reallocation of token embeddings. Comparative assessments against baseline models demonstrate that STR and CMP improve token survival rates across long input sequences while reducing cumulative error propagation across processing layers. Experimental results further indicate reductions in computational overhead, improving inference speed without degrading contextual coherence. Token distribution analyses reveal that structured memory allocation prevents excessive redundancy in attention weight calculations, optimizing information retrieval efficiency in large-scale generative architectures. The integration of STR and CMP into an open-source model illustrates the adaptability of structured memory retention methodologies, highlighting their applicability in generative text processing, long-context comprehension, and scalable sequence modeling.

[Arxiv](https://arxiv.org/abs/2502.03102)