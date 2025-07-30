# 按需探索：从算法控制到用户赋能

发布时间：2025年07月29日

`其他

理由：这篇论文主要讨论的是推荐系统中的过度专业化问题，并提出了一种自适应聚类框架来平衡个性化与多样性。虽然提到了使用句子转换器嵌入和大规模语言模型的A/B测试，但论文的核心内容集中在推荐系统的改进和用户探索机制的设计上，而不是直接研究或应用大型语言模型（LLM）本身。因此，它更适合归类为“其他”。` `推荐系统`

> Exploration on Demand: From Algorithmic Control to User Empowerment

# 摘要

> 推荐系统常常陷入过度专业化的困境，这不仅限制了用户接触多元化内容的机会，还形成了过滤气泡，减少了意外发现的可能性。为解决这一关键性问题，本文提出了一种自适应聚类框架，通过用户可控的探索机制，在电影推荐中实现了个性化与多样性的完美平衡。我们的方法利用句子转换器嵌入，通过一种带有动态阈值的在线算法，将项目分组到语义连贯的集群中，从而构建内容空间的结构化表示。在此基础上，我们提出了一种创新的探索机制，让用户能够通过战略性地从较少参与的集群中进行采样来控制推荐的多样性，从而在保持相关性的同时扩展其内容视野。实验结果表明，该系统在MovieLens数据集上表现优异，探索将列表内相似性从0.34降低到0.26，同时意外性增加到0.73。此外，我们基于大规模语言模型的A/B测试方法，模拟了300名用户，结果显示72.7%的长期用户更倾向于探索性推荐而非纯粹的开发性推荐，这为系统在不牺牲用户满意度的情况下促进有意义内容发现的能力提供了有力证据。

> Recommender systems often struggle with over-specialization, which severely limits users' exposure to diverse content and creates filter bubbles that reduce serendipitous discovery. To address this fundamental limitation, this paper introduces an adaptive clustering framework with user-controlled exploration that effectively balances personalization and diversity in movie recommendations. Our approach leverages sentence-transformer embeddings to group items into semantically coherent clusters through an online algorithm with dynamic thresholding, thereby creating a structured representation of the content space. Building upon this clustering foundation, we propose a novel exploration mechanism that empowers users to control recommendation diversity by strategically sampling from less-engaged clusters, thus expanding their content horizons while preserving relevance. Experiments on the MovieLens dataset demonstrate the system's effectiveness, showing that exploration significantly reduces intra-list similarity from 0.34 to 0.26 while simultaneously increasing unexpectedness to 0.73. Furthermore, our Large Language Model-based A/B testing methodology, conducted with 300 simulated users, reveals that 72.7% of long-term users prefer exploratory recommendations over purely exploitative ones, providing strong evidence for the system's ability to promote meaningful content discovery without sacrificing user satisfaction.

[Arxiv](https://arxiv.org/abs/2507.21884)