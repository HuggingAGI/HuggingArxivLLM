# 大型语言模型能否准确捕捉人工标注者之间的意见分歧？

发布时间：2025年06月24日

`LLM应用` `机器学习`

> Can Large Language Models Capture Human Annotator Disagreements?

# 摘要

> 人类标注差异：大型语言模型的评估挑战  
人类标注差异（即标注分歧）在自然语言处理领域普遍存在，通常反映了任务主观性和样本模糊性等重要信息。尽管大型语言模型（LLMs）正越来越多地被用于自动标注以减少人工投入，但对其评估往往集中在预测多数投票的“真实标签”上。然而，这些模型是否也能够捕捉到具有信息价值的标注分歧，目前尚不清楚。  

我们的研究通过全面评估LLMs在无重复人工标签的情况下预测标注分歧的能力，填补了这一空白。研究发现，LLMs在建模分歧方面表现挣扎，而这一点往往会被基于多数标签的评估所忽视。更有趣的是，虽然基于可验证奖励的强化学习（RLVR-style）推理通常能提升LLMs的性能，但在分歧预测任务中却会导致性能下降。  

这一发现凸显了在分歧建模中对LLMs标注器进行评估和改进的迫切需求。代码和数据可在https://github.com/EdisonNi-hku/Disagreement_Prediction获取。

> Human annotation variation (i.e., annotation disagreements) is common in NLP and often reflects important information such as task subjectivity and sample ambiguity. While Large Language Models (LLMs) are increasingly used for automatic annotation to reduce human effort, their evaluation often focuses on predicting the majority-voted "ground truth" labels. It is still unclear, however, whether these models also capture informative human annotation variation. Our work addresses this gap by extensively evaluating LLMs' ability to predict annotation disagreements without access to repeated human labels. Our results show that LLMs struggle with modeling disagreements, which can be overlooked by majority label-based evaluations. Notably, while RLVR-style (Reinforcement learning with verifiable rewards) reasoning generally boosts LLM performance, it degrades performance in disagreement prediction. Our findings highlight the critical need for evaluating and improving LLM annotators in disagreement modeling. Code and data at https://github.com/EdisonNi-hku/Disagreement_Prediction.

[Arxiv](https://arxiv.org/abs/2506.19467)