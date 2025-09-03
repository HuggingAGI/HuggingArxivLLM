# 为BRIGHT指明方向：基于Anserini、Pyserini和RankLLM的可复现基线

发布时间：2025年09月02日

`RAG` `基础理论`

> Lighting the Way for BRIGHT: Reproducible Baselines with Anserini, Pyserini, and RankLLM

# 摘要

> BRIGHT基准数据集包含不同领域的推理密集型查询。我们采用多种检索技术（涵盖稀疏、密集及融合方法）在BRIGHT上开展检索结果研究，并构建了可复现的基线。随后，我们借助大型语言模型（LLMs）进行列表式重排序，深入探究重排序对推理密集型查询的影响。这些基线已集成到主流检索与重排序工具包（如Anserini、Pyserini和RankLLM）中，支持两键式复现，便于后续在此基础上扩展和开发。在复现原始BRIGHT论文结果的过程中，我们发现其提供的BM25分数与我们用Anserini和Pyserini得到的结果存在明显差异。我们发现差异源于BRIGHT对BM25的独特实现：它将BM25直接应用于查询，而非像Anserini那样采用标准词袋法构建查询向量。随着长查询的兴起（BRIGHT中冗长的推理密集型查询便是典型），加之检索增强生成的应用愈发广泛（LLM提示可能远长于“传统”搜索引擎查询），这种差异的影响也日益凸显。这一发现提示我们，为更好地适配新兴应用，未来或许需要重新审视BM25方法。为此，我们已将查询端BM25集成到Anserini和Pyserini中。

> The BRIGHT benchmark is a dataset consisting of reasoning-intensive queries over diverse domains. We explore retrieval results on BRIGHT using a range of retrieval techniques, including sparse, dense, and fusion methods, and establish reproducible baselines. We then apply listwise reranking with large language models (LLMs) to further investigate the impact of reranking on reasoning-intensive queries. These baselines are integrated into popular retrieval and reranking toolkits Anserini, Pyserini, and RankLLM, with two-click reproducibility that makes them easy to build upon and convenient for further development. While attempting to reproduce the results reported in the original BRIGHT paper, we find that the provided BM25 scores differ notably from those that we obtain using Anserini and Pyserini. We discover that this difference is due to BRIGHT's implementation of BM25, which applies BM25 on the query rather than using the standard bag-of-words approach, as in Anserini, to construct query vectors. This difference has become increasingly relevant due to the rise of longer queries, with BRIGHT's lengthy reasoning-intensive queries being a prime example, and further accentuated by the increasing usage of retrieval-augmented generation, where LLM prompts can grow to be much longer than ''traditional'' search engine queries. Our observation signifies that it may be time to reconsider BM25 approaches going forward in order to better accommodate emerging applications. To facilitate this, we integrate query-side BM25 into both Anserini and Pyserini.

[Arxiv](https://arxiv.org/abs/2509.02558)