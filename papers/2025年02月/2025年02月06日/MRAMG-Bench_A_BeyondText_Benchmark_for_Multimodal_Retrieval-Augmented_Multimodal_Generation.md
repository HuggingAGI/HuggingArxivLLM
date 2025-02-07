# MRAMG-Bench: 超越文本的多模态检索增强生成基准

发布时间：2025年02月06日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术的扩展，特别是多模态检索增强多模态生成（MRAMG）任务。论文提出了一个新的评估基准（MRAMG-Bench）和一个高效的多模态答案生成框架，这些都是RAG技术的具体应用和扩展。因此，这篇论文应归类为RAG。` `多模态生成` `问答系统`

> MRAMG-Bench: A BeyondText Benchmark for Multimodal Retrieval-Augmented Multimodal Generation

# 摘要

> # 摘要
近期，检索增强生成（RAG）技术的突破显著提升了生成模型的响应准确性和相关性，这得益于外部知识的整合。然而，现有的RAG方法在多模态场景下仍主要提供纯文本答案。为此，我们提出了多模态检索增强多模态生成（MRAMG）任务，旨在生成结合文本和图像的答案，充分利用语料库中的多模态数据。尽管这一任务至关重要，但目前尚缺乏一个全面的评估基准。为此，我们推出了MRAMG-Bench，这是一个精心设计、人工标注的数据集，包含4,346份文档、14,190张图像和4,800个问答对，涵盖网络数据、学术论文和生活方式三大类别。该数据集不仅包含多种难度级别，还涉及复杂的多图像场景，为多模态生成任务的评估提供了坚实基础。为了确保评估的严谨性，MRAMG-Bench引入了一套全面的统计和基于LLM的指标，能够深入分析流行生成模型在MRAMG任务中的表现。此外，我们还提出了一种高效的多模态答案生成框架，结合LLM和MLLM生成多模态响应。数据集已开放访问：https://huggingface.co/MRAMG。

> Recent advancements in Retrieval-Augmented Generation (RAG) have shown remarkable performance in enhancing response accuracy and relevance by integrating external knowledge into generative models. However, existing RAG methods primarily focus on providing text-only answers, even in multimodal retrieval-augmented generation scenarios. In this work, we introduce the Multimodal Retrieval-Augmented Multimodal Generation (MRAMG) task, which aims to generate answers that combine both text and images, fully leveraging the multimodal data within a corpus. Despite the importance of this task, there is a notable absence of a comprehensive benchmark to effectively evaluate MRAMG performance. To bridge this gap, we introduce the MRAMG-Bench, a carefully curated, human-annotated dataset comprising 4,346 documents, 14,190 images, and 4,800 QA pairs, sourced from three categories: Web Data, Academic Papers, and Lifestyle. The dataset incorporates diverse difficulty levels and complex multi-image scenarios, providing a robust foundation for evaluating multimodal generation tasks. To facilitate rigorous evaluation, our MRAMG-Bench incorporates a comprehensive suite of both statistical and LLM-based metrics, enabling a thorough analysis of the performance of popular generative models in the MRAMG task. Besides, we propose an efficient multimodal answer generation framework that leverages both LLMs and MLLMs to generate multimodal responses. Our datasets are available at: https://huggingface.co/MRAMG.

[Arxiv](https://arxiv.org/abs/2502.04176)