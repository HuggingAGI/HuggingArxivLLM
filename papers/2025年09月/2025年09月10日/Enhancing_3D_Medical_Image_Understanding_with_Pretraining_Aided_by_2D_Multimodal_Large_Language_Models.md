# 借助2D多模态大型语言模型辅助的预训练提升3D医学图像理解

发布时间：2025年09月10日

`LLM应用` `医疗健康`

> Enhancing 3D Medical Image Understanding with Pretraining Aided by 2D Multimodal Large Language Models

# 摘要

> 在医学领域，理解3D医学图像体块至关重要，但现有的3D医学卷积及基于Transformer的自监督学习（SSL）方法普遍缺乏深度语义理解能力。多模态大型语言模型（MLLMs）的最新突破，为通过文本描述增强图像理解提供了极具潜力的解决方案。为充分发挥这些2D MLLMs在3D医学图像理解中的作用，我们提出了Med3DInsight——一种新颖的预训练框架，它通过专门设计的平面切片感知Transformer模块，将3D图像编码器与2D MLLMs无缝集成。此外，该模型还采用基于部分最优传输的对齐机制，对LLM生成内容中的潜在噪声具有更强的抗干扰能力。Med3DInsight为无需人工标注的可扩展多模态3D医学表征学习开辟了新范式。大量实验验证，在包含CT和MRI模态的多个公共数据集上，该方法在分割与分类这两项下游任务中均达到了最先进水平，性能超越现有SSL方法。Med3DInsight能够无缝融入现有3D医学图像理解网络，有望提升其性能表现。相关源代码、生成数据集及预训练模型将开源至https://github.com/Qybc/Med3DInsight。

> Understanding 3D medical image volumes is critical in the medical field, yet existing 3D medical convolution and transformer-based self-supervised learning (SSL) methods often lack deep semantic comprehension. Recent advancements in multimodal large language models (MLLMs) provide a promising approach to enhance image understanding through text descriptions. To leverage these 2D MLLMs for improved 3D medical image understanding, we propose Med3DInsight, a novel pretraining framework that integrates 3D image encoders with 2D MLLMs via a specially designed plane-slice-aware transformer module. Additionally, our model employs a partial optimal transport based alignment, demonstrating greater tolerance to noise introduced by potential noises in LLM-generated content. Med3DInsight introduces a new paradigm for scalable multimodal 3D medical representation learning without requiring human annotations. Extensive experiments demonstrate our state-of-the-art performance on two downstream tasks, i.e., segmentation and classification, across various public datasets with CT and MRI modalities, outperforming current SSL methods. Med3DInsight can be seamlessly integrated into existing 3D medical image understanding networks, potentially enhancing their performance. Our source code, generated datasets, and pre-trained models will be available at https://github.com/Qybc/Med3DInsight.

[Arxiv](https://arxiv.org/abs/2509.09064)