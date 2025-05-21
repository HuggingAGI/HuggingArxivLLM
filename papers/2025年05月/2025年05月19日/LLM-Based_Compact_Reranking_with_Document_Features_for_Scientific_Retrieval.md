# # 基于LLM的紧凑重排序：结合文档特征提升科学检索效果

发布时间：2025年05月19日

`LLM应用` `科学检索` `学术研究`

> LLM-Based Compact Reranking with Document Features for Scientific Retrieval

# 摘要

> 科学检索是推动学术发现的重要工具。在这一过程中，文档重排序通过优化第一阶段的检索结果发挥着关键作用。然而，在科学领域，基于大型语言模型的列表式重排序面临独特挑战。首先，第一阶段检索在科学领域往往不够理想，导致相关文档排名靠后。其次，传统的列表式重排序方法在上下文窗口中使用候选文档的全文内容，限制了可考虑的候选数量。因此，许多相关文档在重排序之前就被排除，从而限制了整体检索性能。为了解决这些挑战，我们探索了基于语义特征（如类别、章节和关键词）的紧凑文档表示，并提出了一种无训练、模型不可知的重排序框架，名为CoRank，专门用于科学检索。该框架包含三个阶段：(i) 离线提取文档级别的特征，(ii) 使用这些紧凑表示进行粗排，(iii) 在阶段(ii)选出的顶部候选文档的全文上进行细粒度重排序。这种混合设计为文档语义提供了高层次的抽象，扩大了候选覆盖范围，并保留了精确排序所需的关键细节。在LitSearch和CSFCube上的实验表明，CoRank显著提升了不同LLM后端的重排序性能，将nDCG@10从32.0提升至39.7。总体而言，这些结果凸显了信息提取在科学检索重排序中的价值。

> Scientific retrieval is essential for advancing academic discovery. Within this process, document reranking plays a critical role by refining first-stage retrieval results. However, large language model (LLM) listwise reranking faces unique challenges in the scientific domain. First-stage retrieval is often suboptimal in the scientific domain, so relevant documents are ranked lower. Moreover, conventional listwise reranking uses the full text of candidate documents in the context window, limiting the number of candidates that can be considered. As a result, many relevant documents are excluded before reranking, which constrains overall retrieval performance. To address these challenges, we explore compact document representations based on semantic features such as categories, sections, and keywords, and propose a training-free, model-agnostic reranking framework for scientific retrieval called CoRank. The framework involves three stages: (i) offline extraction of document-level features, (ii) coarse reranking using these compact representations, and (iii) fine-grained reranking on full texts of the top candidates from stage (ii). This hybrid design provides a high-level abstraction of document semantics, expands candidate coverage, and retains critical details required for precise ranking. Experiments on LitSearch and CSFCube show that CoRank significantly improves reranking performance across different LLM backbones, increasing nDCG@10 from 32.0 to 39.7. Overall, these results highlight the value of information extraction for reranking in scientific retrieval.

[Arxiv](https://arxiv.org/abs/2505.13757)