# YingSound：通过多模态思维链控制实现的视频引导音效生成

发布时间：2024年12月12日

`LLM应用`

> YingSound: Video-Guided Sound Effects Generation with Multi-modal Chain-of-Thought Controls

# 摘要

> 在为产品级视频生成音效时，不同场景仅有少量有标签数据可用，这就要求在少样本的情况下生成高质量声音。为应对现实场景中有标签数据有限的挑战，我们推出了 YingSound，这是一个用于视频引导声音生成的基础模型，支持在少样本场景下生成高质量音频。具体而言，YingSound 由两大模块构成。第一个模块采用条件流匹配变压器，实现音频和视觉模态声音生成中的有效语义对齐。此模块旨在构建一个可学习的音视聚合器（AVA），在多个阶段将高分辨率视觉特征与相应音频特征相融合。第二个模块通过提出的多模态视音频思维链（CoT）方法开发，用于在少样本场景下生成更精细的音效。最后，展示了一个涵盖各种现实场景的行业标准视频转音频（V2A）数据集。通过自动评估和人类研究，我们证明 YingSound 能在不同条件输入下有效生成高质量同步声音。项目页面：url{https://giantailab.github.io/yingsound/}

> Generating sound effects for product-level videos, where only a small amount of labeled data is available for diverse scenes, requires the production of high-quality sounds in few-shot settings. To tackle the challenge of limited labeled data in real-world scenes, we introduce YingSound, a foundation model designed for video-guided sound generation that supports high-quality audio generation in few-shot settings. Specifically, YingSound consists of two major modules. The first module uses a conditional flow matching transformer to achieve effective semantic alignment in sound generation across audio and visual modalities. This module aims to build a learnable audio-visual aggregator (AVA) that integrates high-resolution visual features with corresponding audio features at multiple stages. The second module is developed with a proposed multi-modal visual-audio chain-of-thought (CoT) approach to generate finer sound effects in few-shot settings. Finally, an industry-standard video-to-audio (V2A) dataset that encompasses various real-world scenarios is presented. We show that YingSound effectively generates high-quality synchronized sounds across diverse conditional inputs through automated evaluations and human studies. Project Page: url{https://giantailab.github.io/yingsound/}

[Arxiv](https://arxiv.org/abs/2412.09168)