# 优化RAG系统中嵌入存储的方案，采用量化和降维技术

发布时间：2025年04月30日

`RAG` `信息检索` `数据处理`

> Optimization of embeddings storage for RAG systems using quantization and dimensionality reduction techniques

# 摘要

> 检索增强生成通过从外部知识库中检索相关信息来提升语言模型性能，依赖于高维向量嵌入，这些嵌入通常以float32精度存储。然而，大规模存储这些嵌入带来了显著的内存挑战。为了解决这一问题，我们在MTEB基准测试上系统性地研究了两种互补的优化策略：量化，评估标准格式（float16、int8、二进制）和低精度浮点类型（float8），以及降维，评估PCA、核PCA、UMAP、随机投影和自编码器等方法。结果显示，float8量化在性能下降极小（<0.3%）的情况下实现了4倍的存储压缩，显著优于同压缩比下的int8量化，且实现更简单。PCA脱颖而出成为最有效的降维技术。至关重要的是，将中等程度的PCA（例如保留50%维度）与float8量化结合使用，提供了极佳的压缩性能平衡，实现8倍总压缩率，相较于单独使用int8（仅提供4倍压缩）对性能的影响更小。为了促进实际应用，我们提出了一种基于可视化性能-存储权衡空间的方法，以识别在特定内存约束下性能最优的配置。

> Retrieval-Augmented Generation enhances language models by retrieving relevant information from external knowledge bases, relying on high-dimensional vector embeddings typically stored in float32 precision. However, storing these embeddings at scale presents significant memory challenges. To address this issue, we systematically investigate on MTEB benchmark two complementary optimization strategies: quantization, evaluating standard formats (float16, int8, binary) and low-bit floating-point types (float8), and dimensionality reduction, assessing methods like PCA, Kernel PCA, UMAP, Random Projections and Autoencoders. Our results show that float8 quantization achieves a 4x storage reduction with minimal performance degradation (<0.3%), significantly outperforming int8 quantization at the same compression level, being simpler to implement. PCA emerges as the most effective dimensionality reduction technique. Crucially, combining moderate PCA (e.g., retaining 50% dimensions) with float8 quantization offers an excellent trade-off, achieving 8x total compression with less performance impact than using int8 alone (which provides only 4x compression). To facilitate practical application, we propose a methodology based on visualizing the performance-storage trade-off space to identify the optimal configuration that maximizes performance within their specific memory constraints.

[Arxiv](https://arxiv.org/abs/2505.00105)