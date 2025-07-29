# CONCAP: 突破英语限制的概念检索增强式字幕生成

发布时间：2025年07月27日

`RAG` `计算机视觉`

> CONCAP: Seeing Beyond English with Concepts Retrieval-Augmented Captioning

# 摘要

> 尽管多语言视觉语言模型在图像描述任务上取得了显著进展，但受限于多语言训练数据的匮乏和高昂的模型参数化成本，它们的表现仍显不足。检索增强生成（RAG）通过基于目标语言的检索样例来调节描述生成，为减少对多语言大规模训练的依赖提供了有前景的替代方案。然而，现有的多语言RAG描述模型往往依赖于从英语翻译而来的检索描述，这可能引发与源语言之间的不匹配和语言偏见。为此，我们提出了CONCAP，一种将检索描述与图像特定概念相结合的多语言图像描述模型。通过增强输入图像的上下文关联，CONCAP在不同语言中为描述生成过程提供了更坚实的基础。在XM3600数据集上的实验表明，CONCAP在低资源和中等资源语言上表现出色，且大幅降低了数据需求。我们的研究结果凸显了概念感知检索增强在弥合多语言性能差距方面的有效性。

> Multilingual vision-language models have made significant strides in image captioning, yet they still lag behind their English counterparts due to limited multilingual training data and costly large-scale model parameterization. Retrieval-augmented generation (RAG) offers a promising alternative by conditioning caption generation on retrieved examples in the target language, reducing the need for extensive multilingual training. However, multilingual RAG captioning models often depend on retrieved captions translated from English, which can introduce mismatches and linguistic biases relative to the source language. We introduce CONCAP, a multilingual image captioning model that integrates retrieved captions with image-specific concepts, enhancing the contextualization of the input image and grounding the captioning process across different languages. Experiments on the XM3600 dataset indicate that CONCAP enables strong performance on low- and mid-resource languages, with highly reduced data requirements. Our findings highlight the effectiveness of concept-aware retrieval augmentation in bridging multilingual performance gaps.

[Arxiv](https://arxiv.org/abs/2507.20411)