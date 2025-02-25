# Visual-RAG：图像生成增强检索基准测试，专为视觉知识密集型查询而设计

发布时间：2025年02月23日

`RAG` `问答系统` `视觉知识`

> Visual-RAG: Benchmarking Text-to-Image Retrieval Augmented Generation for Visual Knowledge Intensive Queries

# 摘要

> 检索增强生成（RAG）是一种流行的提升大型语言模型（LLMs）能力的方法，它通过弥补模型在事实验证和回答知识密集型问题上的不足来实现。随着LLM研究扩展到处理文本以外的输入模态（如图像），一些多模态RAG基准被提出。然而，这些方法主要依赖文本知识库作为增强的主要证据来源。目前仍缺乏专门设计用于评估RAG系统中图像增强效果及其对视觉知识利用的基准。我们提出了Visual-RAG，这是一个专注于视觉知识密集型问题的新问答基准。与以往依赖文本证据的工作不同，Visual-RAG需要进行文本到图像的检索，并整合相关线索图像以提取视觉知识作为证据。通过Visual-RAG，我们评估了5个开源和3个专有的多模态LLM（MLLMs），发现图像可以作为良好的证据用于RAG；然而，即使是SOTA模型也难以有效提取和利用视觉知识。

> Retrieval-Augmented Generation (RAG) is a popular approach for enhancing Large Language Models (LLMs) by addressing their limitations in verifying facts and answering knowledge-intensive questions. As the research in LLM extends their capability to handle input modality other than text, e.g. image, several multimodal RAG benchmarks are proposed. Nonetheless, they mainly use textual knowledge bases as the primary source of evidences for augmentation. There still lack benchmarks designed to evaluate images as augmentation in RAG systems and how they leverage visual knowledge. We propose Visual-RAG, a novel Question Answering benchmark that emphasizes visual knowledge intensive questions. Unlike prior works relying on text-based evidence, Visual-RAG necessitates text-to-image retrieval and integration of relevant clue images to extract visual knowledge as evidence. With Visual-RAG, we evaluate 5 open-sourced and 3 proprietary Multimodal LLMs (MLLMs), revealing that images can serve as good evidence in RAG; however, even the SoTA models struggle with effectively extracting and utilizing visual knowledge

[Arxiv](https://arxiv.org/abs/2502.16636)