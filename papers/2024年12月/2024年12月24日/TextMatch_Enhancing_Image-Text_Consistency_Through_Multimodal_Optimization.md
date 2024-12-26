# TextMatch：借由多模态优化提升图像 - 文本的一致性

发布时间：2024年12月24日

`LLM应用` `图像生成` `多模态`

> TextMatch: Enhancing Image-Text Consistency Through Multimodal Optimization

# 摘要

> 文本到图像的生成模型在依据文本生成图像时表现出众，但在保证输出与提示的对齐和一致性上却力不从心。本文引入了 TextMatch，这是一个新颖的框架，它借助多模态优化来处理文本到图像（T2I）生成与编辑中的图像和文本差异。TextMatch 运用由大型语言模型（LLMs）和视觉问答（VQA）模型驱动的评分策略，评估提示与生成图像之间的语义一致性。通过融合多模态的上下文学习和思维链推理，我们的方法通过迭代优化动态改进提示。这一过程确保生成的图像能更好地领会用户意图，进而实现更高的保真度和相关性。大量实验表明，TextMatch 在多个基准测试中显著提升了文本与图像的一致性，为增强文本到图像生成模型的能力构建了一个可靠的框架。我们的代码可在 https://anonymous.4open.science/r/TextMatch-F55C/ 获取。

> Text-to-image generative models excel in creating images from text but struggle with ensuring alignment and consistency between outputs and prompts. This paper introduces TextMatch, a novel framework that leverages multimodal optimization to address image-text discrepancies in text-to-image (T2I) generation and editing. TextMatch employs a scoring strategy powered by large language models (LLMs) and visual question-answering (VQA) models to evaluate semantic consistency between prompts and generated images. By integrating multimodal in-context learning and chain of thought reasoning, our method dynamically refines prompts through iterative optimization. This process ensures that the generated images better capture user intent of, resulting in higher fidelity and relevance. Extensive experiments demonstrate that TextMatch significantly improves text-image consistency across multiple benchmarks, establishing a reliable framework for advancing the capabilities of text-to-image generative models. Our code is available at https://anonymous.4open.science/r/TextMatch-F55C/.

[Arxiv](https://arxiv.org/abs/2412.18185)