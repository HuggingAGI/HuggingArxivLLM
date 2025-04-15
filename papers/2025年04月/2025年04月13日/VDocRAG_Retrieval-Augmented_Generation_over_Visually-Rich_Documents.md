# VDocRAG: 面向视觉丰富文档的检索增强生成

发布时间：2025年04月13日

`RAG` `文档处理` `问答系统`

> VDocRAG: Retrieval-Augmented Generation over Visually-Rich Documents

# 摘要

> 我们致力于开发一个检索增强生成（RAG）框架，用于处理包含丰富视觉内容的多模态文档（如图表、表格）和多种格式（如PDF、PPTX）。本文中，我们推出了全新的VDocRAG框架，它能够直接解析各类文档和模态的统一图像格式，避免了传统文本解析带来的信息遗漏。为了提升性能，我们设计了创新的自监督预训练任务，通过将视觉信息压缩为与文档文本内容对齐的密集令牌表示，优化大型视觉-语言模型的检索能力。此外，我们推出了首个统一开放领域文档视觉问答数据集集合OpenDocVQA，涵盖多种文档类型和格式。OpenDocVQA为在开放领域环境下训练和评估文档检索与问答模型提供了全面的资源。实验结果表明，VDocRAG显著超越了传统基于文本的RAG方法，并展现了强大的泛化能力，证明了有效RAG范式在真实世界文档应用中的巨大潜力。

> We aim to develop a retrieval-augmented generation (RAG) framework that answers questions over a corpus of visually-rich documents presented in mixed modalities (e.g., charts, tables) and diverse formats (e.g., PDF, PPTX). In this paper, we introduce a new RAG framework, VDocRAG, which can directly understand varied documents and modalities in a unified image format to prevent missing information that occurs by parsing documents to obtain text. To improve the performance, we propose novel self-supervised pre-training tasks that adapt large vision-language models for retrieval by compressing visual information into dense token representations while aligning them with textual content in documents. Furthermore, we introduce OpenDocVQA, the first unified collection of open-domain document visual question answering datasets, encompassing diverse document types and formats. OpenDocVQA provides a comprehensive resource for training and evaluating retrieval and question answering models on visually-rich documents in an open-domain setting. Experiments show that VDocRAG substantially outperforms conventional text-based RAG and has strong generalization capability, highlighting the potential of an effective RAG paradigm for real-world documents.

[Arxiv](https://arxiv.org/abs/2504.09795)