# 一致的解释者，还是不可靠的叙述者？解析LLM生成的群体推荐机制

发布时间：2025年07月18日

`LLM应用` `推荐系统` `群组决策`

> Consistent Explainers or Unreliable Narrators? Understanding LLM-generated Group Recommendations

# 摘要

> 大型语言模型（LLMs）正越来越多地被用作群组推荐系统（GRS）的决策者和解释生成器。我们通过将其与基于社会选择的聚合策略进行对比，评估了这些推荐和解释。研究发现，LLM生成的推荐通常与加法功利主义（ADD）聚合结果相似，但解释多基于平均评分（与ADD聚合类似但不完全相同）。群组结构（统一或分散）对推荐结果无显著影响。此外，LLMs常声称考虑了额外准则，如用户或项目相似性、多样性，或采用了未定义的流行度指标或阈值。这些发现对LLMs在GRS中的应用及标准聚合策略具有重要意义。解释中涉及的额外准则取决于群组场景中的评分数量，这表明标准聚合方法在处理更大规模项目集合时可能存在低效性。此外，不一致和模糊的解释削弱了透明度和可解释性，而这正是使用LLMs进行GRS的核心动机。


> Large Language Models (LLMs) are increasingly being implemented as joint decision-makers and explanation generators for Group Recommender Systems (GRS). In this paper, we evaluate these recommendations and explanations by comparing them to social choice-based aggregation strategies. Our results indicate that LLM-generated recommendations often resembled those produced by Additive Utilitarian (ADD) aggregation. However, the explanations typically referred to averaging ratings (resembling but not identical to ADD aggregation). Group structure, uniform or divergent, did not impact the recommendations. Furthermore, LLMs regularly claimed additional criteria such as user or item similarity, diversity, or used undefined popularity metrics or thresholds. Our findings have important implications for LLMs in the GRS pipeline as well as standard aggregation strategies. Additional criteria in explanations were dependent on the number of ratings in the group scenario, indicating potential inefficiency of standard aggregation methods at larger item set sizes. Additionally, inconsistent and ambiguous explanations undermine transparency and explainability, which are key motivations behind the use of LLMs for GRS.

[Arxiv](https://arxiv.org/abs/2507.13705)