# MIRACL-VISION：大规模多语言视觉文档检索基准

发布时间：2025年05月21日

`RAG` `文档检索` `信息检索`

> MIRACL-VISION: A Large, multilingual, visual document retrieval benchmark

# 摘要

> 文档检索在搜索和检索增强生成（RAG）应用中扮演着重要角色。大型语言模型（LLMs）的引入显著提升了基于文本的文档检索准确性。然而，面对包含复杂布局和视觉元素（如表格、图表和信息图）的文档时，纯文本格式难以完美呈现其内容。近期，基于图像的文档检索流水线逐渐兴起，这些流水线借助视觉大型语言模型（VLMs）实现根据查询精准检索相关页面图像。

然而，现有的视觉文档检索评估基准存在明显局限：主要局限于英语，依赖合成问题，且语料库规模有限。为了解决这些问题，我们推出MIRACL-VISION——一个多语言视觉文档检索评估基准。MIRACL-VISION涵盖18种语言，是对流行文本检索基准MIRACL数据集的扩展。MIRACL通过劳动密集型标注流程构建，旨在生成高质量问题。

为了在保持挑战性的同时减小语料库规模，我们设计了一种方法，用于剔除语料库中的“简单”负样本。通过使用流行公共文本和图像模型进行广泛实验，我们发现：基于VLM的嵌入模型在多语言能力方面存在显著差距，其检索准确度较基于文本的模型最多降低59.7%。即使在英语场景下，视觉模型的检索准确度也比文本模型低12.1%。MIRACL-VISION作为具有挑战性、代表性且多语言的视觉检索评估基准，将助力社区开发更强大的文档检索模型。


> Document retrieval is an important task for search and Retrieval-Augmented Generation (RAG) applications. Large Language Models (LLMs) have contributed to improving the accuracy of text-based document retrieval. However, documents with complex layout and visual elements like tables, charts and infographics are not perfectly represented in textual format. Recently, image-based document retrieval pipelines have become popular, which use visual large language models (VLMs) to retrieve relevant page images given a query. Current evaluation benchmarks on visual document retrieval are limited, as they primarily focus only English language, rely on synthetically generated questions and offer a small corpus size. Therefore, we introduce MIRACL-VISION, a multilingual visual document retrieval evaluation benchmark. MIRACL-VISION covers 18 languages, and is an extension of the MIRACL dataset, a popular benchmark to evaluate text-based multilingual retrieval pipelines. MIRACL was built using a human-intensive annotation process to generate high-quality questions. In order to reduce MIRACL-VISION corpus size to make evaluation more compute friendly while keeping the datasets challenging, we have designed a method for eliminating the "easy" negatives from the corpus. We conducted extensive experiments comparing MIRACL-VISION with other benchmarks, using popular public text and image models. We observe a gap in state-of-the-art VLM-based embedding models on multilingual capabilities, with up to 59.7% lower retrieval accuracy than a text-based retrieval models. Even for the English language, the visual models retrieval accuracy is 12.1% lower compared to text-based models. MIRACL-VISION is a challenging, representative, multilingual evaluation benchmark for visual retrieval pipelines and will help the community build robust models for document retrieval.

[Arxiv](https://arxiv.org/abs/2505.11651)