# # 大型语言模型赋能双曲空间推荐系统

发布时间：2025年04月08日

`LLM应用` `推荐系统`

> Large Language Models Enhanced Hyperbolic Space Recommender Systems

# 摘要

> 大型语言模型（LLMs）凭借其卓越的世界知识能力，在推荐系统领域引起了广泛关注。然而，现有基于欧几里得空间的方法难以有效捕捉文本和语义数据中的丰富层次信息，这对于准确把握用户偏好至关重要。双曲空间的独特几何特性为这一难题提供了极具潜力的解决方案。然而，如何将基于LLMs的方法与双曲空间有机结合，以高效提取和整合多样化的层次信息，仍是一个颇具挑战性的课题。

为此，我们提出了一种名为HyperLLM的模型不可知框架，它能够从结构和语义两个维度提取和整合层次信息。在结构层面，HyperLLM利用LLMs为每个项目生成具有层次父子关系的多级分类标签。随后，通过对比学习技术，模型能够同时学习和对齐标签-项目和用户-项目之间的交互关系，从而为其注入清晰的层次信息。在语义层面，HyperLLM创新性地引入了一种元优化策略，可以从语义嵌入中提取层次信息，并有效弥合语义空间与协作空间之间的鸿沟，实现无缝整合。

通过大量实验验证，HyperLLM在性能上显著超越了现有的基于双曲空间和LLMs的推荐系统，提升幅度超过40%。值得一提的是，HyperLLM不仅显著提升了推荐效果，还大幅增强了训练过程的稳定性。这一成果充分证明了层次信息在推荐系统中的关键作用，为未来的研究和应用提供了重要的参考价值。

> Large Language Models (LLMs) have attracted significant attention in recommender systems for their excellent world knowledge capabilities. However, existing methods that rely on Euclidean space struggle to capture the rich hierarchical information inherent in textual and semantic data, which is essential for capturing user preferences. The geometric properties of hyperbolic space offer a promising solution to address this issue. Nevertheless, integrating LLMs-based methods with hyperbolic space to effectively extract and incorporate diverse hierarchical information is non-trivial. To this end, we propose a model-agnostic framework, named HyperLLM, which extracts and integrates hierarchical information from both structural and semantic perspectives. Structurally, HyperLLM uses LLMs to generate multi-level classification tags with hierarchical parent-child relationships for each item. Then, tag-item and user-item interactions are jointly learned and aligned through contrastive learning, thereby providing the model with clear hierarchical information. Semantically, HyperLLM introduces a novel meta-optimized strategy to extract hierarchical information from semantic embeddings and bridge the gap between the semantic and collaborative spaces for seamless integration. Extensive experiments show that HyperLLM significantly outperforms recommender systems based on hyperbolic space and LLMs, achieving performance improvements of over 40%. Furthermore, HyperLLM not only improves recommender performance but also enhances training stability, highlighting the critical role of hierarchical information in recommender systems.

[Arxiv](https://arxiv.org/abs/2504.05694)