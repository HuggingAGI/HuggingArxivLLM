# 扩展大型视觉-语言模型，提升生物医学图像分析的多模态理解能力

发布时间：2025年01月25日

`LLM应用

理由：该论文主要讨论了如何利用大型语言模型（LLMs）和视觉语言模型（VLMs）来增强低剂量放射治疗（LDRT）中的多模态理解。具体来说，作者基于LLaVA模型微调了智能助手，以处理领域特定的视觉问答任务。这属于将LLM应用于特定领域（LDRT）的实际问题解决，因此归类为“LLM应用”。` `放射治疗`

> Scaling Large Vision-Language Models for Enhanced Multimodal Comprehension In Biomedical Image Analysis

# 摘要

> 大型语言模型（LLMs）在文本理解方面展现了强大的能力，正被广泛应用于加速科学发现，包括知识提取、知识蒸馏和知识合成。然而，科学数据往往以视觉和文本两种形式存在。视觉语言模型（VLMs）通过预训练的视觉骨干网络和跨模态投影器，将图像信息融入LLM的维度空间，从而提供更丰富的多模态理解。尽管如此，现成的VLMs在处理领域特定数据时表现有限，且容易产生幻觉。为此，我们基于LLaVA模型微调了智能助手，以增强低剂量放射治疗（LDRT）中的多模态理解。我们利用42,673篇文章的多语言数据，设计了复杂的视觉问答（VQA）任务。经过50,882个图像-文本对的训练，我们的助手在减少幻觉和提高领域特定理解方面表现优异，显著超越了基础模型。

> Large language models (LLMs) have demonstrated immense capabilities in understanding textual data and are increasingly being adopted to help researchers accelerate scientific discovery through knowledge extraction (information retrieval), knowledge distillation (summarizing key findings and methodologies into concise forms), and knowledge synthesis (aggregating information from multiple scientific sources to address complex queries, generate hypothesis and formulate experimental plans). However, scientific data often exists in both visual and textual modalities. Vision language models (VLMs) address this by incorporating a pretrained vision backbone for processing images and a cross-modal projector that adapts image tokens into the LLM dimensional space, thereby providing richer multimodal comprehension. Nevertheless, off-the-shelf VLMs show limited capabilities in handling domain-specific data and are prone to hallucinations. We developed intelligent assistants finetuned from LLaVA models to enhance multimodal understanding in low-dose radiation therapy (LDRT)-a benign approach used in the treatment of cancer-related illnesses. Using multilingual data from 42,673 articles, we devise complex reasoning and detailed description tasks for visual question answering (VQA) benchmarks. Our assistants, trained on 50,882 image-text pairs, demonstrate superior performance over base models as evaluated using LLM-as-a-judge approach, particularly in reducing hallucination and improving domain-specific comprehension.

[Arxiv](https://arxiv.org/abs/2501.15370)