# # 大型语言模型中的人格表示定位研究

发布时间：2025年05月30日

`LLM理论` `人工智能` `机器学习`

> Localizing Persona Representations in LLMs

# 摘要

> 我们开展了一项研究，探讨人物角色（由独特的人类特征、价值观和信仰组成）在大型语言模型（LLMs）的表示空间中是如何以及在哪些位置被编码的。通过运用一系列降维和模式识别方法，我们首先识别出在编码这些表示方面差异最大的模型层。接着，我们分析选定层中的激活情况，研究特定人物角色相对于其他角色的编码方式，包括它们共享和独特的嵌入空间。我们发现，在多个预训练的仅解码器型LLMs中，所研究的人物角色仅在解码器层的最后三分之一部分显示出显著的表示空间差异。我们观察到特定伦理视角（如道德虚无主义和功利主义）的激活重叠，表明一定程度的多义性。相比之下，保守主义和自由主义等政治意识形态似乎表现在更为独立的区域。这些发现有助于增进我们对LLMs如何内部表征信息的理解，并为未来在优化LLM输出中特定人类特质的调节提供指导。警告：本文包含可能引起冒犯的示例陈述。


> We present a study on how and where personas -- defined by distinct sets of human characteristics, values, and beliefs -- are encoded in the representation space of large language models (LLMs). Using a range of dimension reduction and pattern recognition methods, we first identify the model layers that show the greatest divergence in encoding these representations. We then analyze the activations within a selected layer to examine how specific personas are encoded relative to others, including their shared and distinct embedding spaces. We find that, across multiple pre-trained decoder-only LLMs, the analyzed personas show large differences in representation space only within the final third of the decoder layers. We observe overlapping activations for specific ethical perspectives -- such as moral nihilism and utilitarianism -- suggesting a degree of polysemy. In contrast, political ideologies like conservatism and liberalism appear to be represented in more distinct regions. These findings help to improve our understanding of how LLMs internally represent information and can inform future efforts in refining the modulation of specific human traits in LLM outputs. Warning: This paper includes potentially offensive sample statements.

[Arxiv](https://arxiv.org/abs/2505.24539)