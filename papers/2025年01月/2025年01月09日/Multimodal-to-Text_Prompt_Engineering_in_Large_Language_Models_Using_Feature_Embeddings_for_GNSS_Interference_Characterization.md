# 基于特征嵌入的多模态到文本提示工程在大型语言模型中的应用：GNSS干扰特征描述

发布时间：2025年01月09日

`LLM应用

**理由**：这篇论文主要探讨了如何利用大型语言模型（LLMs）在GNSS干扰监测领域进行应用，特别是通过LLaVA从知识库中检索信息，并通过提示工程解析干扰和环境因素。这属于LLM在实际任务中的应用，因此分类为LLM应用。` `卫星导航` `信号处理`

> Multimodal-to-Text Prompt Engineering in Large Language Models Using Feature Embeddings for GNSS Interference Characterization

# 摘要

> 大型语言模型（LLMs）作为高级AI系统，广泛应用于自然语言处理（NLP）、信息检索和推荐系统等领域。尽管LLMs具备强大的适应性和高效性，但在信号处理任务中，尤其是在全球导航卫星系统（GNSS）干扰监测领域，其潜力尚未被充分挖掘。GNSS干扰监测对于确保车辆定位的可靠性至关重要，这是众多应用的核心需求。然而，GNSS定位易受干扰设备影响，导致精度下降。本文的主要目标是识别、分类并减轻这些干扰。由于多径效应、多种干扰类型、传感器特性差异以及卫星星座的复杂性，解释GNSS快照及相关干扰面临巨大挑战。本文从大规模GNSS数据集中提取特征，利用LLaVA从知识库中检索相关信息，并通过提示工程解析干扰和环境因素，同时使用t-SNE分析特征嵌入。研究结果表明，所提出的方法能够在GNSS上下文中进行视觉和逻辑推理，并且在干扰分类任务中，我们的方法优于当前最先进的机器学习模型。

> Large language models (LLMs) are advanced AI systems applied across various domains, including NLP, information retrieval, and recommendation systems. Despite their adaptability and efficiency, LLMs have not been extensively explored for signal processing tasks, particularly in the domain of global navigation satellite system (GNSS) interference monitoring. GNSS interference monitoring is essential to ensure the reliability of vehicle localization on roads, a critical requirement for numerous applications. However, GNSS-based positioning is vulnerable to interference from jamming devices, which can compromise its accuracy. The primary objective is to identify, classify, and mitigate these interferences. Interpreting GNSS snapshots and the associated interferences presents significant challenges due to the inherent complexity, including multipath effects, diverse interference types, varying sensor characteristics, and satellite constellations. In this paper, we extract features from a large GNSS dataset and employ LLaVA to retrieve relevant information from an extensive knowledge base. We employ prompt engineering to interpret the interferences and environmental factors, and utilize t-SNE to analyze the feature embeddings. Our findings demonstrate that the proposed method is capable of visual and logical reasoning within the GNSS context. Furthermore, our pipeline outperforms state-of-the-art machine learning models in interference classification tasks.

[Arxiv](https://arxiv.org/abs/2501.05079)