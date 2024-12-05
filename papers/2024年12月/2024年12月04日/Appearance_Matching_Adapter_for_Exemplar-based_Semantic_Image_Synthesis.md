# 用于基于示例的语义图像合成的外观匹配适配器

发布时间：2024年12月04日

`其他` `图像合成` `计算机视觉`

> Appearance Matching Adapter for Exemplar-based Semantic Image Synthesis

# 摘要

> 基于范例的语义图像合成旨在生成与给定语义内容相符的图像，同时保留范例图像的外观。像 ControlNet 这类传统的结构引导模型有局限性，无法直接以范例图像为输入，仅依靠文本提示来控制外观。近来的免调优方法在预训练扩散模型的增强自注意力机制中，通过隐式跨图像匹配将范例图像的局部外观转移至合成图像，从而解决了这一难题。但这些方法用于有明显几何变形的内容丰富场景（比如驾驶场景）时会遇到挑战。本文中，我们提出了外观匹配适配器（AM-Adapter），这是一个可学习的框架，它通过融入来自分割图的语义信息来强化增强自注意力中的跨图像匹配。为有效区分生成和匹配过程，我们采用了分阶段训练的方式。起初，我们训练结构引导和生成网络，接着在其他网络保持不变的情况下训练 AM-Adapter。在推理时，我们引入了自动范例检索方法，能高效选择范例图像 - 分割对。尽管使用的可学习参数数量有限，但我们的方法达到了先进水平，在语义对齐保留和局部外观保真度方面表现出色。大量的消融研究进一步验证了我们的设计选择。代码和预训练权重将公开可用：https://cvlab-kaist.github.io/AM-Adapter/

> Exemplar-based semantic image synthesis aims to generate images aligned with given semantic content while preserving the appearance of an exemplar image. Conventional structure-guidance models, such as ControlNet, are limited in that they cannot directly utilize exemplar images as input, relying instead solely on text prompts to control appearance. Recent tuning-free approaches address this limitation by transferring local appearance from the exemplar image to the synthesized image through implicit cross-image matching in the augmented self-attention mechanism of pre-trained diffusion models. However, these methods face challenges when applied to content-rich scenes with significant geometric deformations, such as driving scenes. In this paper, we propose the Appearance Matching Adapter (AM-Adapter), a learnable framework that enhances cross-image matching within augmented self-attention by incorporating semantic information from segmentation maps. To effectively disentangle generation and matching processes, we adopt a stage-wise training approach. Initially, we train the structure-guidance and generation networks, followed by training the AM-Adapter while keeping the other networks frozen. During inference, we introduce an automated exemplar retrieval method to efficiently select exemplar image-segmentation pairs. Despite utilizing a limited number of learnable parameters, our method achieves state-of-the-art performance, excelling in both semantic alignment preservation and local appearance fidelity. Extensive ablation studies further validate our design choices. Code and pre-trained weights will be publicly available.: https://cvlab-kaist.github.io/AM-Adapter/

[Arxiv](https://arxiv.org/abs/2412.03150)