# GuideDog: 面向盲人及低视力人群的现实世界多模态导航数据集。

发布时间：2025年03月17日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）在帮助视障人士出行方面的应用。它介绍了GuideDog数据集和协作人机框架，以及评估模型视觉感知能力的方法。这些内容都是关于MLLMs的实际应用，因此归类为LLM应用。` `视觉辅助` `增强现实`

> GuideDog: A Real-World Egocentric Multimodal Dataset for Blind and Low-Vision Accessibility-Aware Guidance

# 摘要

> 出行仍是全球 22 亿视力障碍者（BLV）面临的重要挑战，其中 7% 的视障人士每月至少发生一次跌倒。尽管多模态大型语言模型（MLLMs）的最新进展为 BLV 辅助提供了巨大潜力，但受限数据集的开发严重阻碍了其发展。这一局限源于 BLV 意识标注需要专业知识和大量人工投入。为解决这一问题，我们推出了 GuideDog，一个包含 22K 图像描述对（含 2K 人工标注对）的新型无障碍感知引导数据集，捕捉从行人视角观察的多样化现实场景。我们的方法通过基于无障碍标准的协作人机框架，将标注负担从生成转移到验证，显著提升了效率同时保持高质量标注。我们还开发了 GuideDogQA，一个包含 818 个样本的子集，通过多项选择题评估细粒度视觉感知能力，特别是物体识别和相对深度感知。实验结果突显了准确空间理解在有效 BLV 引导中的重要性。GuideDog 和 GuideDogQA 将推动基于 MLLM 的 BLV 辅助技术研究，同时为机器人和增强现实中的自我中心场景理解带来更广泛的应用。代码和数据集将公开可用。

> Mobility remains a significant challenge for the 2.2 billion people worldwide affected by blindness and low vision (BLV), with 7% of visually impaired individuals experiencing falls at least once a month. While recent advances in Multimodal Large Language Models (MLLMs) offer promising opportunities for BLV assistance, their development has been hindered by limited datasets. This limitation stems from the fact that BLV-aware annotation requires specialized domain knowledge and intensive labor. To address this gap, we introduce GuideDog, a novel accessibility-aware guide dataset containing 22K image-description pairs (including 2K human-annotated pairs) that capture diverse real-world scenes from a pedestrian's viewpoint. Our approach shifts the annotation burden from generation to verification through a collaborative human-AI framework grounded in established accessibility standards, significantly improving efficiency while maintaining high-quality annotations. We also develop GuideDogQA, a subset of 818 samples featuring multiple-choice questions designed to evaluate fine-grained visual perception capabilities, specifically object recognition and relative depth perception. Our experimental results highlight the importance of accurate spatial understanding for effective BLV guidance. GuideDog and GuideDogQA will advance research in MLLM-based assistive technologies for BLV individuals while contributing to broader applications in understanding egocentric scenes for robotics and augmented reality. The code and dataset will be publicly available.

[Arxiv](https://arxiv.org/abs/2503.12844)