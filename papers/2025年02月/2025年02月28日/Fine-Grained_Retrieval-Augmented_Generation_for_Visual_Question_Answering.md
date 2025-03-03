# # 细粒度检索增强生成的视觉问答方法

发布时间：2025年02月28日

`RAG

理由：这篇论文主要探讨了基于外部知识库的检索增强生成（RAG）方法在视觉问答任务中的应用。它提出了细粒度知识单元和知识单元检索增强生成框架（KU-RAG），并展示了其在提升KB-VQA方法性能方面的有效性。因此，这篇论文属于RAG类别。` `视觉问答` `计算机视觉`

> Fine-Grained Retrieval-Augmented Generation for Visual Question Answering

# 摘要

> # **视觉问答（VQA）**  
视觉问答专注于利用图像信息回答自然语言问题。尽管像GPT-4o这样的前沿多模态大型语言模型（MLLMs）在VQA任务上表现强劲，但它们在获取领域特定或最新知识方面往往表现不足。为了解决这一问题，一种基于外部知识库（KBs）的检索增强生成（RAG）方法，即KB-VQA，应运而生，展现出巨大潜力。然而，传统的单模态检索技术，即将图像转换为文本描述的方法，常常导致关键视觉细节的丢失。本研究提出了细粒度知识单元，将文本片段与存储在向量数据库中的实体图像相结合。此外，我们引入了一种知识单元检索增强生成框架（KU-RAG），该框架将细粒度检索与MLLMs相结合。所提出的KU-RAG框架通过知识校正链确保了相关知识的精准检索，并增强了推理能力。实验结果表明，我们的方法显著提升了领先KB-VQA方法的性能，实现了高达10%的性能提升。

> Visual Question Answering (VQA) focuses on providing answers to natural language questions by utilizing information from images. Although cutting-edge multimodal large language models (MLLMs) such as GPT-4o achieve strong performance on VQA tasks, they frequently fall short in accessing domain-specific or the latest knowledge. To mitigate this issue, retrieval-augmented generation (RAG) leveraging external knowledge bases (KBs), referred to as KB-VQA, emerges as a promising approach. Nevertheless, conventional unimodal retrieval techniques, which translate images into textual descriptions, often result in the loss of critical visual details. This study presents fine-grained knowledge units, which merge textual snippets with entity images stored in vector databases. Furthermore, we introduce a knowledge unit retrieval-augmented generation framework (KU-RAG) that integrates fine-grained retrieval with MLLMs. The proposed KU-RAG framework ensures precise retrieval of relevant knowledge and enhances reasoning capabilities through a knowledge correction chain. Experimental findings demonstrate that our approach significantly boosts the performance of leading KB-VQA methods, achieving improvements of up to 10%.

[Arxiv](https://arxiv.org/abs/2502.20964)