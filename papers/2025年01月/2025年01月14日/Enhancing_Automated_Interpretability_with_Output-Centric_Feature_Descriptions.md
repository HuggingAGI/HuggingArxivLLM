# 提升自动可解释性：聚焦输出特征描述

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要讨论了如何生成自然语言描述来捕捉LLMs中特征对输出的因果效应，并提出了新的方法来解决当前管道生成描述的问题。这涉及到对LLMs内部机制的理解和改进，属于对LLM理论的研究。` `机器学习`

> Enhancing Automated Interpretability with Output-Centric Feature Descriptions

# 摘要

> 自动化可解释性管道为LLMs中的特征生成自然语言描述，例如植物或句子中的第一个词。这些描述基于激活该特征的输入，这些输入可能是模型表示空间中的维度或方向。然而，识别激活输入成本高昂，且特征在模型行为中的作用既取决于输入如何激活特征，也取决于特征激活如何影响输出。通过转向评估，我们发现当前管道生成的描述未能捕捉特征对输出的因果效应。为此，我们提出了高效的、以输出为中心的特征描述生成方法。这些方法使用特征刺激后权重较高的标记，或直接将词汇“解嵌入”头应用于特征后权重最高的标记。以输出为中心的描述比以输入为中心的描述更好地捕捉了特征对输出的因果效应，而结合两者则能在输入和输出评估中实现最佳性能。最后，我们展示了以输出为中心的描述可用于激活先前被认为是“死亡”特征的输入。

> Automated interpretability pipelines generate natural language descriptions for the concepts represented by features in large language models (LLMs), such as plants or the first word in a sentence. These descriptions are derived using inputs that activate the feature, which may be a dimension or a direction in the model's representation space. However, identifying activating inputs is costly, and the mechanistic role of a feature in model behavior is determined both by how inputs cause a feature to activate and by how feature activation affects outputs. Using steering evaluations, we reveal that current pipelines provide descriptions that fail to capture the causal effect of the feature on outputs. To fix this, we propose efficient, output-centric methods for automatically generating feature descriptions. These methods use the tokens weighted higher after feature stimulation or the highest weight tokens after applying the vocabulary "unembedding" head directly to the feature. Our output-centric descriptions better capture the causal effect of a feature on model outputs than input-centric descriptions, but combining the two leads to the best performance on both input and output evaluations. Lastly, we show that output-centric descriptions can be used to find inputs that activate features previously thought to be "dead".

[Arxiv](https://arxiv.org/abs/2501.08319)