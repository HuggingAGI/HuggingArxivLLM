# 大型语言模型能否理解个性化推荐中的用户偏好？

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在个性化推荐任务中的应用，特别是如何通过新的评估方法（PerRecBench）来评估LLMs在捕捉用户个人偏好方面的能力。论文还探讨了LLMs在评分预测和个性化推荐中的表现，并提出了改进LLM对用户偏好理解的策略。因此，这篇论文属于LLM应用类别。` `个性化推荐` `用户行为分析`

> Can Large Language Models Understand Preferences in Personalized Recommendation?

# 摘要

> 大型语言模型（LLMs）在个性化推荐等任务中表现出色。现有评估方法多聚焦于评分预测，依赖实际与预测评分间的回归误差。然而，用户评分偏差和项目质量这两个关键因素，可能掩盖用户-项目对数据中的个人偏好。为此，我们推出PerRecBench，将评估与这两个因素脱钩，通过分组排序评估推荐技术捕捉个人偏好的能力。我们发现，基于LLM的推荐技术在评分预测上表现优异，但在用户评分偏差和项目质量被分组消除后，却难以识别用户喜好。通过PerRecBench和19个LLM的实验，我们发现大模型虽普遍优于小模型，但在个性化推荐上仍有不足。研究揭示了成对和列表排序方法优于点排序，PerRecBench与传统回归指标相关性低，用户档案的重要性，以及预训练数据分布的影响。我们还探索了三种监督微调策略，发现合并单一格式训练的权重颇具潜力，但提升LLM对用户偏好的理解仍是待解难题。代码和数据详见https://github.com/TamSiuhin/PerRecBench。

> Large Language Models (LLMs) excel in various tasks, including personalized recommendations. Existing evaluation methods often focus on rating prediction, relying on regression errors between actual and predicted ratings. However, user rating bias and item quality, two influential factors behind rating scores, can obscure personal preferences in user-item pair data. To address this, we introduce PerRecBench, disassociating the evaluation from these two factors and assessing recommendation techniques on capturing the personal preferences in a grouped ranking manner. We find that the LLM-based recommendation techniques that are generally good at rating prediction fail to identify users' favored and disfavored items when the user rating bias and item quality are eliminated by grouping users. With PerRecBench and 19 LLMs, we find that while larger models generally outperform smaller ones, they still struggle with personalized recommendation. Our findings reveal the superiority of pairwise and listwise ranking approaches over pointwise ranking, PerRecBench's low correlation with traditional regression metrics, the importance of user profiles, and the role of pretraining data distributions. We further explore three supervised fine-tuning strategies, finding that merging weights from single-format training is promising but improving LLMs' understanding of user preferences remains an open research problem. Code and data are available at https://github.com/TamSiuhin/PerRecBench

[Arxiv](https://arxiv.org/abs/2501.13391)