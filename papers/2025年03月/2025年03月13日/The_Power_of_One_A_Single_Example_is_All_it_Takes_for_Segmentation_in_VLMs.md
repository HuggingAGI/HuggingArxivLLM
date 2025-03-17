# # 一的力量：一个例子，足以成就 VLM 中的分割任务

发布时间：2025年03月13日

`LLM应用` `计算机视觉` `图像分割`

> The Power of One: A Single Example is All it Takes for Segmentation in VLMs

# 摘要

> 大规模视觉-语言模型（VLMs）通过大量图像-文本对数据集训练，能够隐式地学习文本与图像区域的关联，展现出强大的多模态理解能力。这种能力使得无需大量标注数据集即可实现零样本物体检测和分割成为可能。然而，这些方法的表现高度依赖于提示工程和手动选择注意力层的层数或头数。在本研究中，我们发现，相较于单纯依赖文本提示，为每个类别提供一个视觉示例并对文本到图像的注意力层和嵌入进行微调，能够显著提升性能。此外，我们提出了一种通过跨多层和/或提示进行少量样本微调来学习集成模型的方法。为了识别最优的文本到图像注意力层，我们提出了一种基于熵的排名和选择机制，无需分割标签即可实现。这消除了对文本到图像注意力层超参数选择的需求，为开放词汇分割提供了一个更灵活和可扩展的解决方案。我们展示了这种方法不仅能够实现强大的零样本性能，还能通过单个视觉示例的微调进一步增强。此外，我们的方法和发现具有普适性，可以应用于各种视觉-语言模型（VLMs）。

> Large-scale vision-language models (VLMs), trained on extensive datasets of image-text pairs, exhibit strong multimodal understanding capabilities by implicitly learning associations between textual descriptions and image regions. This emergent ability enables zero-shot object detection and segmentation, using techniques that rely on text-image attention maps, without necessarily training on abundant labeled segmentation datasets. However, performance of such methods depends heavily on prompt engineering and manually selected layers or head choices for the attention layers. In this work, we demonstrate that, rather than relying solely on textual prompts, providing a single visual example for each category and fine-tuning the text-to-image attention layers and embeddings significantly improves the performance. Additionally, we propose learning an ensemble through few-shot fine-tuning across multiple layers and/or prompts. An entropy-based ranking and selection mechanism for text-to-image attention layers is proposed to identify the top-performing layers without the need for segmentation labels. This eliminates the need for hyper-parameter selection of text-to-image attention layers, providing a more flexible and scalable solution for open-vocabulary segmentation. We show that this approach yields strong zero-shot performance, further enhanced through fine-tuning with a single visual example. Moreover, we demonstrate that our method and findings are general and can be applied across various vision-language models (VLMs).

[Arxiv](https://arxiv.org/abs/2503.10779)