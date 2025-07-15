# 通过层次化聚合实现的检索增强推荐解释生成

发布时间：2025年07月12日

`其他

理由：这篇论文主要探讨了可解释推荐系统（ExRec）的改进，使用了大型语言模型（LLMs）来生成推荐解释。虽然LLMs在这里被应用，但论文的核心是推荐系统的优化，属于推荐系统领域，而非直接探讨LLMs的应用或理论。因此，归类为其他。` `推荐系统`

> Retrieval-Augmented Recommendation Explanation Generation with Hierarchical Aggregation

# 摘要

> 可解释推荐系统（ExRec）通过提升推荐流程的透明性，增强了用户信任并推动了在线服务的运营。随着大型语言模型（LLMs）的兴起，其强大的全球知识和细腻的语言理解能力使得生成类人且具有上下文依据的解释成为可能，基于LLMs的ExRec发展势头强劲。然而，现有基于LLMs的ExRec模型面临用户画像偏差和检索开销过高的问题，限制了其实际应用。为解决这些问题，我们提出了基于分层聚合的检索增强推荐解释生成方法（REXHA）。具体而言，我们设计了一个基于分层聚合的用户画像模块，全面整合用户和物品的评论信息，分层总结并构建完整的用户画像。同时，我们引入了一个高效的检索模块，通过两种伪文档查询方式检索相关评论，从而增强推荐解释的生成能力，有效降低了检索延迟并提高了相关评论的召回率。大量实验结果表明，与现有方法相比，我们的方法在解释质量上提升了多达12.6%，同时保持了高检索效率。

> Explainable Recommender System (ExRec) provides transparency to the recommendation process, increasing users' trust and boosting the operation of online services. With the rise of large language models (LLMs), whose extensive world knowledge and nuanced language understanding enable the generation of human-like, contextually grounded explanations, LLM-powered ExRec has gained great momentum. However, existing LLM-based ExRec models suffer from profile deviation and high retrieval overhead, hindering their deployment. To address these issues, we propose Retrieval-Augmented Recommendation Explanation Generation with Hierarchical Aggregation (REXHA). Specifically, we design a hierarchical aggregation based profiling module that comprehensively considers user and item review information, hierarchically summarizing and constructing holistic profiles. Furthermore, we introduce an efficient retrieval module using two types of pseudo-document queries to retrieve relevant reviews to enhance the generation of recommendation explanations, effectively reducing retrieval latency and improving the recall of relevant reviews. Extensive experiments demonstrate that our method outperforms existing approaches by up to 12.6% w.r.t. the explanation quality while achieving high retrieval efficiency.

[Arxiv](https://arxiv.org/abs/2507.09188)