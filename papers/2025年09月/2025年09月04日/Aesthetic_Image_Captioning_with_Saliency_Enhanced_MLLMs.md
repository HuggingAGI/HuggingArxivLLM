# 显著性增强多模态大模型的美学图像描述

发布时间：2025年09月04日

`LLM应用` `媒体与娱乐`

> Aesthetic Image Captioning with Saliency Enhanced MLLMs

# 摘要

> 美学图像描述生成（AIC）旨在生成图像美学的文本描述，现已成为计算美学领域的关键研究方向。近年来，预训练多模态大语言模型（MLLMs）迅猛发展，推动了融合视觉与文本模态的图像美学研究大幅增长。然而，现有图像美学研究多聚焦于美学评分预测，在AIC领域的应用十分有限。目前基于MLLMs的AIC工作大多依赖微调方法，未能专门调整模型以聚焦目标美学内容。为此，我们提出美学显著性增强多模态大语言模型（ASE-MLLM）——一个端到端框架，可将美学显著性明确融入MLLMs。该框架中，我们引入图像美学显著性模块（IASM），能高效提取图像的美学显著性特征；同时设计IAS-ViT作为MLLMs的图像编码器，借助交叉注意力机制将美学显著性特征与原始图像特征相融合。据我们所知，ASE-MLLM是首个专为AIC任务将图像美学显著性整合进MLLMs的框架。大量实验结果显示，我们的方法在当前主流AIC基准测试中显著优于传统方法和通用MLLMs，实现了最先进（SOTA）的性能。

> Aesthetic Image Captioning (AIC) aims to generate textual descriptions of image aesthetics, becoming a key research direction in the field of computational aesthetics. In recent years, pretrained Multimodal Large Language Models (MLLMs) have advanced rapidly, leading to a significant increase in image aesthetics research that integrates both visual and textual modalities. However, most existing studies on image aesthetics primarily focus on predicting aesthetic ratings and have shown limited application in AIC. Existing AIC works leveraging MLLMs predominantly rely on fine-tuning methods without specifically adapting MLLMs to focus on target aesthetic content. To address this limitation, we propose the Aesthetic Saliency Enhanced Multimodal Large Language Model (ASE-MLLM), an end-to-end framework that explicitly incorporates aesthetic saliency into MLLMs. Within this framework, we introduce the Image Aesthetic Saliency Module (IASM), which efficiently and effectively extracts aesthetic saliency features from images. Additionally, we design IAS-ViT as the image encoder for MLLMs, this module fuses aesthetic saliency features with original image features via a cross-attention mechanism. To the best of our knowledge, ASE-MLLM is the first framework to integrate image aesthetic saliency into MLLMs specifically for AIC tasks. Extensive experiments demonstrated that our approach significantly outperformed traditional methods and generic MLLMs on current mainstream AIC benchmarks, achieving state-of-the-art (SOTA) performance.

[Arxiv](https://arxiv.org/abs/2509.04378)