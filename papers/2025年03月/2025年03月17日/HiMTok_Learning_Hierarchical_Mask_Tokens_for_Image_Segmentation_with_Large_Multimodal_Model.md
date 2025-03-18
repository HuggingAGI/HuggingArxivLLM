# HiMTok——利用大型多模态模型学习分层掩码代币实现图像分割

发布时间：2025年03月17日

`LLM应用` `图像分割` `计算机视觉`

> HiMTok: Learning Hierarchical Mask Tokens for Image Segmentation with Large Multimodal Model

# 摘要

> 大型多模态模型（LMMs）在图像分割领域的卓越表现引起了广泛关注。现有基于LMM的分割方法要么使用边界点表示掩膜，要么引入特殊分割令牌，但这些方法常因表示不足和架构复杂而受限。我们提出了一种名为分层掩膜标记化器（HiMTok）的新方法，通过最多32个令牌实现从粗到细的紧凑掩膜表示，无需原始图像即可解码，完美契合LLM的下一步令牌预测机制。我们设计了三阶段训练方案，结合分层掩膜损失函数，实现高效学习。同时，支持边界框与掩膜令牌的双向转换，充分发挥多任务训练优势。实验结果表明，HiMTok在各类分割任务中均达到顶尖水平，同时显著提升了视觉定位能力。

> The remarkable performance of large multimodal models (LMMs) has attracted significant interest from the image segmentation community. To align with the next-token-prediction paradigm, current LMM-driven segmentation methods either use object boundary points to represent masks or introduce special segmentation tokens, whose hidden states are decoded by a segmentation model requiring the original image as input. However, these approaches often suffer from inadequate mask representation and complex architectures, limiting the potential of LMMs. In this work, we propose the Hierarchical Mask Tokenizer (HiMTok), which represents segmentation masks with up to 32 tokens and eliminates the need for the original image during mask de-tokenization. HiMTok allows for compact and coarse-to-fine mask representations, aligning well with the LLM next-token-prediction paradigm and facilitating the direct acquisition of segmentation capabilities. We develop a 3-stage training recipe for progressive learning of segmentation and visual capabilities, featuring a hierarchical mask loss for effective coarse-to-fine learning. Additionally, we enable bidirectional information flow, allowing conversion between bounding boxes and mask tokens to fully leverage multi-task training potential. Extensive experiments demonstrate that our method achieves state-of-the-art performance across various segmentation tasks,while also enhancing visual grounding and maintaining overall visual understanding.

[Arxiv](https://arxiv.org/abs/2503.13026)