# 结构化信息：提升文本到图像生成中的空间关系

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> Structured Information for Improving Spatial Relationships in Text-to-Image Generation

# 摘要

> 文本到图像（T2I）生成技术发展迅猛，然而，要精准捕捉自然语言提示中描述的空间关系，仍是一大难题。以往研究多通过提示优化、空间锚定生成及语义细化等方法应对这一挑战。本研究则提出一种轻量级方案：利用微调语言模型自动转换并生成基于元组的结构化信息，以此增强提示，并将其无缝融入T2I生成流程。实验结果显示，该方法大幅提升了空间准确性，且通过Inception Score评估，整体图像质量并未下降。不仅如此，自动生成的元组质量可媲美人工制作的元组。这种结构化信息为提升T2I生成中的空间关系提供了实用且可迁移的解决方案，有效弥补了当前大规模生成系统的一大短板。

> Text-to-image (T2I) generation has advanced rapidly, yet faithfully capturing spatial relationships described in natural language prompts remains a major challenge. Prior efforts have addressed this issue through prompt optimization, spatially grounded generation, and semantic refinement. This work introduces a lightweight approach that augments prompts with tuple-based structured information, using a fine-tuned language model for automatic conversion and seamless integration into T2I pipelines. Experimental results demonstrate substantial improvements in spatial accuracy, without compromising overall image quality as measured by Inception Score. Furthermore, the automatically generated tuples exhibit quality comparable to human-crafted tuples. This structured information provides a practical and portable solution to enhance spatial relationships in T2I generation, addressing a key limitation of current large-scale generative systems.

[Arxiv](https://arxiv.org/abs/2509.15962)