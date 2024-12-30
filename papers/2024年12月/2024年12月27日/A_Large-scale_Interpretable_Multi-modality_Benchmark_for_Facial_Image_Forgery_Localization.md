# 一个用于面部图像伪造定位的大规模可解释多模态基准测试

发布时间：2024年12月27日

`LLM应用` `图像伪造` `多模态`

> A Large-scale Interpretable Multi-modality Benchmark for Facial Image Forgery Localization

# 摘要

> 图像伪造定位，旨在识别图像中的篡改像素，已取得重大进展。传统方法常将此挑战建模为图像分割的变体，把伪造区域的二值分割当作最终成果。但我们觉得，基本的二值伪造掩码难以解释模型的预测。它无法说明模型为何指明某些区域，且对所有伪造像素同等对待，导致难以找出最像伪造的部分。在本研究中，我们通过为伪造图像生成聚焦显著区域的解释来缓解上述局限。为此，我们构建了一个多模态篡改追踪（MMTT）数据集，其中包含运用深度伪造技术处理的面部图像，并配有手动的、可解释的文本注释。为获取高质量注释，要求注释者仔细观察处理后的图像，并清晰阐述伪造区域的典型特征。随后，我们收集了包含 128,303 个图像 - 文本对的数据集。借助 MMTT 数据集，我们开发了 ForgeryTalker，这是一种专为同时实现伪造定位和解释而设计的架构。ForgeryTalker 首先训练一个伪造提示网络来识别解释文本中的关键线索。接着，将区域提示器融入多模态大型语言模型进行微调，以达成定位和解释的双重目标。在 MMTT 数据集上开展的大量实验证实了我们所提出模型的卓越性能。数据集、代码以及预训练的检查点将公开可用，以推动进一步研究，并保证我们结果的可重复性。

> Image forgery localization, which centers on identifying tampered pixels within an image, has seen significant advancements. Traditional approaches often model this challenge as a variant of image segmentation, treating the binary segmentation of forged areas as the end product. We argue that the basic binary forgery mask is inadequate for explaining model predictions. It doesn't clarify why the model pinpoints certain areas and treats all forged pixels the same, making it hard to spot the most fake-looking parts. In this study, we mitigate the aforementioned limitations by generating salient region-focused interpretation for the forgery images. To support this, we craft a Multi-Modal Tramper Tracing (MMTT) dataset, comprising facial images manipulated using deepfake techniques and paired with manual, interpretable textual annotations. To harvest high-quality annotation, annotators are instructed to meticulously observe the manipulated images and articulate the typical characteristics of the forgery regions. Subsequently, we collect a dataset of 128,303 image-text pairs. Leveraging the MMTT dataset, we develop ForgeryTalker, an architecture designed for concurrent forgery localization and interpretation. ForgeryTalker first trains a forgery prompter network to identify the pivotal clues within the explanatory text. Subsequently, the region prompter is incorporated into multimodal large language model for finetuning to achieve the dual goals of localization and interpretation. Extensive experiments conducted on the MMTT dataset verify the superior performance of our proposed model. The dataset, code as well as pretrained checkpoints will be made publicly available to facilitate further research and ensure the reproducibility of our results.

[Arxiv](https://arxiv.org/abs/2412.19685)