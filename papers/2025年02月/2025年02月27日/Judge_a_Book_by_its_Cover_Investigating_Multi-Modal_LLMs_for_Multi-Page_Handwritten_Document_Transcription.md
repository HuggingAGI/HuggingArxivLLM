# # 以貌取书：探索多模态LLM在多页手写文档转录中的应用

发布时间：2025年02月27日

`LLM应用` `手写文本识别` `文档处理`

> Judge a Book by its Cover: Investigating Multi-Modal LLMs for Multi-Page Handwritten Document Transcription

# 摘要

> 手写文本识别（HTR）在多页文档场景下仍具挑战性，尤其是当页面共享相似格式和上下文特征时。尽管现代OCR引擎在处理打印文本方面表现出色，但在手写文本上的表现却较为有限，通常需要昂贵的标注数据进行微调。本文探讨了在零样本场景下使用多模态大语言模型（MLLMs）来转录多页手写文档的可能性。我们研究了商用OCR引擎与MLLMs的不同配置方案，将MLLMs既作为端到端转录器，也作为后处理工具，同时考虑了是否包含图像组件。我们提出了一种名为“+first page”的新方法，通过提供整个文档的OCR输出和仅第一页的图像来增强MLLMs的转录效果。这种方法利用了文档的共享特征，而无需承担处理所有图像的高昂成本。在IAM手写数据库的多页版本上的实验表明，“+first page”方法能够提高转录准确率，平衡成本与性能，并通过外推单页的格式和OCR错误模式，甚至提升了对样本外文本的处理效果。

> Handwritten text recognition (HTR) remains a challenging task, particularly for multi-page documents where pages share common formatting and contextual features. While modern optical character recognition (OCR) engines are proficient with printed text, their performance on handwriting is limited, often requiring costly labeled data for fine-tuning. In this paper, we explore the use of multi-modal large language models (MLLMs) for transcribing multi-page handwritten documents in a zero-shot setting. We investigate various configurations of commercial OCR engines and MLLMs, utilizing the latter both as end-to-end transcribers and as post-processors, with and without image components. We propose a novel method, '+first page', which enhances MLLM transcription by providing the OCR output of the entire document along with just the first page image. This approach leverages shared document features without incurring the high cost of processing all images. Experiments on a multi-page version of the IAM Handwriting Database demonstrate that '+first page' improves transcription accuracy, balances cost with performance, and even enhances results on out-of-sample text by extrapolating formatting and OCR error patterns from a single page.

[Arxiv](https://arxiv.org/abs/2502.20295)