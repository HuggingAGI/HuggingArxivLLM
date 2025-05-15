# 一个多语言、多领域评论数据的多方面标注的可扩展无监督框架

发布时间：2025年05月14日

`LLM应用` `评论分析`

> A Scalable Unsupervised Framework for multi-aspect labeling of Multilingual and Multi-Domain Review Data

# 摘要

> 在线评论数据分析在各行业都至关重要。然而，现有研究多局限于特定领域和语言，且依赖需要大规模标注数据的监督学习方法。本研究提出了一种多语言、可扩展且无监督的跨领域方面检测框架，专为多语言、多领域的评论数据多方面标注而设计。我们对涵盖多个领域的韩语和英语评论数据集进行了自动标注，并通过大量实验评估了生成标签的质量。首先通过聚类提取方面类别候选，然后使用负采样将每条评论表示为带有方面感知的嵌入向量。通过多方面标注和对多个预训练语言模型的微调，我们验证了自动生成标签的有效性。实验结果表明，这些模型表现优异，证明了这些标签适合用于训练。与现有大型语言模型的对比显示，该框架在处理大规模数据时具有更优的一致性和可扩展性。人工评估也证实，自动标签质量可与人工标注相媲美。本研究展示了克服监督方法局限性、适应多语言和多领域环境的多方面标注方法的潜力。未来研究将探索自动评论摘要和人工智能代理的整合，以进一步提升评论分析的效率和深度。

> Effectively analyzing online review data is essential across industries. However, many existing studies are limited to specific domains and languages or depend on supervised learning approaches that require large-scale labeled datasets. To address these limitations, we propose a multilingual, scalable, and unsupervised framework for cross-domain aspect detection. This framework is designed for multi-aspect labeling of multilingual and multi-domain review data. In this study, we apply automatic labeling to Korean and English review datasets spanning various domains and assess the quality of the generated labels through extensive experiments. Aspect category candidates are first extracted through clustering, and each review is then represented as an aspect-aware embedding vector using negative sampling. To evaluate the framework, we conduct multi-aspect labeling and fine-tune several pretrained language models to measure the effectiveness of the automatically generated labels. Results show that these models achieve high performance, demonstrating that the labels are suitable for training. Furthermore, comparisons with publicly available large language models highlight the framework's superior consistency and scalability when processing large-scale data. A human evaluation also confirms that the quality of the automatic labels is comparable to those created manually. This study demonstrates the potential of a robust multi-aspect labeling approach that overcomes limitations of supervised methods and is adaptable to multilingual, multi-domain environments. Future research will explore automatic review summarization and the integration of artificial intelligence agents to further improve the efficiency and depth of review analysis.

[Arxiv](https://arxiv.org/abs/2505.09286)