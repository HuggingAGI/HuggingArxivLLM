# InfoGain-RAG：基于文档信息增益的重排序与过滤增强检索增强生成

发布时间：2025年09月16日

`RAG` `基础理论`

> InfoGain-RAG: Boosting Retrieval-Augmented Generation via Document Information Gain-based Reranking and Filtering

# 摘要

> 检索增强生成（RAG）已成为解决大型语言模型（LLMs）关键局限的有力方案，例如幻觉问题、知识陈旧及缺乏引用依据等。然而，现有RAG框架常难以判断检索文档是否对答案生成真正有效，这一缺陷导致难以筛除无关甚至误导性内容，进而严重影响最终效果。为此，本文提出文档信息增益（DIG）——一种量化检索文档对正确答案生成贡献的全新指标。DIG通过计算LLM在有无该文档增强时的生成置信度差异，来衡量文档的实际价值。此外，我们还提出InfoGain-RAG框架，它利用DIG分数训练专用重排序器，从精准区分与准确排序双重视角对检索文档进行优先级排序。该方法能有效滤除无关文档并筛选高价值内容，从而提升答案生成质量。在多模型、多基准上的大量实验证实，InfoGain-RAG在单检索器与多检索器两种范式下均显著优于现有方案：具体在NaturalQA数据集上，其精确匹配准确率较朴素RAG、自反思RAG和现代排序式RAG分别提升17.9%、4.5%和12.5%；在所有数据集上，即便是针对先进专有模型GPT-4o，也实现了平均15.3%的性能提升。这些结果验证了InfoGain-RAG的可行性，为多场景下的RAG应用提供了可靠解决方案。

> Retrieval-Augmented Generation (RAG) has emerged as a promising approach to address key limitations of Large Language Models (LLMs), such as hallucination, outdated knowledge, and lacking reference. However, current RAG frameworks often struggle with identifying whether retrieved documents meaningfully contribute to answer generation. This shortcoming makes it difficult to filter out irrelevant or even misleading content, which notably impacts the final performance. In this paper, we propose Document Information Gain (DIG), a novel metric designed to quantify the contribution of retrieved documents to correct answer generation. DIG measures a document's value by computing the difference of LLM's generation confidence with and without the document augmented. Further, we introduce InfoGain-RAG, a framework that leverages DIG scores to train a specialized reranker, which prioritizes each retrieved document from exact distinguishing and accurate sorting perspectives. This approach can effectively filter out irrelevant documents and select the most valuable ones for better answer generation. Extensive experiments across various models and benchmarks demonstrate that InfoGain-RAG can significantly outperform existing approaches, on both single and multiple retrievers paradigm. Specifically on NaturalQA, it achieves the improvements of 17.9%, 4.5%, 12.5% in exact match accuracy against naive RAG, self-reflective RAG and modern ranking-based RAG respectively, and even an average of 15.3% increment on advanced proprietary model GPT-4o across all datasets. These results demonstrate the feasibility of InfoGain-RAG as it can offer a reliable solution for RAG in multiple applications.

[Arxiv](https://arxiv.org/abs/2509.12765)