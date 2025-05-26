# # 提升大型视觉语言模型的表格问答能力：基于布局模态的日文年报分析

发布时间：2025年05月23日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于表格理解，特别是在金融领域的证券报告中，通过结合文本内容和布局特征来增强理解。它主要关注LLMs在具体任务中的应用，因此属于LLM应用类别。` `表格处理`

> Enhancing Large Vision-Language Models with Layout Modality for Table Question Answering on Japanese Annual Securities Reports

# 摘要

> 随着大型语言模型（LLMs）的 recent advancements 以及检索增强生成（RAG）日益增长的兴趣，理解表格结构的能力变得越来越重要。这在金融领域尤其关键，例如证券报告，这些领域需要对表格进行高度准确的问答（QA）。然而，表格以多种形式存在，包括 HTML、图像和纯文本，这使得保留和提取结构信息变得困难。因此，多模态 LLMs 对于稳健和通用的表格理解至关重要。尽管它们具有潜力，但目前作为多模态 LLMs 主要代表的大型视觉-语言模型（LVLMs）在准确理解文档中的字符及其空间关系方面仍面临挑战。在本研究中，我们提出了一种方法，通过结合表格内的文本内容和布局特征来增强基于 LVLM 的表格理解。实验结果表明，这些辅助模态显著提高了性能，使得在不依赖显式结构化输入格式的情况下，能够对复杂文档布局进行稳健的解释。

> With recent advancements in Large Language Models (LLMs) and growing interest in retrieval-augmented generation (RAG), the ability to understand table structures has become increasingly important. This is especially critical in financial domains such as securities reports, where highly accurate question answering (QA) over tables is required. However, tables exist in various formats-including HTML, images, and plain text-making it difficult to preserve and extract structural information. Therefore, multimodal LLMs are essential for robust and general-purpose table understanding. Despite their promise, current Large Vision-Language Models (LVLMs), which are major representatives of multimodal LLMs, still face challenges in accurately understanding characters and their spatial relationships within documents. In this study, we propose a method to enhance LVLM-based table understanding by incorporating in-table textual content and layout features. Experimental results demonstrate that these auxiliary modalities significantly improve performance, enabling robust interpretation of complex document layouts without relying on explicitly structured input formats.

[Arxiv](https://arxiv.org/abs/2505.17625)