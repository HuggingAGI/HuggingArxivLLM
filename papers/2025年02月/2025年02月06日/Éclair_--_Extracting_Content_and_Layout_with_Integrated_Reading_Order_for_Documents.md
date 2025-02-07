# Éclair -- 集成阅读顺序的文档内容与布局提取

发布时间：2025年02月06日

`其他

理由：这篇论文主要讨论的是光学字符识别（OCR）技术及其在文档处理中的应用，特别是Éclair这一工具的开发与评估。虽然提到了大型语言模型（LLMs）和视觉语言模型（VLMs）的数据整理，但核心内容并不直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `文档处理` `光学字符识别`

> Éclair -- Extracting Content and Layout with Integrated Reading Order for Documents

# 摘要

> # 摘要
光学字符识别（OCR）技术广泛应用于从文档图像中提取文本，助力高效数字化与数据检索。然而，面对复杂文档，仅提取文本远远不够。要全面理解这些文档，需掌握其结构——包括格式、公式、表格及跨页多块多列的阅读顺序——以及用于识别脚注、图像标题等元素的语义信息。这种深度理解对下游任务（如检索、文档问答及为训练大型语言模型（LLMs）和视觉语言模型（VLMs）的数据整理）至关重要。为此，我们推出Éclair，一款专为处理各类文档设计的通用文本提取工具。给定图像，Éclair能按阅读顺序提取格式化文本，并同步获取边界框及其对应语义类别。为全面评估这些新功能，我们构建了多样化的人工标注基准，用于文档级OCR与语义分类。Éclair在该基准上表现卓越，关键指标领先其他方法。此外，Éclair在现有基准测试中也展现出其多面性与强大实力。

> Optical Character Recognition (OCR) technology is widely used to extract text from images of documents, facilitating efficient digitization and data retrieval. However, merely extracting text is insufficient when dealing with complex documents. Fully comprehending such documents requires an understanding of their structure -- including formatting, formulas, tables, and the reading order of multiple blocks and columns across multiple pages -- as well as semantic information for detecting elements like footnotes and image captions. This comprehensive understanding is crucial for downstream tasks such as retrieval, document question answering, and data curation for training Large Language Models (LLMs) and Vision Language Models (VLMs). To address this, we introduce Éclair, a general-purpose text-extraction tool specifically designed to process a wide range of document types. Given an image, Éclair is able to extract formatted text in reading order, along with bounding boxes and their corresponding semantic classes. To thoroughly evaluate these novel capabilities, we introduce our diverse human-annotated benchmark for document-level OCR and semantic classification. Éclair achieves state-of-the-art accuracy on this benchmark, outperforming other methods across key metrics. Additionally, we evaluate Éclair on established benchmarks, demonstrating its versatility and strength across several evaluation standards.

[Arxiv](https://arxiv.org/abs/2502.04223)