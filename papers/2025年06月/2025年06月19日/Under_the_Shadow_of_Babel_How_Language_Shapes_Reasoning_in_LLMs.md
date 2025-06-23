# 巴别塔阴影下：语言如何影响LLMs的推理方式

发布时间：2025年06月19日

`LLM理论` `因果推理` `认知科学`

> Under the Shadow of Babel: How Language Shapes Reasoning in LLMs

# 摘要

> 语言不仅是沟通的工具，更是人类认知与推理的媒介。如果如语言相对论所言，语言的结构塑造了认知模式，那么基于人类语言训练的大型语言模型（LLMs）也可能内化了不同语言中嵌入的习惯性逻辑结构。为了验证这一假设，我们引入了BICAUSE，一个用于因果推理的结构化双语数据集，其中包含语义对齐的中英文样本，涵盖正向和反向因果形式。

我们的研究揭示了三个关键发现：首先，LLMs展现出与语言类型相匹配的注意力模式，中文模型更关注原因和句首连接词，而英文模型则表现出更均衡的分布。其次，模型内化了特定于语言的因果词序偏好，并常常 rigidly 将其应用于非典型输入，导致性能下降，尤其是在中文中。最后，当因果推理成功时，模型表示在跨语言的语义对齐抽象中趋于一致，表明存在超越表面形式的共同理解。

总体而言，这些结果表明，LLMs不仅模仿了语言的表面形式，还内化了由语言塑造的推理偏见。这一现象植根于认知语言学理论，通过模型内部结构的分析，首次得到了实证验证。

> Language is not only a tool for communication but also a medium for human cognition and reasoning. If, as linguistic relativity suggests, the structure of language shapes cognitive patterns, then large language models (LLMs) trained on human language may also internalize the habitual logical structures embedded in different languages. To examine this hypothesis, we introduce BICAUSE, a structured bilingual dataset for causal reasoning, which includes semantically aligned Chinese and English samples in both forward and reversed causal forms. Our study reveals three key findings: (1) LLMs exhibit typologically aligned attention patterns, focusing more on causes and sentence-initial connectives in Chinese, while showing a more balanced distribution in English. (2) Models internalize language-specific preferences for causal word order and often rigidly apply them to atypical inputs, leading to degraded performance, especially in Chinese. (3) When causal reasoning succeeds, model representations converge toward semantically aligned abstractions across languages, indicating a shared understanding beyond surface form. Overall, these results suggest that LLMs not only mimic surface linguistic forms but also internalize the reasoning biases shaped by language. Rooted in cognitive linguistic theory, this phenomenon is for the first time empirically verified through structural analysis of model internals.

[Arxiv](https://arxiv.org/abs/2506.16151)