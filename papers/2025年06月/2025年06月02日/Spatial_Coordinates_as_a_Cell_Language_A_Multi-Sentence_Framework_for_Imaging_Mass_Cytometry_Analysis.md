# 细胞语言：多句框架助力成像质谱细胞分析

发布时间：2025年06月02日

`LLM应用

理由：这篇论文探讨了大型语言模型在生物医学数据分析中的具体应用，特别是如何通过创新的方法提升模型在处理单细胞数据和空间信息方面的表现。论文提出了一种新的框架Spatial2Sentence，专注于将复杂的数据整合到自然语言处理中，以提高模型的应用效果和可解释性。因此，它属于LLM应用类别。` `生物医学` `细胞分析`

> Spatial Coordinates as a Cell Language: A Multi-Sentence Framework for Imaging Mass Cytometry Analysis

# 摘要

> 图像质量细胞计量（IMC）结合质谱流式细胞术的分析能力，实现了细胞表型的高维空间分析。近期研究表明，大型语言模型（LLMs）能够将基因或蛋白质表达转化为生物背景，从而提取细胞状态。然而，现有的单细胞LLMs面临两大挑战：一是难以有效整合空间坐标并编码空间背景为文本；二是无法处理细胞间的相互作用，限制了对生物关系的捕捉能力。

为了解决这些问题，我们提出了Spatial2Sentence，这是一种新颖的多句子表达方法框架，能够将单细胞表达和空间信息整合到自然语言中。通过构建表达相似性和距离矩阵，Spatial2Sentence将空间相邻且表达相似的细胞配对作为正样本，而将空间遥远且表达差异大的细胞作为负样本。这些多句子表达使LLMs能够同时在表达和空间背景下学习细胞间相互作用。

通过多任务学习，Spatial2Sentence在预处理后的IMC数据集上超越了现有的单细胞LLMs。在糖尿病数据集上，其细胞类型分类的准确率提高了5.98%，临床状态预测的准确率提升了4.18%，同时增强了模型的可解释性。源代码可在以下链接获取：https://github.com/UNITES-Lab/Spatial2Sentence。


> Image mass cytometry (IMC) enables high-dimensional spatial profiling by combining mass cytometry's analytical power with spatial distributions of cell phenotypes. Recent studies leverage large language models (LLMs) to extract cell states by translating gene or protein expression into biological context. However, existing single-cell LLMs face two major challenges: (1) Integration of spatial information: they struggle to generalize spatial coordinates and effectively encode spatial context as text, and (2) Treating each cell independently: they overlook cell-cell interactions, limiting their ability to capture biological relationships. To address these limitations, we propose Spatial2Sentence, a novel framework that integrates single-cell expression and spatial information into natural language using a multi-sentence approach. Spatial2Sentence constructs expression similarity and distance matrices, pairing spatially adjacent and expressionally similar cells as positive pairs while using distant and dissimilar cells as negatives. These multi-sentence representations enable LLMs to learn cellular interactions in both expression and spatial contexts. Equipped with multi-task learning, Spatial2Sentence outperforms existing single-cell LLMs on preprocessed IMC datasets, improving cell-type classification by 5.98% and clinical status prediction by 4.18% on the diabetes dataset while enhancing interpretability. The source code can be found here: https://github.com/UNITES-Lab/Spatial2Sentence.

[Arxiv](https://arxiv.org/abs/2506.01918)