# LLMInit: 利用大型语言模型实现推荐系统的高效初始化

发布时间：2025年03月03日

`LLM应用` `推荐系统` `协同过滤`

> LLMInit: A Free Lunch from Large Language Models for Selective Initialization of Recommendation

# 摘要

> 协同过滤模型，尤其是基于图的方法，在推荐系统中捕捉用户-物品交互方面表现突出。然而，它们在冷启动和数据稀疏场景中仍面临挑战。大型语言模型（LLMs）如GPT和LLaMA的出现，为提升推荐性能，特别是在冷启动场景中，带来了新机遇。尽管潜力巨大，但LLMs在可扩展性和效率方面面临挑战，主要源于其高计算需求以及建模复杂用户-物品关系能力的不足。本研究提出了一种利用LLMs进行协同过滤模型初始化的新方法。实验中，我们发现当扩展协同过滤模型至更大嵌入维度时，会出现嵌入坍塌问题。为有效利用大规模LLM嵌入，我们创新性地提出了基于随机、均匀和方差的索引采样选择性初始化策略。在多个真实数据集上的全面评估显示，与现有基于LLM的推荐方法相比，我们的方法在各类协同过滤模型中实现了显著性能提升，同时保持了更低的计算成本。

> Collaborative filtering models, particularly graph-based approaches, have demonstrated strong performance in capturing user-item interactions for recommendation systems. However, they continue to struggle in cold-start and data-sparse scenarios. The emergence of large language models (LLMs) like GPT and LLaMA presents new possibilities for enhancing recommendation performance, especially in cold-start settings. Despite their promise, LLMs pose challenges related to scalability and efficiency due to their high computational demands and limited ability to model complex user-item relationships effectively. In this work, we introduce a novel perspective on leveraging LLMs for CF model initialization. Through experiments, we uncover an embedding collapse issue when scaling CF models to larger embedding dimensions. To effectively harness large-scale LLM embeddings, we propose innovative selective initialization strategies utilizing random, uniform, and variance-based index sampling. Our comprehensive evaluation on multiple real-world datasets demonstrates significant performance gains across various CF models while maintaining a lower computational cost compared to existing LLM-based recommendation approaches.

[Arxiv](https://arxiv.org/abs/2503.01814)