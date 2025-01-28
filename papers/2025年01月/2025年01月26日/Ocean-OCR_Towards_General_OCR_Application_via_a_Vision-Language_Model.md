# Ocean-OCR: 基于视觉-语言模型的通用OCR应用探索

发布时间：2025年01月26日

`LLM应用

**理由**：这篇论文主要讨论了一个多模态大型语言模型（MLLM）在OCR任务中的应用和改进，属于LLM在实际任务中的应用场景，因此分类为LLM应用。` `文档处理` `文本识别`

> Ocean-OCR: Towards General OCR Application via a Vision-Language Model

# 摘要

> 多模态大型语言模型（MLLMs）在多个领域展现了卓越的能力，尤其在处理和理解多模态信息方面表现出色。然而，OCR能力的不足限制了其在文本相关任务中的表现。本文提出的	extbf{Ocean-OCR}，一个3B规模的MLLM，不仅在各类OCR场景中表现优异，还在一般任务上具备强大的理解能力。我们通过Native Resolution ViT实现可变分辨率输入，并利用大量高质量OCR数据集提升模型性能。通过开源OCR基准测试和多种OCR场景的全面实验，我们展示了Ocean-OCR的卓越性能，涵盖文档理解、场景文本识别和手写识别等场景。值得一提的是，Ocean-OCR是首个超越TextIn和PaddleOCR等专业OCR模型的MLLM。

> Multimodal large language models (MLLMs) have shown impressive capabilities across various domains, excelling in processing and understanding information from multiple modalities. Despite the rapid progress made previously, insufficient OCR ability hinders MLLMs from excelling in text-related tasks. In this paper, we present \textbf{Ocean-OCR}, a 3B MLLM with state-of-the-art performance on various OCR scenarios and comparable understanding ability on general tasks. We employ Native Resolution ViT to enable variable resolution input and utilize a substantial collection of high-quality OCR datasets to enhance the model performance. We demonstrate the superiority of Ocean-OCR through comprehensive experiments on open-source OCR benchmarks and across various OCR scenarios. These scenarios encompass document understanding, scene text recognition, and handwritten recognition, highlighting the robust OCR capabilities of Ocean-OCR. Note that Ocean-OCR is the first MLLM to outperform professional OCR models such as TextIn and PaddleOCR.

[Arxiv](https://arxiv.org/abs/2501.15558)