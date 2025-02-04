# Pivoting Factorization: 一种用于大型语言模型高效推理的紧凑元低秩稀疏表示

发布时间：2025年01月31日

`LLM理论

**理由**：这篇论文主要讨论了大型语言模型的压缩技术，特别是低秩剪枝方法及其改进。它涉及模型的理论优化和性能提升，属于对LLM内部机制和效率的研究，因此归类为“LLM理论”。` `模型压缩`

> Pivoting Factorization: A Compact Meta Low-Rank Representation of Sparsity for Efficient Inference in Large Language Models

# 摘要

> 大型语言模型的迅猛发展催生了对高效模型压缩技术的需求，以降低内存和计算开销。低秩剪枝因其张量一致性和全密度下的GPU兼容性备受瞩目。然而，低秩剪枝在性能上往往难以匹敌半结构化剪枝，相似密度下困惑度（PPL）常翻倍。本文提出Pivoting Factorization（PIFA），一种创新的无损元低秩表示方法，通过无监督学习生成紧凑的低秩表示，有效剔除冗余信息。PIFA识别枢轴行（线性独立行），并将非枢轴行表达为线性组合，在r/d = 0.5时，内存节省24.2%，推理速度提升24.6%，显著提升相同密度下的性能。为缓解低秩剪枝的性能损失，我们提出了一种无需重新训练的低秩重建方法，最小化误差累积（M）。MPIFA将M与PIFA结合为端到端框架，大幅超越现有低秩剪枝方法，首次实现与半结构化剪枝相当的性能，并在GPU效率和兼容性上更胜一筹。

> The rapid growth of Large Language Models has driven demand for effective model compression techniques to reduce memory and computation costs. Low-rank pruning has gained attention for its tensor coherence and GPU compatibility across all densities. However, low-rank pruning has struggled to match the performance of semi-structured pruning, often doubling perplexity (PPL) at similar densities. In this paper, we propose Pivoting Factorization (PIFA), a novel lossless meta low-rank representation that unsupervisedly learns a compact form of any low-rank representation, effectively eliminating redundant information. PIFA identifies pivot rows (linearly independent rows) and expresses non-pivot rows as linear combinations, achieving an additional 24.2\% memory savings and 24.6\% faster inference over low-rank layers at r/d = 0.5, thereby significantly enhancing performance at the same density. To mitigate the performance degradation caused by low-rank pruning, we introduce a novel, retraining-free low-rank reconstruction method that minimizes error accumulation (M). MPIFA, combining M and PIFA into an end-to-end framework, significantly outperforms existing low-rank pruning methods and, for the first time, achieves performance comparable to semi-structured pruning, while surpassing it in GPU efficiency and compatibility.

[Arxiv](https://arxiv.org/abs/2501.19090)