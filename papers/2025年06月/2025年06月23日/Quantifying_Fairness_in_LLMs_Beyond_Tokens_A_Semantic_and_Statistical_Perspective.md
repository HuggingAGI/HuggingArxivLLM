# LLM公平性评估新视角：超越token层面，从语义与统计双重视角

发布时间：2025年06月23日

`LLM应用

理由：这篇论文关注的是大型语言模型（LLMs）在生成响应时的公平性问题，特别是针对长文本中的偏见检测。它提出了一种新的统计框架FiSCo，用于评估不同群体之间的语义差异，属于LLM在实际应用中的评估和优化，因此归类为LLM应用。` `公平性评估` `社会公平`

> Quantifying Fairness in LLMs Beyond Tokens: A Semantic and Statistical Perspective

# 摘要

> 大型语言模型（LLMs）生成的响应中常常带有固有偏见，影响了其在现实应用中的可靠性。现有的评估方法往往忽视了长文本响应中的偏见以及LLM输出的内在变异性。为了解决这些挑战，我们提出了FiSCo（细粒度语义计算），这是一种全新的统计框架，旨在通过检测不同人口统计群体在长文本响应中的细微语义差异，评估LLMs在群体层面的公平性。与之前专注于情感或词级比较的工作不同，FiSCo超越了表层分析，深入到主张层面，利用蕴含关系检查来评估不同响应间意义的一致性。我们将模型输出分解为语义上独立的主张，并应用统计假设检验来比较组间和组内的相似性，从而实现对细微偏见的稳健检测。我们正式定义了一种新的群体反事实公平性，并在涵盖性别、种族和年龄的合成数据集和人工标注数据集上验证了FiSCo。实验表明，FiSCo能够更可靠地识别微妙偏见，同时降低了随机LLM变异性的影响，优于多种评估指标。

> Large Language Models (LLMs) often generate responses with inherent biases, undermining their reliability in real-world applications. Existing evaluation methods often overlook biases in long-form responses and the intrinsic variability of LLM outputs. To address these challenges, we propose FiSCo(Fine-grained Semantic Computation), a novel statistical framework to evaluate group-level fairness in LLMs by detecting subtle semantic differences in long-form responses across demographic groups. Unlike prior work focusing on sentiment or token-level comparisons, FiSCo goes beyond surface-level analysis by operating at the claim level, leveraging entailment checks to assess the consistency of meaning across responses. We decompose model outputs into semantically distinct claims and apply statistical hypothesis testing to compare inter- and intra-group similarities, enabling robust detection of subtle biases. We formalize a new group counterfactual fairness definition and validate FiSCo on both synthetic and human-annotated datasets spanning gender, race, and age. Experiments show that FiSco more reliably identifies nuanced biases while reducing the impact of stochastic LLM variability, outperforming various evaluation metrics.

[Arxiv](https://arxiv.org/abs/2506.19028)