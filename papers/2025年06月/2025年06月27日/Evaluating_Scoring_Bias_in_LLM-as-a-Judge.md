# 评估LLM作为评分裁判的偏见

发布时间：2025年06月27日

`LLM应用` `偏好学习`

> Evaluating Scoring Bias in LLM-as-a-Judge

# 摘要

> 大型语言模型（LLMs）的卓越性能催生了“LLM作为裁判”的概念，其中LLMs被用作复杂任务的评估者。这一概念已在自然语言处理（NLP）、偏好学习以及多个特定领域得到广泛应用。然而，LLM作为裁判时存在多种偏见，严重影响了评判的公平性和可靠性。目前研究主要集中在基于比较的评估上，而对基于评分评估中的偏见进行系统性研究仍十分有限。因此，我们将评分偏见定义为：当评分裁判模型受到与偏见相关的扰动时，评分结果会有所不同。我们提供了一个精心设计的框架，以全面评估评分偏见。通过数据合成，我们增强了现有基准测试，构建了评估数据集，并设计了多维度评估指标。实验结果表明，现有裁判模型的评分稳定性受到了评分偏见的干扰。进一步探索性实验和讨论为评分提示模板设计以及在评分标准、评分标识符和参考答案选择等方面缓解评分偏见提供了有价值的见解。

> The remarkable performance of Large Language Models (LLMs) gives rise to``LLM-as-a-Judge'', where LLMs are employed as evaluators for complex tasks. Moreover, it has been widely adopted across fields such as Natural Language Processing (NLP), preference learning, and various specific domains. However, there are various biases within LLM-as-a-Judge, which adversely affect the fairness and reliability of judgments. Current research on evaluating or mitigating bias in LLM-as-a-Judge predominantly focuses on comparison-based evaluations, while systematic investigations into bias in scoring-based evaluations remain limited. Therefore, we define scoring bias in LLM-as-a-Judge as the scores differ when scoring judge models are bias-related perturbed, and provide a well-designed framework to comprehensively evaluate scoring bias. We augment existing LLM-as-a-Judge benchmarks through data synthesis to construct our evaluation dataset and design multi-faceted evaluation metrics. Our experimental results demonstrate that the scoring stability of existing judge models is disrupted by scoring biases. Further exploratory experiments and discussions provide valuable insights into the design of scoring prompt templates and the mitigation of scoring biases on aspects such as score rubrics, score IDs, and reference answer selection.

[Arxiv](https://arxiv.org/abs/2506.22316)