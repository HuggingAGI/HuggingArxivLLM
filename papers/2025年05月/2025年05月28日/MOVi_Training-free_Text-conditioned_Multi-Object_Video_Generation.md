# # MOVi：无需训练的文本条件多目标视频生成

发布时间：2025年05月28日

`LLM应用` `视频生成` `视频合成`

> MOVi: Training-free Text-conditioned Multi-Object Video Generation

# 摘要

> 近期，扩散式文本到视频（T2V）模型取得了显著进展，但这些模型在生成包含多个物体的视频时仍面临挑战。大多数模型难以准确捕捉复杂物体间的交互关系，常常将某些物体视为静态背景元素，限制了它们的运动。此外，它们往往无法根据提示生成多个指定的独立物体，导致生成错误或物体间特征混杂。本文提出了一种基于扩散模型和大型语言模型（LLMs）开放世界知识的无训练多物体视频生成新方法。我们使用LLM作为物体轨迹的“导演”，通过噪声重初始化应用这些轨迹，实现对现实运动的精准控制。我们进一步通过调整注意力机制优化生成过程，以更好地捕捉物体特有特征和运动模式，并防止物体间特征干扰。大量实验验证了我们无训练方法的有效性，显著提升了现有视频扩散模型的多物体生成能力，运动动态和物体生成精度均提升了42%，同时保持了高保真度和运动流畅性。

> Recent advances in diffusion-based text-to-video (T2V) models have demonstrated remarkable progress, but these models still face challenges in generating videos with multiple objects. Most models struggle with accurately capturing complex object interactions, often treating some objects as static background elements and limiting their movement. In addition, they often fail to generate multiple distinct objects as specified in the prompt, resulting in incorrect generations or mixed features across objects. In this paper, we present a novel training-free approach for multi-object video generation that leverages the open world knowledge of diffusion models and large language models (LLMs). We use an LLM as the ``director'' of object trajectories, and apply the trajectories through noise re-initialization to achieve precise control of realistic movements. We further refine the generation process by manipulating the attention mechanism to better capture object-specific features and motion patterns, and prevent cross-object feature interference. Extensive experiments validate the effectiveness of our training free approach in significantly enhancing the multi-object generation capabilities of existing video diffusion models, resulting in 42% absolute improvement in motion dynamics and object generation accuracy, while also maintaining high fidelity and motion smoothness.

[Arxiv](https://arxiv.org/abs/2505.22980)