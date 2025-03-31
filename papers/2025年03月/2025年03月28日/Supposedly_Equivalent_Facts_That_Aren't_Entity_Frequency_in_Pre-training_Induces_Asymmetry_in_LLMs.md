# 表面上等价的事实，实则不然？预训练中实体频率引发LLMs的不对称现象

发布时间：2025年03月28日

`LLM理论` `人工智能`

> Supposedly Equivalent Facts That Aren't? Entity Frequency in Pre-training Induces Asymmetry in LLMs

# 摘要

> 理解和缓解大型语言模型中的幻觉现象对于生成可靠内容至关重要。与以往研究主要关注'LLMs何时会出现幻觉'不同，我们的工作深入解释了'为什么会出现幻觉'，并揭示了模型行为与预训练数据之间的直接联系。具体而言，我们发现模型在识别逻辑上等价的事实时存在一种不对称性，这种不对称性源于实体作为主语和宾语出现频率的差异。由于大多数预训练数据集难以获取，我们利用完全开源的OLMo系列模型，通过分析其Dolma数据集来估算实体频率。我们从Wikidata5M中提取关系事实（表示为三元组），构建了探查数据集以孤立这种不对称性的影响。实验结果显示，尽管在逻辑上等价，但具有高频率主语和低频率宾语的事实比其反向情况更容易被识别。在低频到高频的设置下，这一模式发生逆转，而当两个实体均为高频时，统计上显著的不对称性则不会出现。这些发现不仅凸显了预训练数据在塑造模型预测结果中的关键作用，还为推断封闭或半封闭LLMs的预训练数据特征提供了重要线索。

> Understanding and mitigating hallucinations in Large Language Models (LLMs) is crucial for ensuring reliable content generation. While previous research has primarily focused on "when" LLMs hallucinate, our work explains "why" and directly links model behaviour to the pre-training data that forms their prior knowledge. Specifically, we demonstrate that an asymmetry exists in the recognition of logically equivalent facts, which can be attributed to frequency discrepancies of entities appearing as subjects versus objects. Given that most pre-training datasets are inaccessible, we leverage the fully open-source OLMo series by indexing its Dolma dataset to estimate entity frequencies. Using relational facts (represented as triples) from Wikidata5M, we construct probing datasets to isolate this effect. Our experiments reveal that facts with a high-frequency subject and a low-frequency object are better recognised than their inverse, despite their logical equivalence. The pattern reverses in low-to-high frequency settings, and no statistically significant asymmetry emerges when both entities are high-frequency. These findings highlight the influential role of pre-training data in shaping model predictions and provide insights for inferring the characteristics of pre-training data in closed or partially closed LLMs.

[Arxiv](https://arxiv.org/abs/2503.22362)