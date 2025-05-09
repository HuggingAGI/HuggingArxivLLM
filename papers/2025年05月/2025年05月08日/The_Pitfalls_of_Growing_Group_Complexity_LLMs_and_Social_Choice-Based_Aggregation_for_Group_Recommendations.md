# 群体复杂性增长的挑战：LLMs与社会选择聚合在群体推荐中的应用

发布时间：2025年05月08日

`LLM应用` `推荐系统` `群体推荐`

> The Pitfalls of Growing Group Complexity: LLMs and Social Choice-Based Aggregation for Group Recommendations

# 摘要

> 大型语言模型（LLMs）正越来越多地被应用于面向个人和群体的推荐系统中。过去，群体推荐系统（GRS）通常使用基于社会选择的聚合策略，根据多个人的偏好得出单一推荐结果。本文研究了语言模型在零-shot学习下能否正确执行这些策略，并分析提示中群体场景的格式是否会影响准确性。我们具体关注了群体复杂性（用户和项目的数量）、不同LLMs、不同的提示条件，包括In-Context学习或生成解释，以及群体偏好的格式化。我们的结果显示，当考虑超过100个评分时，性能开始下降。然而，并非所有语言模型对群体复杂性的增长都同样敏感。此外，我们还发现，In-Context Learning（ICL）可以在更高程度的群体复杂性下显著提升性能，而添加其他提示修改、指定领域提示或要求解释，并未影响准确性。我们得出结论，未来的研究应将群体复杂性作为GRS评估的一个因素，因为其对LLM性能的影响。此外，我们还展示了以不同的格式化方式呈现群体场景，例如按用户或按项目列出评分，会影响准确性。总的来说，我们的研究表明，在合适的条件下，较小的LLMs也能够生成群体推荐，这为使用计算需求和成本更低的小模型提供了依据。

> Large Language Models (LLMs) are increasingly applied in recommender systems aimed at both individuals and groups. Previously, Group Recommender Systems (GRS) often used social choice-based aggregation strategies to derive a single recommendation based on the preferences of multiple people. In this paper, we investigate under which conditions language models can perform these strategies correctly based on zero-shot learning and analyse whether the formatting of the group scenario in the prompt affects accuracy. We specifically focused on the impact of group complexity (number of users and items), different LLMs, different prompting conditions, including In-Context learning or generating explanations, and the formatting of group preferences. Our results show that performance starts to deteriorate when considering more than 100 ratings. However, not all language models were equally sensitive to growing group complexity. Additionally, we showed that In-Context Learning (ICL) can significantly increase the performance at higher degrees of group complexity, while adding other prompt modifications, specifying domain cues or prompting for explanations, did not impact accuracy. We conclude that future research should include group complexity as a factor in GRS evaluation due to its effect on LLM performance. Furthermore, we showed that formatting the group scenarios differently, such as rating lists per user or per item, affected accuracy. All in all, our study implies that smaller LLMs are capable of generating group recommendations under the right conditions, making the case for using smaller models that require less computing power and costs.

[Arxiv](https://arxiv.org/abs/2505.05016)