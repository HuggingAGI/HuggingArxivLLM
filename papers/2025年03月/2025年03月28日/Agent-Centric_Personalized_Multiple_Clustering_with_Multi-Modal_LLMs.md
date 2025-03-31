# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月28日

`LLM应用` `数据科学` `人工智能`

> Agent-Centric Personalized Multiple Clustering with Multi-Modal LLMs

# 摘要

> 个性化多聚类的目标是根据不同的用户特定需求，生成数据集的多样化划分，而非单一的聚类结果。这一方法因其能够适应多样化的用户偏好而受到广泛关注。目前，研究者主要通过CLIP嵌入结合代理学习来提取偏向用户聚类偏好的表示。然而，CLIP主要关注粗粒度的图像-文本对齐，无法深入理解用户的兴趣语境。为了解决这一局限性，我们提出了一种基于多模态大型语言模型（MLLMs）的代理为中心的个性化聚类框架。该框架利用MLLMs作为代理，通过全面遍历关系图，根据用户兴趣搜索聚类。得益于MLLMs强大的推理能力，所获得的聚类结果比基于CLIP表示的聚类更贴近用户定义的标准。为了减少计算开销，我们通过MLLMs提取的用户兴趣偏向嵌入构建关系图，从而缩短代理的遍历路径。基于嵌入相似性，可以过滤掉大量弱连接的边，从而提高代理的遍历搜索效率。实验结果表明，我们的方法在Card Order和Card Suits基准测试中分别达到了0.9667和0.9481的NMI得分，与现有最优模型相比，性能提升了超过140%。

> Personalized multiple clustering aims to generate diverse partitions of a dataset based on different user-specific aspects, rather than a single clustering. It has recently drawn research interest for accommodating varying user preferences. Recent approaches primarily use CLIP embeddings with proxy learning to extract representations biased toward user clustering preferences. However, CLIP primarily focuses on coarse image-text alignment, lacking a deep contextual understanding of user interests. To overcome these limitations, we propose an agent-centric personalized clustering framework that leverages multi-modal large language models (MLLMs) as agents to comprehensively traverse a relational graph to search for clusters based on user interests. Due to the advanced reasoning mechanism of MLLMs, the obtained clusters align more closely with user-defined criteria than those obtained from CLIP-based representations. To reduce computational overhead, we shorten the agents' traversal path by constructing a relational graph using user-interest-biased embeddings extracted by MLLMs. A large number of weakly connected edges can be filtered out based on embedding similarity, facilitating an efficient traversal search for agents. Experimental results show that the proposed method achieves NMI scores of 0.9667 and 0.9481 on the Card Order and Card Suits benchmarks, respectively, largely improving the SOTA model by over 140%.

[Arxiv](https://arxiv.org/abs/2503.22241)