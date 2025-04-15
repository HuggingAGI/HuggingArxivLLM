# 通过语义对齐的协作知识，提升基于LLM的推荐系统性能

发布时间：2025年04月14日

`LLM应用` `推荐系统` `电子商务`

> Enhancing LLM-based Recommendation through Semantic-Aligned Collaborative Knowledge

# 摘要

> 大型语言模型（LLMs）在推荐任务中展现了强大的能力，能够充分利用全面的世界知识和复杂的推理机制。然而，与传统的协同过滤模型（Collabs.）相比，LLMs 在建模稀疏标识符（如用户和项目 ID）方面存在明显不足，这限制了其学习独特用户-项目表示的能力，形成了性能瓶颈。尽管先前研究指出，将协同知识从 Collabs. 整合到 LLMs 中可以提升推荐性能，但 LLMs 和 Collab. 之间知识分布和语义空间的巨大差异使有效知识迁移面临巨大挑战。

为解决这一难题，我们提出了 SeLLa-Rec 框架，专注于实现 Collabs. 和 LLMs 语义空间的对齐。这种对齐促进了知识的有效融合，减少了判别噪声的影响，并实现了跨模型的深度知识整合。具体而言，我们通过混合投影层将三种嵌入协同知识的特殊令牌嵌入到 LLM 的语义空间中，并将其集成到任务特定的提示中，以引导推荐过程。实验结果表明，在 MovieLens-1M 和 Amazon Book 两个基准数据集上，SeLLa-Rec 达到了当前最优的性能水平。

> Large Language Models (LLMs) demonstrate remarkable capabilities in leveraging comprehensive world knowledge and sophisticated reasoning mechanisms for recommendation tasks. However, a notable limitation lies in their inability to effectively model sparse identifiers (e.g., user and item IDs), unlike conventional collaborative filtering models (Collabs.), thus hindering LLM to learn distinctive user-item representations and creating a performance bottleneck. Prior studies indicate that integrating collaborative knowledge from Collabs. into LLMs can mitigate the above limitations and enhance their recommendation performance. Nevertheless, the significant discrepancy in knowledge distribution and semantic space between LLMs and Collab. presents substantial challenges for effective knowledge transfer. To tackle these challenges, we propose a novel framework, SeLLa-Rec, which focuses on achieving alignment between the semantic spaces of Collabs. and LLMs. This alignment fosters effective knowledge fusion, mitigating the influence of discriminative noise and facilitating the deep integration of knowledge from diverse models. Specifically, three special tokens with collaborative knowledge are embedded into the LLM's semantic space through a hybrid projection layer and integrated into task-specific prompts to guide the recommendation process. Experiments conducted on two public benchmark datasets (MovieLens-1M and Amazon Book) demonstrate that SeLLa-Rec achieves state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2504.10107)