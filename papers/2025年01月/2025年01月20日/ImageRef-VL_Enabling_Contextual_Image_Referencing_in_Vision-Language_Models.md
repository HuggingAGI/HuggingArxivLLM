# ImageRef-VL: 视觉-语言模型中的上下文图像引用技术

发布时间：2025年01月20日

`RAG

理由：这篇论文主要讨论了视觉-语言模型（VLMs）在基于检索增强生成（RAG）的对话系统中的应用，特别是如何提升对话中引用上下文相关图像的能力。论文提出了ImageRef-VL方法，并通过实验验证了其在上下文图像引用任务中的优越性能。因此，这篇论文的核心内容与检索增强生成（RAG）密切相关，应归类为RAG。` `多模态对话系统` `图像检索`

> ImageRef-VL: Enabling Contextual Image Referencing in Vision-Language Models

# 摘要

> # 摘要
视觉-语言模型（VLMs）在多模态输入理解方面表现出色，并已广泛应用于基于检索增强生成（RAG）的对话系统。然而，现有VLM驱动的聊天机器人在对话中引用上下文相关图像时存在明显不足。本文提出上下文图像引用能力，即根据对话上下文从检索文档中准确引用相关图像，并系统探讨了VLMs在此方面的表现。我们首次进行了上下文图像引用评估，构建了专用测试数据集和评估指标。此外，我们提出了ImageRef-VL方法，通过对大规模人工标注的多模态对话数据集进行指令微调，显著提升了开源VLMs的图像引用能力。实验结果显示，ImageRef-VL不仅在上下文图像引用任务中超越专有模型，还比当前最优开源VLMs性能提升了88%。代码已开源：https://github.com/bytedance/ImageRef-VL。

> Vision-Language Models (VLMs) have demonstrated remarkable capabilities in understanding multimodal inputs and have been widely integrated into Retrieval-Augmented Generation (RAG) based conversational systems. While current VLM-powered chatbots can provide textual source references in their responses, they exhibit significant limitations in referencing contextually relevant images during conversations. In this paper, we introduce Contextual Image Reference -- the ability to appropriately reference relevant images from retrieval documents based on conversation context -- and systematically investigate VLMs' capability in this aspect. We conduct the first evaluation for contextual image referencing, comprising a dedicated testing dataset and evaluation metrics. Furthermore, we propose ImageRef-VL, a method that significantly enhances open-source VLMs' image referencing capabilities through instruction fine-tuning on a large-scale, manually curated multimodal conversation dataset. Experimental results demonstrate that ImageRef-VL not only outperforms proprietary models but also achieves an 88% performance improvement over state-of-the-art open-source VLMs in contextual image referencing tasks. Our code is available at https://github.com/bytedance/ImageRef-VL.

[Arxiv](https://arxiv.org/abs/2501.12418)