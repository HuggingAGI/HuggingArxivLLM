# 对检索增强生成中上下文利用的现实检验

发布时间：2024年12月22日

`RAG` `语言模型` `自动声明验证`

> A Reality Check on Context Utilisation for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）能够化解语言模型（LM）中内置参数知识的局限性。然而，有关语言模型在现实场景中如何运用不同复杂程度的检索信息这方面的研究，目前仅局限于合成语境。我们推出了 DRUID（检索到的不可靠、不充分及难以理解的语境数据集），其中涵盖了真实世界的查询以及人工标注立场的语境。该数据集基于自动声明验证这一原型任务，而在此任务中，自动检索真实世界的证据极为关键。我们将 DRUID 与合成数据集（CounterFact、ConflictQA）做了对比，发现人工数据集通常难以体现真实世界复杂多样的语境设置。我们指出，合成数据集夸大了真实检索数据中少见的语境特征，致使依据我们新的 ACU 分数所衡量的语境利用结果被夸大。另外，尽管此前的工作主要聚焦于单一语境特征来阐释语境利用情况，但与其他和语境来源相关的属性相比，DRUID 中单一语境属性与 ACU 之间的相关性小得令人意外。总之，我们的工作凸显了开展与真实世界相符的语境利用研究的必要性，以便在真实世界的 RAG 环境中展现并提升性能。

> Retrieval-augmented generation (RAG) helps address the limitations of the parametric knowledge embedded within a language model (LM). However, investigations of how LMs utilise retrieved information of varying complexity in real-world scenarios have been limited to synthetic contexts. We introduce DRUID (Dataset of Retrieved Unreliable, Insufficient and Difficult-to-understand contexts) with real-world queries and contexts manually annotated for stance. The dataset is based on the prototypical task of automated claim verification, for which automated retrieval of real-world evidence is crucial. We compare DRUID to synthetic datasets (CounterFact, ConflictQA) and find that artificial datasets often fail to represent the complex and diverse real-world context settings. We show that synthetic datasets exaggerate context characteristics rare in real retrieved data, which leads to inflated context utilisation results, as measured by our novel ACU score. Moreover, while previous work has mainly focused on singleton context characteristics to explain context utilisation, correlations between singleton context properties and ACU on DRUID are surprisingly small compared to other properties related to context source. Overall, our work underscores the need for real-world aligned context utilisation studies to represent and improve performance in real-world RAG settings.

[Arxiv](https://arxiv.org/abs/2412.17031)