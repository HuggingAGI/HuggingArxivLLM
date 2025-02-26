# olmOCR：视觉语言模型助力PDF中万亿级文本信息的高效解锁

发布时间：2025年02月25日

`LLM应用` `文档处理` `计算机视觉`

> olmOCR: Unlocking Trillions of Tokens in PDFs with Vision Language Models

# 摘要

> PDF文档有望成为语言模型训练的宝贵资源，能够提供数万亿个新颖、高质量tokens。然而，由于这些文档类型多样、格式和视觉布局各异，提取并忠实呈现其内容用于语言模型面临诸多挑战。我们推出olmOCR——一个开源的Python工具包，它能够将PDF文件处理为自然阅读顺序下的干净、线性化纯文本，同时保留章节、表格、列表、公式等结构化内容。我们的工具包基于一个在260,000页样本上微调的70亿参数视觉-语言模型（VLM），这些样本来自超过100,000份具有多样化属性的爬取PDF文件，包括图形、手写文本和低质量扫描内容。olmOCR专为大规模批处理设计，能够灵活扩展以适应不同硬件配置，处理一百万页PDF文件仅需190美元。我们开源了olmOCR的所有组件，包括VLM权重、数据和训练代码，以及基于vLLM和SGLang等服务框架构建的推理代码。


> PDF documents have the potential to provide trillions of novel, high-quality tokens for training language models. However, these documents come in a diversity of types with differing formats and visual layouts that pose a challenge when attempting to extract and faithfully represent the underlying content for language model use. We present olmOCR, an open-source Python toolkit for processing PDFs into clean, linearized plain text in natural reading order while preserving structured content like sections, tables, lists, equations, and more. Our toolkit runs a fine-tuned 7B vision language model (VLM) trained on a sample of 260,000 pages from over 100,000 crawled PDFs with diverse properties, including graphics, handwritten text and poor quality scans. olmOCR is optimized for large-scale batch processing, able to scale flexibly to different hardware setups and convert a million PDF pages for only $190 USD. We release all components of olmOCR including VLM weights, data and training code, as well as inference code built on serving frameworks including vLLM and SGLang.

[Arxiv](https://arxiv.org/abs/2502.18443)