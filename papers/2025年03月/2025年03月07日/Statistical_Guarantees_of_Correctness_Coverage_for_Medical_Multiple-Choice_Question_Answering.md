# 医学选择题解答的正确性覆盖统计保障

发布时间：2025年03月07日

`LLM应用` `问答系统`

> Statistical Guarantees of Correctness Coverage for Medical Multiple-Choice Question Answering

# 摘要

> 大型语言模型（LLMs）在现实世界中的问答（QA）应用中越来越普及。然而，LLMs生成幻觉和非事实信息的问题在高风险医疗任务中引发了对其可靠性的质疑。Conformal prediction（CP）以其模型不可知性和分布自由性著称，能够在分类任务中创建统计上严谨的预测集。在本研究中，我们首次将CP框架引入医疗多选题问答（MCQA）任务，通过结合非符合性评分与基于自我一致性理论的正确选项频率评分，且无需访问模型内部信息。考虑到适应后的CP框架仅能控制（误）覆盖率，我们引入了一个风险控制框架，该框架通过设计一个单调递减的损失函数来管理特定任务的指标。我们使用4个现成的LLMs在3个流行的医疗MCQA数据集上评估我们的框架。实证结果表明，我们在测试集上实现了用户指定的平均（或边缘）错误率。此外，我们发现测试集上的平均预测集大小（APSS）随着风险水平的增加而减少，这为评估LLMs的不确定性提供了一个有前景的评估指标。

> Large language models (LLMs) are increasingly deployed in real-world question-answering (QA) applications. However, LLMs have been proven to generate hallucinations and nonfactual information, undermining their trustworthiness in high-stakes medical tasks. Conformal prediction (CP) is well-known to be model-agnostic and distribution-free, which creates statistically rigorous prediction sets in classification tasks. In this work, we for the first time adapt the CP framework to medical multiple-choice question-answering (MCQA) tasks, by correlating the nonconformity score with the frequency score of correct options grounded in self-consistency theory, assuming no access to internal model information. Considering that the adapted CP framework can only control the (mis)coverage rate, we employ a risk control framework, which can manage task-specific metrics by devising a monotonically decreasing loss function. We evaluate our framework on 3 popular medical MCQA datasets utilizing 4 ``off-the-shelf'' LLMs. Empirical results demonstrate that we achieve user-specified average (or marginal) error rates on the test set. Furthermore, we observe that the average prediction set size (APSS) on the test set decreases as the risk level increases, which concludes a promising evaluation metric for the uncertainty of LLMs.

[Arxiv](https://arxiv.org/abs/2503.05505)