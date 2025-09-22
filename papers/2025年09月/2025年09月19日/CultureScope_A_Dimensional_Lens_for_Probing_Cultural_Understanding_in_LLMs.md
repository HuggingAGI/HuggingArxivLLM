# CultureScope：探究大型语言模型（LLMs）文化理解的维度透镜

发布时间：2025年09月19日

`LLM应用` `基础理论`

> CultureScope: A Dimensional Lens for Probing Cultural Understanding in LLMs

# 摘要

> 随着大型语言模型（LLMs）在多元文化环境中的应用日益广泛，评估其文化理解能力对确保应用的可信度和文化适配性至关重要。然而，大多数现有评估基准缺乏全面性，且难以在不同文化背景下扩展和适配，这是因为其框架常缺乏成熟文化理论的指导，且依赖专家手动标注。为解决这些问题，我们提出了CultureScope——目前评估LLMs文化理解能力的最全面框架。受文化冰山理论启发，我们设计了全新的文化知识分类维度体系，包含3层共140个维度，可指导特定文化知识库及对应评估数据集的自动化构建，适用于任意语言和文化背景。实验结果显示，我们的方法能有效评估文化理解能力。实验还发现，现有大型语言模型缺乏全面的文化能力，仅整合多语言数据未必能提升其文化理解水平。所有代码和数据文件均已开源，地址为https://github.com/HoganZinger/Culture。

> As large language models (LLMs) are increasingly deployed in diverse cultural environments, evaluating their cultural understanding capability has become essential for ensuring trustworthy and culturally aligned applications. However, most existing benchmarks lack comprehensiveness and are challenging to scale and adapt across different cultural contexts, because their frameworks often lack guidance from well-established cultural theories and tend to rely on expert-driven manual annotations. To address these issues, we propose CultureScope, the most comprehensive evaluation framework to date for assessing cultural understanding in LLMs. Inspired by the cultural iceberg theory, we design a novel dimensional schema for cultural knowledge classification, comprising 3 layers and 140 dimensions, which guides the automated construction of culture-specific knowledge bases and corresponding evaluation datasets for any given languages and cultures. Experimental results demonstrate that our method can effectively evaluate cultural understanding. They also reveal that existing large language models lack comprehensive cultural competence, and merely incorporating multilingual data does not necessarily enhance cultural understanding. All code and data files are available at https://github.com/HoganZinger/Culture

[Arxiv](https://arxiv.org/abs/2509.16188)