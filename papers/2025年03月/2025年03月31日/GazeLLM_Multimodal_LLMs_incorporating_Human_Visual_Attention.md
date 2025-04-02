# GazeLLM：结合人类视觉注意力机制的多模态大型语言模型

发布时间：2025年03月31日

`LLM应用` `人工智能` `机器人`

> GazeLLM: Multimodal LLMs incorporating Human Visual Attention

# 摘要

> 大型语言模型（LLMs）正迈向多模态大语言模型（MLLMs），不仅能处理文本，还能应对图像、音频和视频。结合第一人称视角视频，MLLMs在通过视听信息理解人类活动方面潜力巨大，可应用于人类-计算机交互、现实世界代理和技能迁移等场景。然而，高分辨率、长时间视频处理会产生庞大潜在表示，导致内存和计算需求激增，限制了MLLMs的处理能力。降低分辨率虽能节省内存，却常影响理解效果。本文提出了一种整合眼动追踪数据优化第一人称视频分析的方法，并通过分解视频为注视子区域聚焦关键内容。这种方法在保持甚至超越全分辨率图像理解效果的同时，将视频数据输入减少至原来的十分之一，为高效利用MLLMs解析和应用人类技能提供了创新解决方案。

> Large Language Models (LLMs) are advancing into Multimodal LLMs (MLLMs), capable of processing image, audio, and video as well as text. Combining first-person video, MLLMs show promising potential for understanding human activities through video and audio, enabling many human-computer interaction and human-augmentation applications such as human activity support, real-world agents, and skill transfer to robots or other individuals. However, handling high-resolution, long-duration videos generates large latent representations, leading to substantial memory and processing demands, limiting the length and resolution MLLMs can manage. Reducing video resolution can lower memory usage but often compromises comprehension. This paper introduces a method that optimizes first-person video analysis by integrating eye-tracking data, and proposes a method that decomposes first-person vision video into sub areas for regions of gaze focus. By processing these selectively gazed-focused inputs, our approach achieves task comprehension equivalent to or even better than processing the entire image at full resolution, but with significantly reduced video data input (reduce the number of pixels to one-tenth), offering an efficient solution for using MLLMs to interpret and utilize human skills.

[Arxiv](https://arxiv.org/abs/2504.00221)