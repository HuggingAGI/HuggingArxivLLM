# mKG-RAG：面向视觉问答的多模态知识图谱增强RAG模型

发布时间：2025年08月07日

`RAG` `计算机视觉` `知识图谱`

> mKG-RAG: Multimodal Knowledge Graph-Enhanced RAG for Visual Question Answering

# 摘要

> # 摘要
近期，检索增强生成（RAG）被提出用于通过将外部知识数据库整合到生成过程中来扩展多模态大型语言模型（MLLMs）的内部知识，这一方法在基于知识的视觉问答（VQA）任务中得到了广泛应用。尽管取得了显著进展，但传统的基于RAG的VQA方法由于依赖非结构化的文档，并忽视了知识元素之间的结构性关系，常常会引入无关或误导性内容，从而降低了答案的准确性和可靠性。为了克服这些挑战，我们提出了一种基于多模态知识图谱（KGs）的新型知识增强生成框架（mKG-RAG），旨在提升知识密集型VQA任务的性能。具体而言，我们利用MLLM驱动的关键词提取和视觉-文本匹配技术，从多模态文档中提取语义一致且模态对齐的实体/关系，构建高质量的多模态知识图谱作为结构化的知识表示。此外，我们还引入了一种配备问题感知的多模态检索器的双阶段检索策略，以在提升检索效率的同时优化精度。通过全面的实验，我们证明了我们的方法显著优于现有方法，为基于知识的VQA任务设立了新的技术水平。

> Recently, Retrieval-Augmented Generation (RAG) has been proposed to expand internal knowledge of Multimodal Large Language Models (MLLMs) by incorporating external knowledge databases into the generation process, which is widely used for knowledge-based Visual Question Answering (VQA) tasks. Despite impressive advancements, vanilla RAG-based VQA methods that rely on unstructured documents and overlook the structural relationships among knowledge elements frequently introduce irrelevant or misleading content, reducing answer accuracy and reliability. To overcome these challenges, a promising solution is to integrate multimodal knowledge graphs (KGs) into RAG-based VQA frameworks to enhance the generation by introducing structured multimodal knowledge. Therefore, in this paper, we propose a novel multimodal knowledge-augmented generation framework (mKG-RAG) based on multimodal KGs for knowledge-intensive VQA tasks. Specifically, our approach leverages MLLM-powered keyword extraction and vision-text matching to distill semantically consistent and modality-aligned entities/relationships from multimodal documents, constructing high-quality multimodal KGs as structured knowledge representations. In addition, a dual-stage retrieval strategy equipped with a question-aware multimodal retriever is introduced to improve retrieval efficiency while refining precision. Comprehensive experiments demonstrate that our approach significantly outperforms existing methods, setting a new state-of-the-art for knowledge-based VQA.

[Arxiv](https://arxiv.org/abs/2508.05318)