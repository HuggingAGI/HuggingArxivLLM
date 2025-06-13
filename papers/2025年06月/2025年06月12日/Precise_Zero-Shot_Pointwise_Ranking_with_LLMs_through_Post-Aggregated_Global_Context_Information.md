# 借助大型语言模型，通过全局上下文信息的后聚合处理实现精确零样本排序

发布时间：2025年06月12日

`LLM应用` `信息检索` `文档排序`

> Precise Zero-Shot Pointwise Ranking with LLMs through Post-Aggregated Global Context Information

# 摘要

> 最近的研究成功利用大型语言模型（LLMs）实现了零样本文档排序，并探索了多种提示策略。比较式方法，如成对比较和列表比较，虽然表现出色，但计算开销巨大，因此在大规模应用中不太实用。评分式点对点方法通过独立生成每个候选文档的相关性评分，展现出更高的效率。然而，这种独立性忽视了文档之间的重要比较信息，导致评分不一致和性能欠佳。

本文旨在通过两项关键创新，提升点对点方法的效果，同时保持其效率：(1) 我们提出了一种新型的全局一致比较点对点排序（GCCP）策略，通过将每个候选文档与一个锚点文档进行全局参考比较，生成对比相关性评分。我们战略性地将锚点文档设计为伪相关候选文档的查询聚焦摘要，通过捕获全局上下文信息，为文档比较提供了有效的参考点。(2) 这些对比相关性评分可以与现有点对点方法高效后聚合（PAGC），在无需额外训练的情况下，无缝融入关键的全局上下文信息。

我们在TREC DL和BEIR基准数据集上进行了大量实验，结果表明，与现有点对点方法相比，我们的方法在保持相当效率的同时，显著提升了性能。我们的方法在与需要更多计算资源的比较式方法的竞争中，也表现出了极具竞争力的水平。进一步的分析验证了我们锚点构建策略的有效性。


> Recent advancements have successfully harnessed the power of Large Language Models (LLMs) for zero-shot document ranking, exploring a variety of prompting strategies. Comparative approaches like pairwise and listwise achieve high effectiveness but are computationally intensive and thus less practical for larger-scale applications. Scoring-based pointwise approaches exhibit superior efficiency by independently and simultaneously generating the relevance scores for each candidate document. However, this independence ignores critical comparative insights between documents, resulting in inconsistent scoring and suboptimal performance. In this paper, we aim to improve the effectiveness of pointwise methods while preserving their efficiency through two key innovations: (1) We propose a novel Global-Consistent Comparative Pointwise Ranking (GCCP) strategy that incorporates global reference comparisons between each candidate and an anchor document to generate contrastive relevance scores. We strategically design the anchor document as a query-focused summary of pseudo-relevant candidates, which serves as an effective reference point by capturing the global context for document comparison. (2) These contrastive relevance scores can be efficiently Post-Aggregated with existing pointwise methods, seamlessly integrating essential Global Context information in a training-free manner (PAGC). Extensive experiments on the TREC DL and BEIR benchmark demonstrate that our approach significantly outperforms previous pointwise methods while maintaining comparable efficiency. Our method also achieves competitive performance against comparative methods that require substantially more computational resources. More analyses further validate the efficacy of our anchor construction strategy.

[Arxiv](https://arxiv.org/abs/2506.10859)