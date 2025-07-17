# 公平奖励模型引领大型语言模型决策之路

发布时间：2025年07月15日

`LLM应用`

> Guiding LLM Decision-Making with Fairness Reward Models

# 摘要

> 大型语言模型正越来越多地被用于支持高风险决策，这些决策可能影响到谁能够获得保释或贷款。传统的链式思维采样虽然能提升平均决策准确率，但也会放大不公平偏见。为了解决这一挑战并确保推理模型在高风险决策中的可信应用，我们提出了一种训练通用公平奖励模型（FRM）的框架。我们的模型为大型语言模型的推理过程赋予公平性评分，使系统能够在整合推理链的决策时，降低偏见路径的权重，转而支持更加公平的推理路径。我们证明，只需在一个由弱监督、大型语言模型标注的偏见推理与无偏见推理示例集上训练的单一公平奖励模型，无需额外微调，即可跨任务、跨领域和跨模型家族进行迁移。将其应用于包括再犯预测和社会媒体内容审核在内的现实世界决策任务中，我们发现该方法不仅能够持续提升公平性，同时还能达到甚至超越基线准确率。

> Large language models are increasingly used to support high-stakes decisions, potentially influencing who is granted bail or receives a loan. Naive chain-of-thought sampling can improve average decision accuracy, but has also been shown to amplify unfair bias. To address this challenge and enable the trustworthy use of reasoning models in high-stakes decision-making, we propose a framework for training a generalizable Fairness Reward Model (FRM). Our model assigns a fairness score to LLM reasoning, enabling the system to down-weight biased trajectories and favor equitable ones when aggregating decisions across reasoning chains. We show that a single Fairness Reward Model, trained on weakly supervised, LLM-annotated examples of biased versus unbiased reasoning, transfers across tasks, domains, and model families without additional fine-tuning. Applied to real-world decision-making tasks including recidivism prediction and social media moderation, we show that our approach consistently improves fairness while matching, or even surpassing, baseline accuracy.

[Arxiv](https://arxiv.org/abs/2507.11344)