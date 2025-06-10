# # 大型语言模型中的关联性错误探索

发布时间：2025年06月09日

`LLM理论` `人力资源` `评估系统`

> Correlated Errors in Large Language Models

# 摘要

> 人们普遍认为，通过多样化训练数据、模型架构和供应商可以缓解LLMs的同质化问题。然而，目前尚无实证证据表明不同LLMs之间存在实质性的差异。我们对350多个LLMs进行了大规模实证评估，采用两个流行的排行榜和一个简历筛选任务。结果显示，模型错误之间存在显著相关性——在一个排行榜数据集上，当两个模型同时出错时，它们的错误结果有60%一致。我们发现，共享的架构和供应商是导致模型相关性的主要原因。然而，至关重要的是，即使采用不同的架构和供应商，更大且更准确的模型其错误仍具有高度相关性。最后，我们在两个下游任务中展示了这种相关性的影响：LLM作为评估者和招聘场景——后者进一步印证了关于算法同质化的理论预测。

> Diversity in training data, architecture, and providers is assumed to mitigate homogeneity in LLMs. However, we lack empirical evidence on whether different LLMs differ meaningfully. We conduct a large-scale empirical evaluation on over 350 LLMs overall, using two popular leaderboards and a resume-screening task. We find substantial correlation in model errors -- on one leaderboard dataset, models agree 60% of the time when both models err. We identify factors driving model correlation, including shared architectures and providers. Crucially, however, larger and more accurate models have highly correlated errors, even with distinct architectures and providers. Finally, we show the effects of correlation in two downstream tasks: LLM-as-judge evaluation and hiring -- the latter reflecting theoretical predictions regarding algorithmic monoculture.

[Arxiv](https://arxiv.org/abs/2506.07962)