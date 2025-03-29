# 实时评估模型：谁最能识别幻觉内容？

发布时间：2025年03月27日

`RAG` `信息检索` `内容安全`

> Real-Time Evaluation Models for RAG: Who Detects Hallucinations Best?

# 摘要

> 本文综述了用于自动检测检索增强生成（RAG）中幻觉的评估模型，并对其在六个RAG应用场景中的性能进行了全面基准测试。本研究纳入的方法包括：LLM-as-a-Judge、Prometheus、Lynx、休斯大厅幻觉评估模型（HHEM）以及可信语言模型（TLM）。这些方法均为无参考方法，无需真实答案或标签即可识别错误的LLM响应。研究发现，在多种RAG应用场景下，其中一些方法始终能以高精度和高召回率检测出错误的RAG响应。

> This article surveys Evaluation models to automatically detect hallucinations in Retrieval-Augmented Generation (RAG), and presents a comprehensive benchmark of their performance across six RAG applications. Methods included in our study include: LLM-as-a-Judge, Prometheus, Lynx, the Hughes Hallucination Evaluation Model (HHEM), and the Trustworthy Language Model (TLM). These approaches are all reference-free, requiring no ground-truth answers/labels to catch incorrect LLM responses. Our study reveals that, across diverse RAG applications, some of these approaches consistently detect incorrect RAG responses with high precision/recall.

[Arxiv](https://arxiv.org/abs/2503.21157)