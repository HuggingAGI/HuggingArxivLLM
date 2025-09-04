# HF-RAG：基于分层融合的多源多排序器检索增强生成（RAG）

发布时间：2025年09月02日

`RAG` `基础理论`

> HF-RAG: Hierarchical Fusion-based RAG with Multiple Sources and Rankers

# 摘要

> 在检索增强生成（RAG）中，同时利用标记数据（输入-输出关联）与未标记数据（更广泛的上下文背景）有望带来互补优势。然而，由于不同来源的相似度分数无法直接比较，有效融合这些异构数据的证据颇具挑战。此外，通过聚合多个排序器输出的置信度，能够进一步提升RAG的效果。我们提出的方法首先针对标记和未标记两种来源，采用标准排序融合技术聚合多个信息检索（IR）模型返回的顶级文档；随后，在合并两个来源的顶级检索文档前，通过z分数转换对各来源内的检索分数分布进行标准化处理。在事实核查任务上的评估结果显示，该方法不仅持续优于性能最佳的单个排序器或数据源，还具备更强的域外泛化能力。

> Leveraging both labeled (input-output associations) and unlabeled data (wider contextual grounding) may provide complementary benefits in retrieval augmented generation (RAG). However, effectively combining evidence from these heterogeneous sources is challenging as the respective similarity scores are not inter-comparable. Additionally, aggregating beliefs from the outputs of multiple rankers can improve the effectiveness of RAG. Our proposed method first aggregates the top-documents from a number of IR models using a standard rank fusion technique for each source (labeled and unlabeled). Next, we standardize the retrieval score distributions within each source by applying z-score transformation before merging the top-retrieved documents from the two sources. We evaluate our approach on the fact verification task, demonstrating that it consistently improves over the best-performing individual ranker or source and also shows better out-of-domain generalization.

[Arxiv](https://arxiv.org/abs/2509.02837)