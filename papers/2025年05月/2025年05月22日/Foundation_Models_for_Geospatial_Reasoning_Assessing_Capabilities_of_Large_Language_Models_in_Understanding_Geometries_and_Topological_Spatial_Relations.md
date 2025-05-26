# # 基础模型在地理空间推理中的应用：评估大型语言模型在几何形状及拓扑空间关系理解上的能力

发布时间：2025年05月22日

`LLM应用` `地理空间` `AI模型`

> Foundation Models for Geospatial Reasoning: Assessing Capabilities of Large Language Models in Understanding Geometries and Topological Spatial Relations

# 摘要

> 直接将AI基础模型应用于地理空间数据集仍然面临诸多挑战，主要源于模型在处理地理实体（尤其是向量几何和复杂空间关系描述）方面的能力限制。为解决这些问题，我们研究了WKT表示法及其空间关系在GPT-3.5-turbo、GPT-4和DeepSeek-R1-14B等大语言模型中的保留情况。我们的工作流程采用了三种方法进行空间推理任务的对比：基于几何嵌入、基于提示工程和基于日常语言的评估。实验结果显示，基于嵌入和提示工程的GPT模型在地理空间问答任务中，对几何体间拓扑关系的识别准确率平均超过0.6。其中，GPT-4通过少量样本提示表现最佳，拓扑推理准确率高达0.66。此外，GPT推理器能准确理解逆拓扑关系，且结合LLM生成的几何体可提升地理检索效果。GPT-4还具备将地点俗语转化为正式拓扑关系的能力，添加几何或地点上下文可提升推理精度，但效果因情况而异。这些成果为开发具备地理推理能力的地理基础模型提供了宝贵参考。

> Applying AI foundation models directly to geospatial datasets remains challenging due to their limited ability to represent and reason with geographical entities, specifically vector-based geometries and natural language descriptions of complex spatial relations. To address these issues, we investigate the extent to which a well-known-text (WKT) representation of geometries and their spatial relations (e.g., topological predicates) are preserved during spatial reasoning when the geospatial vector data are passed to large language models (LLMs) including GPT-3.5-turbo, GPT-4, and DeepSeek-R1-14B. Our workflow employs three distinct approaches to complete the spatial reasoning tasks for comparison, i.e., geometry embedding-based, prompt engineering-based, and everyday language-based evaluation. Our experiment results demonstrate that both the embedding-based and prompt engineering-based approaches to geospatial question-answering tasks with GPT models can achieve an accuracy of over 0.6 on average for the identification of topological spatial relations between two geometries. Among the evaluated models, GPT-4 with few-shot prompting achieved the highest performance with over 0.66 accuracy on topological spatial relation inference. Additionally, GPT-based reasoner is capable of properly comprehending inverse topological spatial relations and including an LLM-generated geometry can enhance the effectiveness for geographic entity retrieval. GPT-4 also exhibits the ability to translate certain vernacular descriptions about places into formal topological relations, and adding the geometry-type or place-type context in prompts may improve inference accuracy, but it varies by instance. The performance of these spatial reasoning tasks offers valuable insights for the refinement of LLMs with geographical knowledge towards the development of geo-foundation models capable of geospatial reasoning.

[Arxiv](https://arxiv.org/abs/2505.17136)