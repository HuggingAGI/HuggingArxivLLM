# 视觉引导分块即所需：通过多模态文档理解增强 RAG

发布时间：2025年06月19日

`RAG` `信息检索` `问答系统`

> Vision-Guided Chunking Is All You Need: Enhancing RAG with Multimodal Document Understanding

# 摘要

> RAG系统革新了信息检索与问答领域，但传统文本分块方法在处理复杂文档、多页表格、嵌入图表及跨页上下文依赖时力不从心。我们提出了一种基于大型多模态模型（LMMs）的创新多模态文档分块方法，支持批量处理PDF文档，同时确保语义连贯与结构完整。我们的方法采用可配置页码分批处理文档，跨批次保留上下文，精准处理跨页表格、嵌入式视觉元素及程序性内容。在精心挑选的PDF文档数据集上进行评估，结果表明我们的方法在分块质量和下游RAG性能上均有显著提升。与传统基础RAG系统相比，我们的视觉引导方法在准确性、文档结构保留及语义连贯性方面均表现更优。

> Retrieval-Augmented Generation (RAG) systems have revolutionized information retrieval and question answering, but traditional text-based chunking methods struggle with complex document structures, multi-page tables, embedded figures, and contextual dependencies across page boundaries. We present a novel multimodal document chunking approach that leverages Large Multimodal Models (LMMs) to process PDF documents in batches while maintaining semantic coherence and structural integrity. Our method processes documents in configurable page batches with cross-batch context preservation, enabling accurate handling of tables spanning multiple pages, embedded visual elements, and procedural content. We evaluate our approach on a curated dataset of PDF documents with manually crafted queries, demonstrating improvements in chunk quality and downstream RAG performance. Our vision-guided approach achieves better accuracy compared to traditional vanilla RAG systems, with qualitative analysis showing superior preservation of document structure and semantic coherence.

[Arxiv](https://arxiv.org/abs/2506.16035)