# 解释-查询-测试：基于解释与理解差异的LLM自我评估

发布时间：2025年01月20日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）是否真正理解复杂概念，并设计了一个自我评估流程（EQT）来评估模型的理解水平。论文的核心在于对LLMs的理论理解和评估方法的探讨，而不是具体的应用或实现。因此，将其归类为“LLM理论”更为合适。` `模型评估`

> Explain-Query-Test: Self-Evaluating LLMs Via Explanation and Comprehension Discrepancy

# 摘要

> 大型语言模型（LLMs）在生成复杂概念的详细解释方面表现出色，但它们是否真正理解这些概念仍不明确。为评估模型的理解水平，我们设计了一个自我评估流程——解释-查询-测试（EQT）。模型首先根据主题生成摘录，然后基于摘录生成问答对，最后回答问题。有趣的是，EQT生成的问答对的准确性与模型在MMLU-Pro等基准测试中的表现高度相关。这意味着EQT可以预测模型在标准测试中的表现，并仅需主题列表即可对模型进行排名。此外，我们发现模型在生成详细解释与回答相关问题时存在差距，这揭示了当前LLMs在知识表示和推理能力上的局限性。代码已开源：https://github.com/asgsaeid/EQT。

> Large language models (LLMs) have demonstrated remarkable proficiency in generating detailed and coherent explanations of complex concepts. However, the extent to which these models truly comprehend the concepts they articulate remains unclear. To assess the level of comprehension of a model relative to the content it generates, we implemented a self-evaluation pipeline where models: (i) given a topic generate an excerpt with information about the topic, (ii) given an excerpt generate question-answer pairs, and finally (iii) given a question generate an answer. We refer to this self-evaluation approach as Explain-Query-Test (EQT). Interestingly, the accuracy on generated questions resulting from running the EQT pipeline correlates strongly with the model performance as verified by typical benchmarks such as MMLU-Pro. In other words, EQT's performance is predictive of MMLU-Pro's, and EQT can be used to rank models without the need for any external source of evaluation data other than lists of topics of interest. Moreover, our results reveal a disparity between the models' ability to produce detailed explanations and their performance on questions related to those explanations. This gap highlights fundamental limitations in the internal knowledge representation and reasoning abilities of current LLMs. We release the code at https://github.com/asgsaeid/EQT.

[Arxiv](https://arxiv.org/abs/2501.11721)