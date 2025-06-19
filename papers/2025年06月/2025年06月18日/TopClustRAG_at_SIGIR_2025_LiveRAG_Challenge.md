# # TopClustRAG团队在SIGIR 2025实时RAG挑战赛中

发布时间：2025年06月18日

`RAG` `信息检索` `问答系统`

> TopClustRAG at SIGIR 2025 LiveRAG Challenge

# 摘要

> 我们提出了TopClustRAG，这是一个为LiveRAG挑战开发的检索增强生成（RAG）系统，专注于在大规模网络语料库上实现端到端的问题回答。我们的系统采用了一种结合稀疏和密集索引的混合检索策略，并通过K-Means聚类将语义相似的段落分组。从每个聚类中选取代表性的段落，用于构建特定于聚类的大语言模型（LLM）提示，生成中间答案。这些中间答案经过过滤、重新排序，最终整合为一个全面的最终回答。这种多阶段的流水线显著提升了答案的多样性、相关性和对检索到的证据的忠实度。在FineWeb Sample-10BT数据集上的评估显示，TopClustRAG在官方排行榜上忠实度排名第2，正确性排名第7，充分证明了基于聚类的上下文过滤和提示聚合在大规模RAG系统中的有效性。

> We present TopClustRAG, a retrieval-augmented generation (RAG) system developed for the LiveRAG Challenge, which evaluates end-to-end question answering over large-scale web corpora. Our system employs a hybrid retrieval strategy combining sparse and dense indices, followed by K-Means clustering to group semantically similar passages. Representative passages from each cluster are used to construct cluster-specific prompts for a large language model (LLM), generating intermediate answers that are filtered, reranked, and finally synthesized into a single, comprehensive response. This multi-stage pipeline enhances answer diversity, relevance, and faithfulness to retrieved evidence. Evaluated on the FineWeb Sample-10BT dataset, TopClustRAG ranked 2nd in faithfulness and 7th in correctness on the official leaderboard, demonstrating the effectiveness of clustering-based context filtering and prompt aggregation in large-scale RAG systems.

[Arxiv](https://arxiv.org/abs/2506.15246)