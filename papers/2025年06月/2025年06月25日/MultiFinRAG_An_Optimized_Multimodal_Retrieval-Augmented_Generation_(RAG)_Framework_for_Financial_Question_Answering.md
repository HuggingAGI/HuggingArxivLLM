# MultiFinRAG：专为财务问答优化设计的多模态增强生成（RAG）框架

发布时间：2025年06月25日

`RAG` `问答系统`

> MultiFinRAG: An Optimized Multimodal Retrieval-Augmented Generation (RAG) Framework for Financial Question Answering

# 摘要

> 财务文档——如10-Ks、10-Qs和投资者演示文稿——通常篇幅浩繁，涵盖叙述性文本、结构化表格和复杂图表等多模态内容。传统LLMs和RAG方法在处理这类内容时面临挑战，原因包括分词限制、布局丢失和跨模态上下文碎片化。为此，我们推出MultiFinRAG——专为财务问答设计的检索增强生成框架。MultiFinRAG通过多模态提取技术，将表格和图表图像分批处理后发送至轻量级开源多模态LLM，生成结构化JSON输出和简洁文本摘要。这些输出与叙述性文本一同嵌入并基于多模态感知相似度阈值进行索引，确保精准检索。随后，分层回退策略根据需要动态升级，从纯文本上下文逐步扩展至文本+表格+图像的组合，从而在减少无关上下文的同时支持跨模态推理。尽管MultiFinRAG运行于普通硬件，但在涉及文本、表格、图像及多模态联合推理的复杂财务问答任务中，其准确率仍比ChatGPT-4o（免费版）高出19个百分点。


> Financial documents--such as 10-Ks, 10-Qs, and investor presentations--span hundreds of pages and combine diverse modalities, including dense narrative text, structured tables, and complex figures. Answering questions over such content often requires joint reasoning across modalities, which strains traditional large language models (LLMs) and retrieval-augmented generation (RAG) pipelines due to token limitations, layout loss, and fragmented cross-modal context. We introduce MultiFinRAG, a retrieval-augmented generation framework purpose-built for financial QA. MultiFinRAG first performs multimodal extraction by grouping table and figure images into batches and sending them to a lightweight, quantized open-source multimodal LLM, which produces both structured JSON outputs and concise textual summaries. These outputs, along with narrative text, are embedded and indexed with modality-aware similarity thresholds for precise retrieval. A tiered fallback strategy then dynamically escalates from text-only to text+table+image contexts when necessary, enabling cross-modal reasoning while reducing irrelevant context. Despite running on commodity hardware, MultiFinRAG achieves 19 percentage points higher accuracy than ChatGPT-4o (free-tier) on complex financial QA tasks involving text, tables, images, and combined multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2506.20821)