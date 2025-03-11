# SemHiTok：基于语义引导的分层代码本，实现统一图像标记，助力多模态理解和生成。

发布时间：2025年03月09日

`其他` `图像处理` `多模态模型`

> SemHiTok: A Unified Image Tokenizer via Semantic-Guided Hierarchical Codebook for Multimodal Understanding and Generation

# 摘要

> 我们推出 SemHiTok，一款基于语义引导分层码本的统一图像tokenizer，为多模态理解和生成任务提供一致的离散特征表示。近期，统一多模态大模型（MLLMs）在研究领域掀起探索热潮。此前研究尝试通过结合语义特征重建和像素重建损失函数来训练统一图像tokenizer。然而，多模态理解和生成任务对特征层次的侧重不同，使得联合训练方法在权衡上面临重大挑战。SemHiTok通过语义引导分层码本巧妙应对这一难题，在预训练语义码本基础上构建纹理子码本。这种设计不仅解耦了语义重建与像素重建的训练过程，更赋予tokenizer提取低级纹理特征的能力，同时丝毫不影响其对高级语义特征的提取能力。实验结果表明，SemHiTok在256X256分辨率下实现了超越其他统一tokenizer的顶尖rFID分数，并在多模态理解和生成任务中展现出极具竞争力的性能表现。

> We present SemHiTok, a unified image Tokenizer via Semantic-Guided Hierarchical codebook that provides consistent discrete feature representations for multimodal understanding and generation tasks. Recently, unified multimodal large models (MLLMs) for understanding and generation have sparked exploration within research community. Previous works attempt to train a unified image tokenizer by combining loss functions for semantic feature reconstruction and pixel reconstruction. However, due to the differing levels of features prioritized by multimodal understanding and generation tasks, joint training methods face significant challenges in achieving a good trade-off. SemHiTok addresses this challenge through Semantic-Guided Hierarchical codebook which builds texture sub-codebooks on pre-trained semantic codebook. This design decouples the training of semantic reconstruction and pixel reconstruction and equips the tokenizer with low-level texture feature extraction capability without degradation of high-level semantic feature extraction ability. Our experiments demonstrate that SemHiTok achieves state-of-the-art rFID score at 256X256resolution compared to other unified tokenizers, and exhibits competitive performance on multimodal understanding and generation tasks.

[Arxiv](https://arxiv.org/abs/2503.06764)