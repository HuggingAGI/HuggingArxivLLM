# 人类如何助力LLMs：评估与激励人类偏好标注者

发布时间：2025年02月10日

`LLM应用` `人力资源管理` `激励机制`

> How Humans Help LLMs: Assessing and Incentivizing Human Preference Annotators

# 摘要

> 人工标注的偏好数据在大型语言模型（LLMs）的对齐过程中发挥关键作用。本文探讨了评估标注员表现并激励其提供高质量标注的两个核心问题。语言/文本标注的质量评估面临两大挑战：(i) 标注员之间的固有异质性，这使得依赖真实标签假设的传统方法难以适用；(ii) 标注质量与下游任务性能之间的关系不明确，排除了根据标注数据训练的模型表现推断标注员行为的可能性。

我们构建了一个委托-代理模型，刻画公司与标注员之间的行为互动。该模型合理化了现实中用于激励标注员的奖金机制，这一机制对双方均有益，并强调了评估系统与适当合同方案共同存在的必要性。从技术角度看，我们的分析扩展了委托-代理模型的相关文献，考虑了代理方的连续动作空间。我们展示了在连续动作空间下，最优与次优解之间的差距对于二元合同为【数学公式】，而对于线性合同则为【数学公式】，其中$n$为用于评估表现的样本数量；这一结果与离散动作空间下二元合同已知的【数学公式】差距形成鲜明对比。

本文使用真实偏好标注数据伴随讨论，贯穿始终。


> Human-annotated preference data play an important role in aligning large language models (LLMs). In this paper, we investigate the questions of assessing the performance of human annotators and incentivizing them to provide high-quality annotations. The quality assessment of language/text annotation faces two challenges: (i) the intrinsic heterogeneity among annotators, which prevents the classic methods that assume the underlying existence of a true label; and (ii) the unclear relationship between the annotation quality and the performance of downstream tasks, which excludes the possibility of inferring the annotators' behavior based on the model performance trained from the annotation data. Then we formulate a principal-agent model to characterize the behaviors of and the interactions between the company and the human annotators. The model rationalizes a practical mechanism of a bonus scheme to incentivize annotators which benefits both parties and it underscores the importance of the joint presence of an assessment system and a proper contract scheme. From a technical perspective, our analysis extends the existing literature on the principal-agent model by considering a continuous action space for the agent. We show the gap between the first-best and the second-best solutions (under the continuous action space) is of $Θ(1/\sqrt{n \log n})$ for the binary contracts and $Θ(1/n)$ for the linear contracts, where $n$ is the number of samples used for performance assessment; this contrasts with the known result of $\exp(-Θ(n))$ for the binary contracts when the action space is discrete. Throughout the paper, we use real preference annotation data to accompany our discussions.

[Arxiv](https://arxiv.org/abs/2502.06387)