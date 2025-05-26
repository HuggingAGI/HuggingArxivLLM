# 理解价值神经元如何影响 LLM 中特定值的生成过程

发布时间：2025年05月23日

`LLM理论

理由：这篇论文探讨了大型语言模型内部价值表示的机制，通过构建数据集和开发神经元识别方法，深入分析了模型内部的价值对齐问题。研究重点在于模型的内部机制和理论分析，属于LLM理论范畴。` `心理学`

> Understanding How Value Neurons Shape the Generation of Specified Values in LLMs

# 摘要

> 大型语言模型 (LLMs) 快速融入社会应用，引发了对其与普世伦理原则对齐的日益加剧的担忧。尽管在行为对齐方面有所进展，但模型内部的价值表示仍然不透明。当前方法难以系统性解释价值如何编码到神经架构中，受限于侧重表面判断而非机制分析的数据集。我们引入了基于 Schwartz 价值观调查的机制可解释性框架 ValueLocate，以填补这一空白。我们的方法首先构建了 ValueInsight 数据集，通过现实世界的行为情境具体化四个普遍价值维度。利用此数据集，我们开发了一种神经元识别方法，通过计算对立价值方面之间的激活差异，实现对价值关键神经元的精准定位，无需依赖计算密集的归因方法。我们的验证方法表明，针对性操作这些神经元能有效改变模型的价值取向，证实了神经元与价值表示之间的因果关系。这项工作通过连接心理价值框架与 LLM 中的神经元分析，为价值对齐奠定了基础。

> Rapid integration of large language models (LLMs) into societal applications has intensified concerns about their alignment with universal ethical principles, as their internal value representations remain opaque despite behavioral alignment advancements. Current approaches struggle to systematically interpret how values are encoded in neural architectures, limited by datasets that prioritize superficial judgments over mechanistic analysis. We introduce ValueLocate, a mechanistic interpretability framework grounded in the Schwartz Values Survey, to address this gap. Our method first constructs ValueInsight, a dataset that operationalizes four dimensions of universal value through behavioral contexts in the real world. Leveraging this dataset, we develop a neuron identification method that calculates activation differences between opposing value aspects, enabling precise localization of value-critical neurons without relying on computationally intensive attribution methods. Our proposed validation method demonstrates that targeted manipulation of these neurons effectively alters model value orientations, establishing causal relationships between neurons and value representations. This work advances the foundation for value alignment by bridging psychological value frameworks with neuron analysis in LLMs.

[Arxiv](https://arxiv.org/abs/2505.17712)