# Rank-K：测试时推理驱动的列表重排序

发布时间：2025年05月20日

`LLM应用` `信息检索`

> Rank-K: Test-Time Reasoning for Listwise Reranking

# 摘要

> 检索与重排因其高效性而广受欢迎，它通过减少比较次数，让慢但有效的重排器在查询时也能表现出色。近年来，神经重排器借助大型语言模型强大的推理能力，在查询与段落间建立联系，取得了最先进的检索效果。然而，这类重排器即便经过优化，仍需大量资源。我们提出了Rank-K，一种基于查询时利用推理语言模型推理能力的列表式段落重排模型，它在处理困难查询时具备测试时的可扩展性。实验结果显示，Rank-K在对BM25初始排序列表进行重排时，比最先进的列表式重排器RankZephyr提升了23\%的检索效果；而在对SPLADE-v3的强检索结果进行重排时，提升了19\%。由于Rank-K本质上是一个多语言模型，它能够像在单语种检索中一样，根据不同语言的查询对段落进行有效排序。


> Retrieve-and-rerank is a popular retrieval pipeline because of its ability to make slow but effective rerankers efficient enough at query time by reducing the number of comparisons. Recent works in neural rerankers take advantage of large language models for their capability in reasoning between queries and passages and have achieved state-of-the-art retrieval effectiveness. However, such rerankers are resource-intensive, even after heavy optimization. In this work, we introduce Rank-K, a listwise passage reranking model that leverages the reasoning capability of the reasoning language model at query time that provides test time scalability to serve hard queries. We show that Rank-K improves retrieval effectiveness by 23\% over the RankZephyr, the state-of-the-art listwise reranker, when reranking a BM25 initial ranked list and 19\% when reranking strong retrieval results by SPLADE-v3. Since Rank-K is inherently a multilingual model, we found that it ranks passages based on queries in different languages as effectively as it does in monolingual retrieval.

[Arxiv](https://arxiv.org/abs/2505.14432)