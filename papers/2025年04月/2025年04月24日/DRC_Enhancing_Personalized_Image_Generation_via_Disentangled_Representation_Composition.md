# DRC：通过解耦表示组合提升个性化图像生成效果

发布时间：2025年04月24日

`其他` `计算机视觉` `多模态内容创作`

> DRC: Enhancing Personalized Image Generation via Disentangled Representation Composition

# 摘要

> 个性化图像生成正成为多模态内容创作领域的前沿方向，它通过分析用户历史交互图像和多模态指令，生成符合个人风格偏好（如色彩搭配、角色设计、构图布局）和语义意图（如情感表达、动作场景、环境背景）的定制化图像。尽管已取得显著进展，现有方法——无论是基于扩散模型、大型语言模型还是大型多模态模型（LMMs）——都难以精准捕捉并融合用户的风格偏好和语义意图。尤为突出的是，基于LMMs的最先进方法因视觉特征的纠缠问题而面临“指导坍塌”困境，导致生成的图像无法忠实保留用户偏好的风格或准确反映指定的语义信息。

为突破这一瓶颈，我们提出了一种名为DRC的创新性个性化图像生成框架，通过解耦表征组合技术增强LMMs的生成能力。DRC从用户的历史图像和参考图像中显式提取风格偏好和语义意图，形成特定于用户的潜在指令，从而精准指导LMMs的图像生成过程。具体而言，DRC包含两个关键学习阶段：1）解耦学习阶段，采用双塔解耦器显式分离风格和语义特征，并通过基于重建的优化范式和难度感知的重要采样技术提升学习效率；2）个性化建模阶段，应用语义保留增强策略，有效适应解耦后的表征，实现更加稳定和高质量的个性化图像生成。在两个基准数据集上的大量实验表明，DRC不仅在性能上表现优异，还成功解决了“指导坍塌”问题，充分证明了解耦表示学习在实现可控且高效的个性化图像生成中的关键作用。

> Personalized image generation has emerged as a promising direction in multimodal content creation. It aims to synthesize images tailored to individual style preferences (e.g., color schemes, character appearances, layout) and semantic intentions (e.g., emotion, action, scene contexts) by leveraging user-interacted history images and multimodal instructions. Despite notable progress, existing methods -- whether based on diffusion models, large language models, or Large Multimodal Models (LMMs) -- struggle to accurately capture and fuse user style preferences and semantic intentions. In particular, the state-of-the-art LMM-based method suffers from the entanglement of visual features, leading to Guidance Collapse, where the generated images fail to preserve user-preferred styles or reflect the specified semantics.
  To address these limitations, we introduce DRC, a novel personalized image generation framework that enhances LMMs through Disentangled Representation Composition. DRC explicitly extracts user style preferences and semantic intentions from history images and the reference image, respectively, to form user-specific latent instructions that guide image generation within LMMs. Specifically, it involves two critical learning stages: 1) Disentanglement learning, which employs a dual-tower disentangler to explicitly separate style and semantic features, optimized via a reconstruction-driven paradigm with difficulty-aware importance sampling; and 2) Personalized modeling, which applies semantic-preserving augmentations to effectively adapt the disentangled representations for robust personalized generation. Extensive experiments on two benchmarks demonstrate that DRC shows competitive performance while effectively mitigating the guidance collapse issue, underscoring the importance of disentangled representation learning for controllable and effective personalized image generation.

[Arxiv](https://arxiv.org/abs/2504.17349)