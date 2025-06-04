# 原生级分辨率图像生成

发布时间：2025年06月03日

`其他` `计算机视觉` `生成模型`

> Native-Resolution Image Synthesis

# 摘要

> 我们推出了一种开创性的生成建模范式——原生分辨率图像合成，它能够生成任意分辨率和宽高比的图像。这一方法突破了传统固定分辨率、正方形图像生成的局限性，通过原生支持可变长度视觉令牌，解决了传统技术的核心难题。为此，我们提出了原生分辨率扩散Transformer（NiT），这种创新架构能够在去噪过程中显式建模不同的分辨率和宽高比。摆脱了固定格式的束缚，NiT能够从涵盖广泛分辨率和宽高比的图像中学习到更本质的视觉分布特征。值得注意的是，单个NiT模型在ImageNet-256x256和512x512基准测试中同时达到了当前最优的性能水平。更令人惊喜的是，类似于先进大型语言模型中强大的零样本学习能力，仅在ImageNet上训练的NiT展现出了卓越的零样本泛化能力。它能够成功生成高保真的高分辨率图像（例如1536x1536）和各种宽高比（例如16:9、3:1、4:3）的图像，具体效果如图1所示。这些成果表明，原生分辨率建模在连接视觉生成建模与先进LLM方法方面具有巨大的潜力。

> We introduce native-resolution image synthesis, a novel generative modeling paradigm that enables the synthesis of images at arbitrary resolutions and aspect ratios. This approach overcomes the limitations of conventional fixed-resolution, square-image methods by natively handling variable-length visual tokens, a core challenge for traditional techniques. To this end, we introduce the Native-resolution diffusion Transformer (NiT), an architecture designed to explicitly model varying resolutions and aspect ratios within its denoising process. Free from the constraints of fixed formats, NiT learns intrinsic visual distributions from images spanning a broad range of resolutions and aspect ratios. Notably, a single NiT model simultaneously achieves the state-of-the-art performance on both ImageNet-256x256 and 512x512 benchmarks. Surprisingly, akin to the robust zero-shot capabilities seen in advanced large language models, NiT, trained solely on ImageNet, demonstrates excellent zero-shot generalization performance. It successfully generates high-fidelity images at previously unseen high resolutions (e.g., 1536 x 1536) and diverse aspect ratios (e.g., 16:9, 3:1, 4:3), as shown in Figure 1. These findings indicate the significant potential of native-resolution modeling as a bridge between visual generative modeling and advanced LLM methodologies.

[Arxiv](https://arxiv.org/abs/2506.03131)