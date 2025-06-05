# # 抽样偏好揭示简单而有效的可信度评分
通过分析抽样偏好，我们能够获得简单而有效的可信度评分。

发布时间：2025年06月03日

`LLM理论

理由：这篇论文探讨了大语言模型（LLMs）的多维评估框架以及如何通过“偏好采样”方法从多维评估结果中提取标量可信度分数，属于对LLM的理论研究，旨在改进模型选择和评估方法。` `AI评估` `可信AI`

> Sampling Preferences Yields Simple Trustworthiness Scores

# 摘要

> 随着大语言模型（LLMs）的兴起，AI 模型的性能正在变得多维化。为此，出现了多种多维评估框架用于评估 LLMs。尽管这些框架比早期的单一指标评估更现实，但多维评估可能使决策过程变得更加复杂，因为没有明显的方法来选择最优模型。本研究引入了“偏好采样”方法，通过考虑用户重视的模型性能的多种特性，从多维评估结果中提取标量可信度分数。我们展示了偏好采样通过利用 TrustLLM 和 DecodingTrust 的多维可信度评估，改进了其他聚合方法。我们发现，偏好采样始终具有简化性——在 100% 的情况下完全减少候选模型集合，而帕累托最优性从未将集合减少超过 50%。同样，偏好采样始终对用户先验敏感——允许用户指定其偏好的相对权重和置信度——而平均分数则对用户的先验知识无动于衷。

> With the onset of large language models (LLMs), the performance of artificial intelligence (AI) models is becoming increasingly multi-dimensional. Accordingly, there have been several large, multi-dimensional evaluation frameworks put forward to evaluate LLMs. Though these frameworks are much more realistic than previous attempts which only used a single score like accuracy, multi-dimensional evaluations can complicate decision-making since there is no obvious way to select an optimal model. This work introduces preference sampling, a method to extract a scalar trustworthiness score from multi-dimensional evaluation results by considering the many characteristics of model performance which users value. We show that preference sampling improves upon alternate aggregation methods by using multi-dimensional trustworthiness evaluations of LLMs from TrustLLM and DecodingTrust. We find that preference sampling is consistently reductive, fully reducing the set of candidate models 100% of the time whereas Pareto optimality never reduces the set by more than 50%. Likewise, preference sampling is consistently sensitive to user priors-allowing users to specify the relative weighting and confidence of their preferences-whereas averaging scores is intransigent to the users' prior knowledge.

[Arxiv](https://arxiv.org/abs/2506.03399)