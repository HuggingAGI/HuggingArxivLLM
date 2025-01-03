# 通用大型语言模型能否胜任英语-泰语机器翻译任务？

发布时间：2024年10月22日

`LLM应用

理由：该论文主要探讨了大型语言模型（LLMs）在低资源和低计算环境下的表现，特别是在英泰机器翻译和代码切换数据集上的表现。这属于LLM在实际应用中的表现和局限性研究，因此归类为LLM应用。` `机器翻译` `低资源计算`

> Can General-Purpose Large Language Models Generalize to English-Thai Machine Translation ?

# 摘要

> 大型语言模型（LLMs）在常见任务上表现出色，但在低资源和低计算环境下泛化能力不足。我们通过测试多种LLMs和专用翻译模型在英泰机器翻译和代码切换数据集上的表现，揭示了这一局限性。研究发现，在4位量化等严格计算限制下，LLMs的翻译效果不佳。而计算需求相当或更低的专用模型则始终表现更优。这凸显了在资源受限情况下，专用模型对保持性能的重要性。

> Large language models (LLMs) perform well on common tasks but struggle with generalization in low-resource and low-computation settings. We examine this limitation by testing various LLMs and specialized translation models on English-Thai machine translation and code-switching datasets. Our findings reveal that under more strict computational constraints, such as 4-bit quantization, LLMs fail to translate effectively. In contrast, specialized models, with comparable or lower computational requirements, consistently outperform LLMs. This underscores the importance of specialized models for maintaining performance under resource constraints.

[Arxiv](https://arxiv.org/abs/2410.17145)