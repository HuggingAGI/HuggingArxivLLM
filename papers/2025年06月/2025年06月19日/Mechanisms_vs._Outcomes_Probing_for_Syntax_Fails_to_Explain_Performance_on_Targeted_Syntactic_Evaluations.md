# 机制与结果：句法机制的探究无法解释特定句法评估的性能表现

发布时间：2025年06月19日

`LLM理论

摘要讨论了大型语言模型（LLMs）在句法理解和表示方面的内在机制，探讨了探查方法在模型内部句法表示中的应用及其与下游任务表现的关系。这属于对模型内部工作原理和理论的研究，因此归类为LLM理论。` `人工智能`

> Mechanisms vs. Outcomes: Probing for Syntax Fails to Explain Performance on Targeted Syntactic Evaluations

# 摘要

> 大型语言模型（LLMs）在处理和生成文本时展现出对句法的强劲掌握能力。这表明模型可能已经内在化了对层次句法和依存关系的理解，但它们如何精确地表示句法结构仍然是可解释性研究中的一个开放问题。探查提供了一种识别句法在激活中被线性编码机制的方法，然而，目前还没有全面的研究能够确定模型的探查准确性是否可靠地预测其下游句法性能。我们采用“机制与结果”的框架，评估了32个开放权重的Transformer模型，发现通过探查提取的句法特征无法预测针对句法评估的英文语言现象的结果。我们的研究结果突显了通过探查发现的潜在句法表示与下游任务中可观察到的句法行为之间存在显著的脱节。

> Large Language Models (LLMs) exhibit a robust mastery of syntax when processing and generating text. While this suggests internalized understanding of hierarchical syntax and dependency relations, the precise mechanism by which they represent syntactic structure is an open area within interpretability research. Probing provides one way to identify the mechanism of syntax being linearly encoded in activations, however, no comprehensive study has yet established whether a model's probing accuracy reliably predicts its downstream syntactic performance. Adopting a "mechanisms vs. outcomes" framework, we evaluate 32 open-weight transformer models and find that syntactic features extracted via probing fail to predict outcomes of targeted syntax evaluations across English linguistic phenomena. Our results highlight a substantial disconnect between latent syntactic representations found via probing and observable syntactic behaviors in downstream tasks.

[Arxiv](https://arxiv.org/abs/2506.16678)