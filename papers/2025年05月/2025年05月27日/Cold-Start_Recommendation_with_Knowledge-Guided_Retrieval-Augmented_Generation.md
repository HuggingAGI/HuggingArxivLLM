# 冷启动推荐：知识引导的检索增强生成方法

发布时间：2025年05月27日

`LLM应用` `推荐系统` `知识图谱`

> Cold-Start Recommendation with Knowledge-Guided Retrieval-Augmented Generation

# 摘要

> 冷启动物品在推荐系统中一直是难题，因为它们缺乏协作模型依赖的历史用户交互。尽管最近的零样本方法利用大型语言模型 (LLMs) 来应对这一挑战，但它们常受制于稀疏元数据及知识的不完整性和幻觉问题。我们提出 ColdRAG，这是一种基于检索增强生成的方法，通过动态构建领域特定的知识图谱，无需特定任务微调，即可增强基于 LLM 的推荐。ColdRAG 将结构化的物品属性转化为丰富的自然语言描述，从中提取实体与关系，构建统一的知识图谱，捕捉物品语义。根据用户交互历史，ColdRAG 使用 LLM 对图中的边进行评分，检索带支持证据的候选物品，并提示 LLM 进行排序。通过多跳推理，ColdRAG 将推荐建立在可验证证据基础上，减少幻觉并增强语义联系。在三个公开基准数据集上的实验表明，ColdRAG 在 Recall 和 NDCG 指标上超越现有零样本方法。此框架结合知识图谱推理与检索增强的 LLM 生成，为冷启动推荐提供实用解决方案。

> Cold-start items remain a persistent challenge in recommender systems due to their lack of historical user interactions, which collaborative models rely on. While recent zero-shot methods leverage large language models (LLMs) to address this, they often struggle with sparse metadata and hallucinated or incomplete knowledge. We propose ColdRAG, a retrieval-augmented generation approach that builds a domain-specific knowledge graph dynamically to enhance LLM-based recommendation in cold-start scenarios, without requiring task-specific fine-tuning. ColdRAG begins by converting structured item attributes into rich natural-language profiles, from which it extracts entities and relationships to construct a unified knowledge graph capturing item semantics. Given a user's interaction history, it scores edges in the graph using an LLM, retrieves candidate items with supporting evidence, and prompts the LLM to rank them. By enabling multi-hop reasoning over this graph, ColdRAG grounds recommendations in verifiable evidence, reducing hallucinations and strengthening semantic connections. Experiments on three public benchmarks demonstrate that ColdRAG surpasses existing zero-shot baselines in both Recall and NDCG. This framework offers a practical solution to cold-start recommendation by combining knowledge-graph reasoning with retrieval-augmented LLM generation.

[Arxiv](https://arxiv.org/abs/2505.20773)