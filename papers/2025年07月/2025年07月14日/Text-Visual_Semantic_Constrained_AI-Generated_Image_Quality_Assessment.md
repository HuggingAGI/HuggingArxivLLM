# 基于文本-视觉语义约束的AI生成图像质量评估

发布时间：2025年07月14日

`LLM应用` `人工智能` `图像生成`

> Text-Visual Semantic Constrained AI-Generated Image Quality Assessment

# 摘要

> 随着人工智能生成图像（AGI）技术的迅猛发展，对其质量进行精准评估变得至关重要。目前主流的方法通常依赖于跨模态模型如CLIP或BLIP来评估文本与图像的对齐度及视觉质量。然而，这些方法在应用于AGI时，面临着语义对齐偏差和细节感知缺失两大挑战。为了解决这些局限性，我们提出了一种名为SC-AGIQA（文本-视觉语义约束的人工智能生成图像质量评估方法）的统一框架，该方法通过引入文本-视觉语义约束，显著提升了对AI生成图像文本-图像一致性和感知失真方面的综合评估能力。

我们的方法整合了多个模型的关键功能，并通过两大核心模块来应对上述挑战：文本辅助语义对齐模块（TSAM）和频域细粒度退化感知模块（FFDPM）。其中，TSAM借助多模态大型语言模型（MLLMs）生成图像描述并与原始提示进行对比，从而缩小语义差距并实现更精确的一致性检查；而FFDPM则从人类视觉系统（HVS）的特性中汲取灵感，结合频域分析与感知敏感度加权，更好地量化细微视觉失真，从而增强对图像中细粒度视觉质量细节的捕捉能力。

在多个基准数据集上进行的广泛实验表明，SC-AGIQA在性能上超越了现有的最先进方法。我们的代码已在GitHub上公开，地址为https://github.com/mozhu1/SC-AGIQA。
    

> With the rapid advancements in Artificial Intelligence Generated Image (AGI) technology, the accurate assessment of their quality has become an increasingly vital requirement. Prevailing methods typically rely on cross-modal models like CLIP or BLIP to evaluate text-image alignment and visual quality. However, when applied to AGIs, these methods encounter two primary challenges: semantic misalignment and details perception missing. To address these limitations, we propose Text-Visual Semantic Constrained AI-Generated Image Quality Assessment (SC-AGIQA), a unified framework that leverages text-visual semantic constraints to significantly enhance the comprehensive evaluation of both text-image consistency and perceptual distortion in AI-generated images. Our approach integrates key capabilities from multiple models and tackles the aforementioned challenges by introducing two core modules: the Text-assisted Semantic Alignment Module (TSAM), which leverages Multimodal Large Language Models (MLLMs) to bridge the semantic gap by generating an image description and comparing it against the original prompt for a refined consistency check, and the Frequency-domain Fine-Grained Degradation Perception Module (FFDPM), which draws inspiration from Human Visual System (HVS) properties by employing frequency domain analysis combined with perceptual sensitivity weighting to better quantify subtle visual distortions and enhance the capture of fine-grained visual quality details in images. Extensive experiments conducted on multiple benchmark datasets demonstrate that SC-AGIQA outperforms existing state-of-the-art methods. The code is publicly available at https://github.com/mozhu1/SC-AGIQA.

[Arxiv](https://arxiv.org/abs/2507.10432)