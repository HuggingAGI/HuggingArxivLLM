# # 幻灯片检索的最佳方法是什么？多模态、基于标题与混合检索技术的比较研究

发布时间：2025年09月18日

`RAG` `基础理论`

> What's the Best Way to Retrieve Slides? A Comparative Study of Multimodal, Caption-Based, and Hybrid Retrieval Techniques

# 摘要

> 幻灯片组作为连接演示文稿与书面文档的数字报告，是学术和企业场景中传递信息的常用媒介。其多模态特性融合了文本、图像和图表，这给检索增强生成系统带来了挑战——检索质量直接影响下游性能。传统幻灯片检索方法往往对不同模态单独建立索引，这不仅增加了复杂性，还会丢失上下文信息。本文研究了多种高效幻灯片检索方法，包括ColPali等视觉后期交互嵌入模型、视觉重排序器的应用，以及将密集检索与BM25相结合的混合检索技术——这些技术通过文本重排序器和互反排序融合（Reciprocal Rank Fusion）等融合方法进一步增强。此外，本文还评估了一种新型基于视觉语言模型的captioning流水线，与视觉后期交互技术相比，该流水线在保证相当检索性能的同时，显著降低了嵌入存储需求。我们的分析还涵盖了这些方法的实际应用层面，评估了它们的运行时性能、存储需求及检索效果，从而为现实应用中高效稳健的幻灯片检索系统的选型与开发提供实用指导。

> Slide decks, serving as digital reports that bridge the gap between presentation slides and written documents, are a prevalent medium for conveying information in both academic and corporate settings. Their multimodal nature, combining text, images, and charts, presents challenges for retrieval-augmented generation systems, where the quality of retrieval directly impacts downstream performance. Traditional approaches to slide retrieval often involve separate indexing of modalities, which can increase complexity and lose contextual information. This paper investigates various methodologies for effective slide retrieval, including visual late-interaction embedding models like ColPali, the use of visual rerankers, and hybrid retrieval techniques that combine dense retrieval with BM25, further enhanced by textual rerankers and fusion methods like Reciprocal Rank Fusion. A novel Vision-Language Models-based captioning pipeline is also evaluated, demonstrating significantly reduced embedding storage requirements compared to visual late-interaction techniques, alongside comparable retrieval performance. Our analysis extends to the practical aspects of these methods, evaluating their runtime performance and storage demands alongside retrieval efficacy, thus offering practical guidance for the selection and development of efficient and robust slide retrieval systems for real-world applications.

[Arxiv](https://arxiv.org/abs/2509.15211)