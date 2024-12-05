# 全球 MMLU：理解并化解多语言评估中的文化与语言偏见

发布时间：2024年12月04日

`LLM应用` `模型评估`

> Global MMLU: Understanding and Addressing Cultural and Linguistic Biases in Multilingual Evaluation

# 摘要

> 多语言数据集中存在的文化偏见，给其作为全球基准的有效性带来了巨大挑战。这些偏见不仅源自语言，还源自解读问题所需的文化知识，致使像 MMLU 这类翻译数据集的实用价值降低。而且，翻译往往会引入一些瑕疵，可能扭曲目标语言中问题的含义或清晰度。在多语言评估中，常见的做法是依赖机器翻译的评估集，但仅翻译数据集难以应对这些挑战。在本研究中，我们探究了这两个问题对多语言评估及后续模型性能的影响。我们对最先进的开放和专有模型进行大规模评估后发现，MMLU 的进展在很大程度上依赖于对以西方为中心概念的学习，全部问题中有 28%需要具备文化敏感性知识。此外，在需要地理知识的问题中，高达 84.9%聚焦于北美或欧洲地区。模型评估的排名会因评估对象是全部问题还是被标注为文化敏感的问题子集而有所不同，这表明盲目依赖翻译的 MMLU 会导致模型排名出现偏差。我们推出了 Global-MMLU，这是改进后的 MMLU，涵盖 42 种语言的评估——通过与有偿的专业和社区标注人员合作来验证翻译质量，同时严格评估原始数据集中的文化偏见，从而提升了整体质量。这个全面的 Global-MMLU 集合还包含被标记为文化敏感和文化无关的特定子集，以便进行更全面、完整的评估。

> Cultural biases in multilingual datasets pose significant challenges for their effectiveness as global benchmarks. These biases stem not only from language but also from the cultural knowledge required to interpret questions, reducing the practical utility of translated datasets like MMLU. Furthermore, translation often introduces artifacts that can distort the meaning or clarity of questions in the target language. A common practice in multilingual evaluation is to rely on machine-translated evaluation sets, but simply translating a dataset is insufficient to address these challenges. In this work, we trace the impact of both of these issues on multilingual evaluations and ensuing model performances. Our large-scale evaluation of state-of-the-art open and proprietary models illustrates that progress on MMLU depends heavily on learning Western-centric concepts, with 28% of all questions requiring culturally sensitive knowledge. Moreover, for questions requiring geographic knowledge, an astounding 84.9% focus on either North American or European regions. Rankings of model evaluations change depending on whether they are evaluated on the full portion or the subset of questions annotated as culturally sensitive, showing the distortion to model rankings when blindly relying on translated MMLU. We release Global-MMLU, an improved MMLU with evaluation coverage across 42 languages -- with improved overall quality by engaging with compensated professional and community annotators to verify translation quality while also rigorously evaluating cultural biases present in the original dataset. This comprehensive Global-MMLU set also includes designated subsets labeled as culturally sensitive and culturally agnostic to allow for more holistic, complete evaluation.

[Arxiv](https://arxiv.org/abs/2412.03304)