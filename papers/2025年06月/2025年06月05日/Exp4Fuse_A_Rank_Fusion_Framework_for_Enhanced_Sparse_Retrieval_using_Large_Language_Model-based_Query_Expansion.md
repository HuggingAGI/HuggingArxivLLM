# Exp4Fuse：基于大型语言模型的查询扩展增强稀疏检索的排序融合框架。

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了如何利用零样本LLM查询扩展来提升稀疏检索器的性能，特别是在信息检索领域。它提出了一种新的融合排序框架Exp4Fuse，并通过实验验证了其有效性。研究的重点是将LLM应用于实际任务中，属于LLM的应用层面。` `信息检索` `稀疏检索`

> Exp4Fuse: A Rank Fusion Framework for Enhanced Sparse Retrieval using Large Language Model-based Query Expansion

# 摘要

> 大型语言模型（LLMs）在生成假设性文档以增强信息检索方面展现出潜力，但其效果高度依赖于生成文档的质量，这通常需要复杂的提示策略和密集检索技术的结合，成本和计算量都较高。为了解决这一问题，我们探索了零样本LLM查询扩展在提升稀疏检索，特别是针对学习型稀疏检索器的应用。为此，我们提出了一种新型融合排序框架Exp4Fuse，通过间接应用零样本LLM查询扩展来增强稀疏检索器的性能。Exp4Fuse通过同时考虑两条检索路径——基于原始查询和基于LLM增强查询——生成两个排序列表，并通过修改后的倒数排名融合方法将它们融合。我们在三个与MS MARCO相关的数据集和七个低资源数据集上，将Exp4Fuse与领先LLM查询扩展方法和先进检索技术进行了全面对比。实验结果表明，Exp4Fuse不仅在提升稀疏检索器方面超越了现有LLM查询扩展方法，而且与先进稀疏检索器结合时，在多个基准测试中达到了最优性能。这充分证明了Exp4Fuse在提升稀疏检索查询扩展方面的卓越效果和高效性。

> Large Language Models (LLMs) have shown potential in generating hypothetical documents for query expansion, thereby enhancing information retrieval performance. However, the efficacy of this method is highly dependent on the quality of the generated documents, which often requires complex prompt strategies and the integration of advanced dense retrieval techniques. This can be both costly and computationally intensive. To mitigate these limitations, we explore the use of zero-shot LLM-based query expansion to improve sparse retrieval, particularly for learned sparse retrievers. We introduce a novel fusion ranking framework, Exp4Fuse, which enhances the performance of sparse retrievers through an indirect application of zero-shot LLM-based query expansion. Exp4Fuse operates by simultaneously considering two retrieval routes-one based on the original query and the other on the LLM-augmented query. It then generates two ranked lists using a sparse retriever and fuses them using a modified reciprocal rank fusion method. We conduct extensive evaluations of Exp4Fuse against leading LLM-based query expansion methods and advanced retrieval techniques on three MS MARCO-related datasets and seven low-resource datasets. Experimental results reveal that Exp4Fuse not only surpasses existing LLM-based query expansion methods in enhancing sparse retrievers but also, when combined with advanced sparse retrievers, achieves SOTA results on several benchmarks. This highlights the superior performance and effectiveness of Exp4Fuse in improving query expansion for sparse retrieval.

[Arxiv](https://arxiv.org/abs/2506.04760)