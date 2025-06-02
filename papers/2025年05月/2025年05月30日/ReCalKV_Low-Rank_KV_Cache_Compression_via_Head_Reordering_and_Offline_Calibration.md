# ReCalKV: 基于头部重排与离线校准的低秩KV缓存压缩技术

发布时间：2025年05月30日

`LLM应用

LLM应用

摘要内容主要讨论了大型语言模型（LLMs）在推理过程中KV缓存的压缩方法，以提高效率和性能。这属于LLM的应用优化，因此归类为LLM应用。` `模型优化` `计算效率`

> ReCalKV: Low-Rank KV Cache Compression via Head Reordering and Offline Calibration

# 摘要

> 大型语言模型（LLMs）虽然表现出色，但其长上下文推理能力常受限于 KV 缓存所需的庞大内存，因此 KV 缓存压缩成为实现高效推理的关键。近期研究通过降低 KV 缓存的隐藏维度来解决这一问题，但许多方法要么增加计算开销，要么在高压缩比下性能大幅下降。为此，我们提出了 ReCalKV，一种基于后训练的 KV 缓存压缩方法。根据 Keys 和 Values 在注意力机制中的不同作用，我们制定了针对性的压缩策略。对于 Keys，我们提出了基于头间相似性的分组重排方法（HSR），通过聚类相似注意力头并应用分组奇异值分解，减少计算开销同时保持精度。对于 Values，我们提出了离线校准和矩阵融合（OCMF），在不增加计算开销的情况下保持精度。实验表明，ReCalKV 在保持高性能的同时，实现了比现有低秩压缩方法更高的压缩比率。代码已开源：https://github.com/XIANGLONGYAN/ReCalKV.

> Large language models (LLMs) have achieved remarkable performance, yet their capability on long-context reasoning is often constrained by the excessive memory required to store the Key-Value (KV) cache. This makes KV cache compression an essential step toward enabling efficient long-context reasoning. Recent methods have explored reducing the hidden dimensions of the KV cache, but many introduce additional computation through projection layers or suffer from significant performance degradation under high compression ratios. To address these challenges, we propose ReCalKV, a post-training KV cache compression method that reduces the hidden dimensions of the KV cache. We develop distinct compression strategies for Keys and Values based on their different roles and varying importance in the attention mechanism. For Keys, we propose Head-wise Similarity-aware Reordering (HSR), which clusters similar heads and applies grouped SVD to the key projection matrix, reducing additional computation while preserving accuracy. For Values, we propose Offline Calibration and Matrix Fusion (OCMF) to preserve accuracy without extra computational overhead. Experiments show that ReCalKV outperforms existing low-rank compression methods, achieving high compression ratios with minimal performance loss. Code is available at: https://github.com/XIANGLONGYAN/ReCalKV.

[Arxiv](https://arxiv.org/abs/2505.24357)