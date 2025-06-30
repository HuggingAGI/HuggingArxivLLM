# # JointRank：大规模集合排序，一次遍历搞定

发布时间：2025年06月27日

`其他` `信息检索` `推荐系统`

> JointRank: Rank Large Set with Single Pass

# 摘要

> 从大型候选池中高效排序相关项目是现代信息检索系统的核心——例如网络搜索、推荐和检索增强生成。列表重排器通过同时考虑多个候选项目来提高相关性，但在实践中往往受到限制：要么是模型输入大小的限制，要么是在处理大规模集合时质量下降。我们提出了一种用于快速重排超出模型输入限制的大规模集合的模型不可知方法。该方法首先将候选项目划分为重叠的块，每个块独立并行排名。然后从这些局部排名中推导出隐式成对比较。最后，使用Winrate或PageRank等算法将这些比较聚合以构建全局排名。在TREC DL-2019上的实验表明，我们的方法在使用gpt-4.1-mini作为长上下文模型时，nDCG@10达到70.88，而全上下文列表方法为57.68，同时将延迟从21秒减少到8秒。该算法的实现和实验可在以下仓库中找到：https://github.com/V3RGANz/jointrank

> Efficiently ranking relevant items from large candidate pools is a cornerstone of modern information retrieval systems -- such as web search, recommendation, and retrieval-augmented generation. Listwise rerankers, which improve relevance by jointly considering multiple candidates, are often limited in practice: either by model input size constraints, or by degraded quality when processing large sets. We propose a model-agnostic method for fast reranking large sets that exceed a model input limits. The method first partitions candidate items into overlapping blocks, each of which is ranked independently in parallel. Implicit pairwise comparisons are then derived from these local rankings. Finally, these comparisons are aggregated to construct a global ranking using algorithms such as Winrate or PageRank. Experiments on TREC DL-2019 show that our method achieves an nDCG@10 of 70.88 compared to the 57.68 for full-context listwise approach using gpt-4.1-mini as long-context model, while reducing latency from 21 to 8 seconds.
  The implementation of the algorithm and the experiments is available in the repository: https://github.com/V3RGANz/jointrank

[Arxiv](https://arxiv.org/abs/2506.22262)