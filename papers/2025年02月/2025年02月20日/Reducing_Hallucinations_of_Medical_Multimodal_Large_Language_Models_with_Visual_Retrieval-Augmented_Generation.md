# 基于视觉检索增强生成的医学多模态大型语言模型幻觉减少方法

发布时间：2025年02月20日

`RAG` `医疗图像分析`

> Reducing Hallucinations of Medical Multimodal Large Language Models with Visual Retrieval-Augmented Generation

# 摘要

> 多模态大型语言模型 (MLLMs) 在视觉和文本任务中已经展现出了令人印象深刻的性能。然而，在医疗等细节至上的领域，幻觉依然是一个严峻挑战。本研究中，我们探讨了如何优化 MLLMs 以支持 Visual RAG（V-RAG），这是一种结合检索图像中的文本和视觉数据的增强生成框架。通过在 MIMIC-CXR 胸部 X 光片报告生成和 Multicare 医疗图像描述生成数据集上的实验，我们发现 Visual RAG 显著提升了实体探查的准确性，即判断医学实体是否由图像支持。值得注意的是，这种提升不仅体现在常见实体上，更惠及了罕见实体，而这些实体往往缺乏充足的训练数据支持。在实际应用中，我们将 V-RAG 与实体探查相结合，有效纠正幻觉现象，生成更为精准的临床 X 光报告，最终获得了更高的 RadGraph-F1 评分。

> Multimodal Large Language Models (MLLMs) have shown impressive performance in vision and text tasks. However, hallucination remains a major challenge, especially in fields like healthcare where details are critical. In this work, we show how MLLMs may be enhanced to support Visual RAG (V-RAG), a retrieval-augmented generation framework that incorporates both text and visual data from retrieved images. On the MIMIC-CXR chest X-ray report generation and Multicare medical image caption generation datasets, we show that Visual RAG improves the accuracy of entity probing, which asks whether a medical entities is grounded by an image. We show that the improvements extend both to frequent and rare entities, the latter of which may have less positive training data. Downstream, we apply V-RAG with entity probing to correct hallucinations and generate more clinically accurate X-ray reports, obtaining a higher RadGraph-F1 score.

[Arxiv](https://arxiv.org/abs/2502.15040)