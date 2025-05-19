# 解释你的意思：构建意图增强的知识图谱推荐器，助力精准理解你的需求

发布时间：2025年05月16日

`LLM应用` `推荐系统` `电子商务`

> Explain What You Mean: Intent Augmented Knowledge Graph Recommender Built With LLM

# 摘要

> 交互稀疏性是推荐系统的核心挑战。这一问题常见于用户与产品基数不均衡的环境中，例如在线市场，并且对于新引入的实体而言，表现为冷启动问题。尽管近期为缓解稀疏性问题做出了诸多努力，但这些方法却将性能瓶颈转移到了计算流水线的其他环节。那些试图通过外部数据丰富稀疏表示的方法不仅需要大量资源，还需要领域专家的协助；而基于大型语言模型 (LLM) 的推荐系统则面临数据质量和可用性的限制。为解决这一难题，我们提出了基于 LLM 的意图知识图谱推荐器 (IKGR)，这是一个结合检索增强生成与编码方法的创新框架。IKGR 从交互知识图谱中学习潜在的用户-项目亲和力，并通过相互意图连接进一步密集化知识图谱。这不仅解决了稀疏性问题，还使模型能够通过可解释的嵌入转换层实现意图基础的推荐。通过在真实世界数据集上的广泛实验，我们证明 IKGR 成功克服了知识缺口，并在公共数据集和内部推荐数据集上显著超越了现有最先进的基线。

> Interaction sparsity is the primary obstacle for recommendation systems. Sparsity manifests in environments with disproportional cardinality of groupings of entities, such as users and products in an online marketplace. It also is found for newly introduced entities, described as the cold-start problem. Recent efforts to mitigate this sparsity issue shifts the performance bottleneck to other areas in the computational pipeline. Those that focus on enriching sparse representations with connectivity data from other external sources propose methods that are resource demanding and require careful domain expert aided addition of this newly introduced data. Others that turn to Large Language Model (LLM) based recommenders will quickly encounter limitations surrounding data quality and availability. In this work, we propose LLM-based Intent Knowledge Graph Recommender (IKGR), a novel framework that leverages retrieval-augmented generation and an encoding approach to construct and densify a knowledge graph. IKGR learns latent user-item affinities from an interaction knowledge graph and further densifies it through mutual intent connectivity. This addresses sparsity issues and allows the model to make intent-grounded recommendations with an interpretable embedding translation layer. Through extensive experiments on real-world datasets, we demonstrate that IKGR overcomes knowledge gaps and achieves substantial gains over state-of-the-art baselines on both publicly available and our internal recommendation datasets.

[Arxiv](https://arxiv.org/abs/2505.10900)