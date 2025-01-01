# 用于弱监督语义分割的图像增强代理

发布时间：2024年12月29日

`Agent` `计算机视觉` `图像分割`

> Image Augmentation Agent for Weakly Supervised Semantic Segmentation

# 摘要

> 弱监督语义分割（WSSS）仅凭借图像级标签就取得了显著成就。然而，现有的多数 WSSS 方法都聚焦于设计新的网络结构和损失函数来生成更精准的密集标签，却忽视了固定数据集所带来的限制，这可能会制约性能的提升。我们觉得更多样化的可训练图像能给 WSSS 提供更丰富的信息，帮助模型理解更全面的语义模式。所以在本文中，我们引入了一种名为图像增强代理（IAA）的新方法，表明从数据生成的视角增强 WSSS 是可行的。IAA 主要设计了一个增强代理，借助大型语言模型（LLMs）和扩散模型为 WSSS 自动生成额外的图像。在实际操作中，为解决 LLMs 在提示生成中的不稳定性问题，我们开发了一种提示自优化机制。它能让 LLMs 重新评估生成提示的合理性，从而产生更连贯的提示。另外，我们在扩散生成过程中插入了一个在线过滤器，以动态保障生成图像的质量和平衡。实验结果显示，我们的方法在 PASCAL VOC 2012 和 MS COCO 2014 数据集上大幅超越了最先进的 WSSS 方法。

> Weakly-supervised semantic segmentation (WSSS) has achieved remarkable progress using only image-level labels. However, most existing WSSS methods focus on designing new network structures and loss functions to generate more accurate dense labels, overlooking the limitations imposed by fixed datasets, which can constrain performance improvements. We argue that more diverse trainable images provides WSSS richer information and help model understand more comprehensive semantic pattern. Therefore in this paper, we introduce a novel approach called Image Augmentation Agent (IAA) which shows that it is possible to enhance WSSS from data generation perspective. IAA mainly design an augmentation agent that leverages large language models (LLMs) and diffusion models to automatically generate additional images for WSSS. In practice, to address the instability in prompt generation by LLMs, we develop a prompt self-refinement mechanism. It allow LLMs to re-evaluate the rationality of generated prompts to produce more coherent prompts. Additionally, we insert an online filter into diffusion generation process to dynamically ensure the quality and balance of generated images. Experimental results show that our method significantly surpasses state-of-the-art WSSS approaches on the PASCAL VOC 2012 and MS COCO 2014 datasets.

[Arxiv](https://arxiv.org/abs/2412.20439)