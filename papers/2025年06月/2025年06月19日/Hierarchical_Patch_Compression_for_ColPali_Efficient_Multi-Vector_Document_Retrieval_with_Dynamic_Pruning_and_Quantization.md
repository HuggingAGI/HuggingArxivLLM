# ColPali的层次化块压缩：动态剪枝与量化驱动的高效多向量文档检索

发布时间：2025年06月19日

`其他` `文档检索`

> Hierarchical Patch Compression for ColPali: Efficient Multi-Vector Document Retrieval with Dynamic Pruning and Quantization

# 摘要

> 多向量文档检索系统（如ColPali）在复杂查询的细粒度匹配方面表现出色，但因其依赖高维补丁嵌入和晚期交互评分，导致存储和计算成本显著增加。为了解决这些挑战，我们提出了HPC-ColPali，这是一种分层补丁压缩框架，旨在提升ColPali的效率，同时保持其检索精度。

我们的方法整合了三项创新技术：
1. K-Means量化：将补丁嵌入压缩为1字节的质心索引，实现最高32×的存储缩减；
2. 注意力引导的动态剪枝：利用视觉-语言模型的注意力权重，仅保留最显著的前p%补丁，将晚期交互计算减少高达60%，同时nDCG@10损失低于2%；
3. 可选的质心索引二进制编码为b位字符串（b=⌈log₂K⌉），支持资源受限环境下的快速汉明距离相似性搜索。

在ViDoRe和SEC-Filings数据集上的评估显示，HPC-ColPali在HNSW索引下实现了30--50%的查询延迟降低，同时保持了高检索精度。将其集成到法律摘要的检索增强生成流水线中，可将幻觉率降低30%，并将端到端延迟减半。这些进展确立了HPC-ColPali作为多向量文档检索在各类应用中可扩展且高效的解决方案。代码可在https://github.com/DngBack/HPC-ColPali获取。

> Multi-vector document retrieval systems, such as ColPali, excel in fine-grained matching for complex queries but incur significant storage and computational costs due to their reliance on high-dimensional patch embeddings and late-interaction scoring. To address these challenges, we propose HPC-ColPali, a Hierarchical Patch Compression framework that enhances the efficiency of ColPali while preserving its retrieval accuracy. Our approach integrates three innovative techniques: (1) K-Means quantization, which compresses patch embeddings into 1-byte centroid indices, achieving up to 32$\times$ storage reduction; (2) attention-guided dynamic pruning, utilizing Vision-Language Model attention weights to retain only the top-$p\%$ most salient patches, reducing late-interaction computation by up to 60\% with less than 2\% nDCG@10 loss; and (3) optional binary encoding of centroid indices into $b$-bit strings ($b=\lceil\log_2 K\rceil$), enabling rapid Hamming distance-based similarity search for resource-constrained environments. Evaluated on the ViDoRe and SEC-Filings datasets, HPC-ColPali achieves 30--50\% lower query latency under HNSW indexing while maintaining high retrieval precision. When integrated into a Retrieval-Augmented Generation pipeline for legal summarization, it reduces hallucination rates by 30\% and halves end-to-end latency. These advancements establish HPC-ColPali as a scalable and efficient solution for multi-vector document retrieval across diverse applications. Code is available at https://github.com/DngBack/HPC-ColPali.

[Arxiv](https://arxiv.org/abs/2506.21601)