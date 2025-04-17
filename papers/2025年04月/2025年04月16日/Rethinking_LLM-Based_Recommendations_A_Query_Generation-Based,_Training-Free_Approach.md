# 重新审视基于LLM的推荐：一种基于查询生成的无需训练的方法

发布时间：2025年04月16日

`LLM应用` `推荐系统` `电子商务`

> Rethinking LLM-Based Recommendations: A Query Generation-Based, Training-Free Approach

# 摘要

> 现有基于 LLM 的推荐方法面临多重挑战：处理大规模候选池效率低下，对提示中项目顺序敏感（“迷失在中间”现象），扩展性差，以及因随机负采样导致评估不切实际。为应对这些挑战，我们提出了一种 Query-to-Recommendation 方法，通过 LLM 生成个性化查询，直接从整个候选池中检索相关项目，无需预选候选。该方法无需额外训练即可融入基于 ID 的推荐系统，借助 LLM 的广泛知识提升推荐效果和多样性，尤其对冷门项目组表现优异。实验结果显示，在三个数据集上，推荐性能提升了高达 57%，平均提升 31%，展现出卓越的零样本性能。与现有模型结合使用时，效果还能进一步提升。

> Existing large language model LLM-based recommendation methods face several challenges, including inefficiency in handling large candidate pools, sensitivity to item order within prompts ("lost in the middle" phenomenon) poor scalability, and unrealistic evaluation due to random negative sampling. To address these issues, we propose a Query-to-Recommendation approach that leverages LLMs to generate personalized queries for retrieving relevant items from the entire candidate pool, eliminating the need for candidate pre-selection. This method can be integrated into an ID-based recommendation system without additional training, enhances recommendation performance and diversity through LLMs' world knowledge, and performs well even for less popular item groups. Experiments on three datasets show up to 57 percent improvement, with an average gain of 31 percent, demonstrating strong zero-shot performance and further gains when ensembled with existing models.

[Arxiv](https://arxiv.org/abs/2504.11889)