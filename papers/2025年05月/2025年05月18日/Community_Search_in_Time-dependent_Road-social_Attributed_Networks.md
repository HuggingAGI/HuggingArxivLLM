# # 时间依赖路社属性网络中的社区搜索

发布时间：2025年05月18日

`其他` `社区搜索`

> Community Search in Time-dependent Road-social Attributed Networks

# 摘要

> 现实世界中的网络通常同时涉及关键词和位置信息，且由于交通状况的变化，位置之间的 travel time 也会发生变化。然而，现有的大多数基于凝聚子图的社区搜索研究仅利用单一属性（关键词或位置）来识别社区。它们未能同时考虑关键词和位置，导致检测到的社区在语义或空间上凝聚力较低，且无法考虑 travel time 的变化。此外，这些研究遍历整个网络来构建高效的索引，但检测到的社区仅涉及查询节点附近的节点，导致遍历与社区无关的节点。因此，我们提出了发现语义-空间感知的 k-core 问题，即包含查询节点且具有高语义和时间依赖的空间凝聚力的 k-core。为了解决这一问题，我们提出了一个精确算法和一个贪心算法，它们都从查询节点逐渐向外扩展。它们是局部方法，仅访问属性网络中靠近查询节点的局部部分，而不是整个网络。此外，我们设计了一种基于大型语言模型计算两个关键词之间语义相似性的方法。该方法缓解了现有社区搜索研究中关键词匹配方法的缺点，例如由不同表达的同义词引起的匹配不准确以及存在无关词的问题。实验结果表明，贪心算法在结构、语义和时间依赖的空间凝聚力方面优于基线方法。

> Real-world networks often involve both keywords and locations, along with travel time variations between locations due to traffic conditions. However, most existing cohesive subgraph-based community search studies utilize a single attribute, either keywords or locations, to identify communities. They do not simultaneously consider both keywords and locations, which results in low semantic or spatial cohesiveness of the detected communities, and they fail to account for variations in travel time. Additionally, these studies traverse the entire network to build efficient indexes, but the detected community only involves nodes around the query node, leading to the traversal of nodes that are not relevant to the community. Therefore, we propose the problem of discovering semantic-spatial aware k-core, which refers to a k-core with high semantic and time-dependent spatial cohesiveness containing the query node. To address this problem, we propose an exact and a greedy algorithm, both of which gradually expand outward from the query node. They are local methods that only access the local part of the attributed network near the query node rather than the entire network. Moreover, we design a method to calculate the semantic similarity between two keywords using large language models. This method alleviates the disadvantages of keyword-matching methods used in existing community search studies, such as mismatches caused by differently expressed synonyms and the presence of irrelevant words. Experimental results show that the greedy algorithm outperforms baselines in terms of structural, semantic, and time-dependent spatial cohesiveness.

[Arxiv](https://arxiv.org/abs/2505.12309)