# 大型语言模型中的叙事聚类探索：BERT分层分析

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要探讨了BERT模型的内部机制，特别是其在处理叙事内容和作者风格时的聚类能力。研究通过分析BERT的逐层激活，揭示了模型在处理语义内容和风格特征时的不同表现。这些发现有助于我们更好地理解Transformer模型的表征能力和处理层次，属于对大型语言模型（LLM）内部工作机制的理论研究。因此，将其分类为“LLM理论”是合适的。` `认知科学`

> Exploring Narrative Clustering in Large Language Models: A Layerwise Analysis of BERT

# 摘要

> 本研究深入探讨了基于Transformer的大型语言模型BERT的内部机制，特别关注其在各层中对叙事内容和作者风格的聚类能力。我们利用GPT-4生成的多样化叙事数据集，分析了BERT的逐层激活，揭示了局部神经处理的模式。通过主成分分析（PCA）和多维尺度分析（MDS）等降维技术，我们发现BERT在后层中对叙事内容表现出显著的聚类，且聚类逐渐紧凑和明显。尽管当叙事被重述为不同文本类型（如寓言、科幻、儿童故事）时，风格聚类可能较强，但对于特定作者的风格，聚类现象较弱。这些发现表明，BERT更倾向于处理语义内容而非风格特征，为我们理解其表征能力和处理层次提供了新的视角。本研究为理解Transformer模型如何编码语言信息提供了重要见解，并为未来人工智能与认知神经科学的跨学科研究奠定了基础。

> This study investigates the internal mechanisms of BERT, a transformer-based large language model, with a focus on its ability to cluster narrative content and authorial style across its layers. Using a dataset of narratives developed via GPT-4, featuring diverse semantic content and stylistic variations, we analyze BERT's layerwise activations to uncover patterns of localized neural processing. Through dimensionality reduction techniques such as Principal Component Analysis (PCA) and Multidimensional Scaling (MDS), we reveal that BERT exhibits strong clustering based on narrative content in its later layers, with progressively compact and distinct clusters. While strong stylistic clustering might occur when narratives are rephrased into different text types (e.g., fables, sci-fi, kids' stories), minimal clustering is observed for authorial style specific to individual writers. These findings highlight BERT's prioritization of semantic content over stylistic features, offering insights into its representational capabilities and processing hierarchy. This study contributes to understanding how transformer models like BERT encode linguistic information, paving the way for future interdisciplinary research in artificial intelligence and cognitive neuroscience.

[Arxiv](https://arxiv.org/abs/2501.08053)