# 量化LLM公平性：语义与统计视角下的新维度

发布时间：2025年06月23日

`LLM理论

理由：这篇论文专注于研究大型语言模型（LLMs）的偏见问题，并提出了一种新的统计框架FiSCo，用于评估LLMs的群体层面公平性。它探讨了LLMs生成回复中的固有偏见和内在变异性，并提出了一种新的评估方法，这属于LLMs的理论分析和改进。因此，它应归类为LLM理论。`

> Quantifying Fairness in LLMs Beyond Tokens: A Semantic and Statistical Perspective

# 摘要

> 大型语言模型（LLMs）生成的回复往往带有固有偏见，这严重影响了其在实际应用中的可靠性。现有的评估方法通常忽视了长文本回复中的偏见以及LLM输出的内在变异性。为了解决这些挑战，我们提出了FiSCo（细粒度语义计算），这是一种全新的统计框架，旨在通过检测长文本回复在不同人口统计学群体之间的细微语义差异，评估LLMs的群体层面公平性。

与之前专注于情感或词级别比较的工作不同，FiSCo超越了表面分析，从声明级别进行操作，利用蕴含检查来评估不同回复之间意义的一致性。我们将模型输出分解为语义上不同的声明，并应用统计假设检验来比较组间和组内的相似性，从而实现对细微偏见的有力检测。我们正式定义了一种新的群体反事实公平性，并在涵盖性别、种族和年龄的合成数据集和人工标注数据集上验证了FiSCo。

实验结果表明，FiSCo不仅更可靠地识别细微偏见，还有效减少了随机LLM变异性的影响，优于各种传统评估指标。

> Large Language Models (LLMs) often generate responses with inherent biases, undermining their reliability in real-world applications. Existing evaluation methods often overlook biases in long-form responses and the intrinsic variability of LLM outputs. To address these challenges, we propose FiSCo(Fine-grained Semantic Computation), a novel statistical framework to evaluate group-level fairness in LLMs by detecting subtle semantic differences in long-form responses across demographic groups. Unlike prior work focusing on sentiment or token-level comparisons, FiSCo goes beyond surface-level analysis by operating at the claim level, leveraging entailment checks to assess the consistency of meaning across responses. We decompose model outputs into semantically distinct claims and apply statistical hypothesis testing to compare inter- and intra-group similarities, enabling robust detection of subtle biases. We formalize a new group counterfactual fairness definition and validate FiSCo on both synthetic and human-annotated datasets spanning gender, race, and age. Experiments show that FiSco more reliably identifies nuanced biases while reducing the impact of stochastic LLM variability, outperforming various evaluation metrics.

[Arxiv](https://arxiv.org/abs/2506.19028)