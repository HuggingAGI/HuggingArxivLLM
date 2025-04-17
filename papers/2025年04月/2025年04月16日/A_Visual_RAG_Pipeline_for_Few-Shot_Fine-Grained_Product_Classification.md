# 基于视觉RAG管道的少量样本细粒度产品分类

发布时间：2025年04月16日

`RAG` `计算机视觉`

> A Visual RAG Pipeline for Few-Shot Fine-Grained Product Classification

# 摘要

> 尽管学习和计算机视觉算法发展迅速，细粒度分类（FGC）在许多实际相关应用中仍然是一个开放性问题。例如，在零售领域，快速变化且视觉上高度相似的产品及其属性的识别，对于自动化价格监控和产品推荐至关重要。本文提出了一种结合检索增强生成（RAG）方法和视觉语言模型（VLMs）的新型视觉RAG管道，用于少样本细粒度分类。该视觉RAG管道可以从各种零售商的广告传单中提取产品和促销数据，并同时预测细粒度的产品ID以及价格和折扣信息。与之前的方法相比，视觉RAG管道的关键特性是无需重新训练，只需通过向RAG数据库添加少量类别样本即可预测新型产品。在比较了GPT-4o [23]、GPT-4o-mini [24]和Gemini 2.0 Flash [10]等多个VLM后端后，我们的方法在多样化的数据集上达到了86.8%的准确率。

> Despite the rapid evolution of learning and computer vision algorithms, Fine-Grained Classification (FGC) still poses an open problem in many practically relevant applications. In the retail domain, for example, the identification of fast changing and visually highly similar products and their properties are key to automated price-monitoring and product recommendation. This paper presents a novel Visual RAG pipeline that combines the Retrieval Augmented Generation (RAG) approach and Vision Language Models (VLMs) for few-shot FGC. This Visual RAG pipeline extracts product and promotion data in advertisement leaflets from various retailers and simultaneously predicts fine-grained product ids along with price and discount information. Compared to previous approaches, the key characteristic of the Visual RAG pipeline is that it allows the prediction of novel products without re-training, simply by adding a few class samples to the RAG database. Comparing several VLM back-ends like GPT-4o [23], GPT-4o-mini [24], and Gemini 2.0 Flash [10], our approach achieves 86.8% accuracy on a diverse dataset.

[Arxiv](https://arxiv.org/abs/2504.11838)