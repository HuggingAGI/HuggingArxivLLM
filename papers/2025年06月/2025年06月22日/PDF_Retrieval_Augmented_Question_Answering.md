# # 基于PDF检索的增强问答系统
PDF Retrieval Augmented Question Answering

发布时间：2025年06月22日

`RAG` `问答系统` `文档处理`

> PDF Retrieval Augmented Question Answering

# 摘要

> 本文提出了一种基于检索增强生成（RAG）框架的问答（QA）系统改进方案，旨在提升从PDF文件中提取信息的能力。PDF文件中包含文本、图像、矢量图、图表和表格等多种数据形式，这为主要针对文本内容设计的现有QA系统带来了独特挑战。我们致力于开发一个全面的RAG-based QA系统，以有效应对复杂的多模态问题，即查询中包含多种数据类型的组合。这一目标主要通过优化PDF中非文本元素的处理和整合方法，将其纳入RAG框架以生成精确且相关的答案，同时对大型语言模型进行微调，使其更好地适应我们的系统。我们对解决方案进行了深入的实验评估，证明了其在不同PDF内容类型中提取准确信息的能力。这项工作不仅推动了检索增强型QA系统的边界，还为多模态数据整合与处理的进一步研究奠定了基础。

> This paper presents an advancement in Question-Answering (QA) systems using a Retrieval Augmented Generation (RAG) framework to enhance information extraction from PDF files. Recognizing the richness and diversity of data within PDFs--including text, images, vector diagrams, graphs, and tables--poses unique challenges for existing QA systems primarily designed for textual content. We seek to develop a comprehensive RAG-based QA system that will effectively address complex multimodal questions, where several data types are combined in the query. This is mainly achieved by refining approaches to processing and integrating non-textual elements in PDFs into the RAG framework to derive precise and relevant answers, as well as fine-tuning large language models to better adapt to our system. We provide an in-depth experimental evaluation of our solution, demonstrating its capability to extract accurate information that can be applied to different types of content across PDFs. This work not only pushes the boundaries of retrieval-augmented QA systems but also lays a foundation for further research in multimodal data integration and processing.

[Arxiv](https://arxiv.org/abs/2506.18027)