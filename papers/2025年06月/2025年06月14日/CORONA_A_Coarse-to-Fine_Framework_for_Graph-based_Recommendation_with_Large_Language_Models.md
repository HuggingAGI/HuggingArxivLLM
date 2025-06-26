# CORONA：基于大型语言模型的图推荐系统中从粗到细的框架

发布时间：2025年06月14日

`LLM应用` `电子商务` `推荐系统`

> CORONA: A Coarse-to-Fine Framework for Graph-based Recommendation with Large Language Models

# 摘要

> 推荐系统（RSs）的目标是从海量商品库中筛选出用户可能感兴趣的候选商品。图神经网络（GNNs）因其擅长捕捉高阶交互关系而成为主流方法。随着大型语言模型（LLMs）在跨领域中展现出强大的能力，研究人员开始探索将其用于提升推荐效果。然而，此前的研究仅限于利用LLMs进行结果重排序或数据增强，未能在候选过滤阶段充分发挥其潜力，这可能导致推荐性能不尽如人意。为此，我们提出在候选过滤过程中充分利用LLMs的推理能力，并引入Chain Of Retrieval ON grAphs（CORONA）框架，借助LLMs逐步缩小交互图中的候选商品范围：（1）首先，LLM基于用户画像进行偏好推理，其输出结果作为查询，从交互图中提取相关用户和商品，形成偏好辅助检索；（2）接着，LLM结合上一步骤检索到的信息以及目标用户的购买历史，进行意图推理，进一步缩小交互子图范围，形成意图辅助检索；（3）最后，我们采用GNN从提取的子图中捕获高阶协同过滤信息，通过GNN增强检索生成最终推荐结果。该框架在检索过程中充分挖掘了LLMs的推理能力，同时无缝融入GNN以提升整体推荐性能。在多种数据集和设置下的大量实验表明，我们提出的CORONA框架实现了 state-of-the-art 的性能表现，平均召回率和NDCG分别提升了18.6%和18.4%的相对改进。

> Recommender systems (RSs) are designed to retrieve candidate items a user might be interested in from a large pool. A common approach is using graph neural networks (GNNs) to capture high-order interaction relationships. As large language models (LLMs) have shown strong capabilities across domains, researchers are exploring their use to enhance recommendation. However, prior work limits LLMs to re-ranking results or dataset augmentation, failing to utilize their power during candidate filtering - which may lead to suboptimal performance. Instead, we propose to leverage LLMs' reasoning abilities during the candidate filtering process, and introduce Chain Of Retrieval ON grAphs (CORONA) to progressively narrow down the range of candidate items on interaction graphs with the help of LLMs: (1) First, LLM performs preference reasoning based on user profiles, with the response serving as a query to extract relevant users and items from the interaction graph as preference-assisted retrieval; (2) Then, using the information retrieved in the previous step along with the purchase history of target user, LLM conducts intent reasoning to help refine an even smaller interaction subgraph as intent-assisted retrieval; (3) Finally, we employ a GNN to capture high-order collaborative filtering information from the extracted subgraph, performing GNN-enhanced retrieval to generate the final recommendation results. The proposed framework leverages the reasoning capabilities of LLMs during the retrieval process, while seamlessly integrating GNNs to enhance overall recommendation performance. Extensive experiments on various datasets and settings demonstrate that our proposed CORONA achieves state-of-the-art performance with an 18.6% relative improvement in recall and an 18.4% relative improvement in NDCG on average.

[Arxiv](https://arxiv.org/abs/2506.17281)