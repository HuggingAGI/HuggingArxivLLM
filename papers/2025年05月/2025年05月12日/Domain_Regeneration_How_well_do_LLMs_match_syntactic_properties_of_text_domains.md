# # **领域再生：LLMs能否精准匹配文本领域的句法特性？** 研究为您揭晓答案！

发布时间：2025年05月12日

`LLM理论

摘要分析：该研究探讨了大型语言模型（LLM）如何近似训练数据分布的能力，分析了模型在不同文本域中的表现，属于对模型工作原理和特性的基础研究。因此，归类为LLM理论。` `文本生成`

> Domain Regeneration: How well do LLMs match syntactic properties of text domains?

# 摘要

> 大型语言模型性能的提升，很可能伴随着其更好地近似训练数据分布的能力。本研究探讨以下问题：大型语言模型能够忠实近似的文本域具备哪些特性，以及它们在多大程度上能够做到这一点？我们采用语料语言学中常用的方法，提示一个常用开源大型语言模型从两个常见于LLM训练数据的宽松授权英文文本域中重新生成文本——维基百科和新闻文本。这种重新生成的范式使我们能够探究在语义可控的设置下，大型语言模型是否能与原始人类文本域保持忠实匹配。我们研究了不同层次的句法抽象，从较为简单的属性，如句子长度和文章可读性，到更复杂且更高阶的属性，如依存标签分布、句法深度和句法复杂度。我们发现，与原始人类文本相比，大多数重新生成的分布表现出均值偏移、标准差降低以及长尾减少。

> Recent improvement in large language model performance have, in all likelihood, been accompanied by improvement in how well they can approximate the distribution of their training data. In this work, we explore the following question: which properties of text domains do LLMs faithfully approximate, and how well do they do so? Applying observational approaches familiar from corpus linguistics, we prompt a commonly used, opensource LLM to regenerate text from two domains of permissively licensed English text which are often contained in LLM training data -- Wikipedia and news text. This regeneration paradigm allows us to investigate whether LLMs can faithfully match the original human text domains in a fairly semantically-controlled setting. We investigate varying levels of syntactic abstraction, from more simple properties like sentence length, and article readability, to more complex and higher order properties such as dependency tag distribution, parse depth, and parse complexity. We find that the majority of the regenerated distributions show a shifted mean, a lower standard deviation, and a reduction of the long tail, as compared to the human originals.

[Arxiv](https://arxiv.org/abs/2505.07784)