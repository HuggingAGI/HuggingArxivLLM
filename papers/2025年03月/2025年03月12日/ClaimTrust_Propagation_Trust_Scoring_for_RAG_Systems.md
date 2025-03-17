# ClaimTrust：为 RAG 系统设计的传播信任评分机制

发布时间：2025年03月12日

`RAG` `图计算`

> ClaimTrust: Propagation Trust Scoring for RAG Systems

# 摘要

> 检索增强生成（RAG）系统的广泛应用彻底改变了大规模内容生成，同时也带来了如何确保检索信息可信性的挑战。本文提出了一种名为 ClaimTrust 的基于传播的置信度评分框架，用于动态评估 RAG 系统中文档的可靠性。ClaimTrust 采用一种基于 PageRank 的启发式算法，通过从提取的事实声明中推导出的关系，在文档之间传播置信度分数。我们对 Kaggle 的虚假新闻检测数据集中 814 篇政治新闻文章进行了预处理和分析，从中提取了 2,173 个唯一声明，并分类了 965 个有意义的关系（支持或矛盾）。通过将数据集表示为文档图，ClaimTrust 迭代更新置信度分数直至收敛，从而有效区分可信文章与不可靠文章。我们的方法利用基于嵌入的过滤器进行高效的声明比较和关系分类，在保持计算可扩展性的同时实现了 11.2% 的显著连接。实验结果表明，ClaimTrust 成功为经过验证的文档分配了更高的置信度分数，同时对包含虚假信息的文档进行了惩罚。未来的研究方向包括优化声明提取和比较（Li 等人，2022）、参数优化、增强语言模型的利用以及鲁棒的评估指标，以实现跨不同数据集和领域的框架泛化。

> The rapid adoption of retrieval-augmented generation (RAG) systems has revolutionized large-scale content generation but has also highlighted the challenge of ensuring trustworthiness in retrieved information. This paper introduces ClaimTrust, a propagation-based trust scoring framework that dynamically evaluates the reliability of documents in a RAG system. Using a modified PageRank-inspired algorithm, ClaimTrust propagates trust scores across documents based on relationships derived from extracted factual claims. We preprocess and analyze 814 political news articles from Kaggle's Fake News Detection Dataset to extract 2,173 unique claims and classify 965 meaningful relationships (supporting or contradicting). By representing the dataset as a document graph, ClaimTrust iteratively updates trust scores until convergence, effectively differentiating trustworthy articles from unreliable ones. Our methodology, which leverages embedding-based filtering for efficient claim comparison and relationship classification, achieves a 11.2% of significant connections while maintaining computational scalability. Experimental results demonstrate that ClaimTrust successfully assigns higher trust scores to verified documents while penalizing those containing false information. Future directions include fine-tuned claim extract and compare (Li et al., 2022), parameter optimization, enhanced language model utilization, and robust evaluation metrics to generalize the framework across diverse datasets and domains.

[Arxiv](https://arxiv.org/abs/2503.10702)