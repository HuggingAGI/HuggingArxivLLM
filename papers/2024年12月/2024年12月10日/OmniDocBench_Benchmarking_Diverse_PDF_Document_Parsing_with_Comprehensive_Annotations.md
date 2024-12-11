# OmniDocBench：通过全面注释对多样化的 PDF 文档解析进行基准测试

发布时间：2024年12月10日

`其他` `计算机视觉` `文档解析`

> OmniDocBench: Benchmarking Diverse PDF Document Parsing with Comprehensive Annotations

# 摘要

> 文档内容提取在计算机视觉领域极为关键，尤其是要满足大型语言模型（LLMs）和检索增强生成（RAG）技术对高质量数据的需求。然而，当下的文档解析方法在多样性和综合评估上存在明显局限。为应对这些难题，我们推出了 OmniDocBench，这是一个全新的多源基准，旨在推动自动文档内容提取的发展。OmniDocBench 包含一个精心整理和标注的高质量评估数据集，涵盖了诸如学术论文、教科书、幻灯片等九种不同的文档类型。我们的基准提供了一个灵活且全面的评估框架，设有 19 个布局类别标签和 14 个属性标签，能够针对整个数据集、单个模块或特定数据类型进行多层次评估。借助 OmniDocBench，我们对现有的模块化管道和多模态端到端方法展开了详尽的对比分析，凸显了它们在处理文档多样性和确保公平评估方面的不足。OmniDocBench 为文档内容提取领域确立了一个强大、多元且公平的评估标准，为未来的进步提供了重要见解，也促进了文档解析技术的发展。相关代码和数据集可在 https://github.com/opendatalab/OmniDocBench 获取。

> Document content extraction is crucial in computer vision, especially for meeting the high-quality data needs of large language models (LLMs) and retrieval-augmented generation (RAG) technologies. However, current document parsing methods suffer from significant limitations in terms of diversity and comprehensive evaluation. To address these challenges, we introduce OmniDocBench, a novel multi-source benchmark designed to advance automated document content extraction. OmniDocBench includes a meticulously curated and annotated high-quality evaluation dataset comprising nine diverse document types, such as academic papers, textbooks, slides, among others. Our benchmark provides a flexible and comprehensive evaluation framework with 19 layout category labels and 14 attribute labels, enabling multi-level assessments across entire datasets, individual modules, or specific data types. Using OmniDocBench, we perform an exhaustive comparative analysis of existing modular pipelines and multimodal end-to-end methods, highlighting their limitations in handling document diversity and ensuring fair evaluation. OmniDocBench establishes a robust, diverse, and fair evaluation standard for the document content extraction field, offering crucial insights for future advancements and fostering the development of document parsing technologies. The codes and dataset is available in https://github.com/opendatalab/OmniDocBench.

[Arxiv](https://arxiv.org/abs/2412.07626)