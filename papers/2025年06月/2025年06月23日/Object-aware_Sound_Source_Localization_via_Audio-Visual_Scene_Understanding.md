# # 通过视听场景理解实现对象感知的声音定位

发布时间：2025年06月23日

`LLM应用` `计算机视觉` `多模态学习`

> Object-aware Sound Source Localization via Audio-Visual Scene Understanding

# 摘要

> 音频-视觉声音源定位任务旨在通过整合视觉与音频线索，对场景中的发声物体进行空间定位。然而，现有方法在复杂场景中准确定位发声物体时仍面临挑战，尤其是在存在视觉上与发声物体相似的静默物体时。这一限制主要源于传统方法仅依赖简单的音视觉对应关系，无法捕捉发声物体与静默物体之间的细粒度语义差异。为了解决这一难题，我们提出了一种基于多模态大语言模型（MLLMs）的新型声音源定位框架，该框架能够生成详细上下文信息，从而明确区分发声前景物体与静默背景物体。为了有效整合这些详细信息，我们创新性地提出了两个损失函数：基于对象感知的对比对齐（OCA）损失和对象区域隔离（ORI）损失。在MUSIC和VGGSound数据集上的大量实验结果表明，我们的方法在单源和多源定位场景中均显著优于现有方法。代码和生成的详细上下文信息已在GitHub上公开，访问链接为：https://github.com/VisualAIKHU/OA-SSL。

> Audio-visual sound source localization task aims to spatially localize sound-making objects within visual scenes by integrating visual and audio cues. However, existing methods struggle with accurately localizing sound-making objects in complex scenes, particularly when visually similar silent objects coexist. This limitation arises primarily from their reliance on simple audio-visual correspondence, which does not capture fine-grained semantic differences between sound-making and silent objects. To address these challenges, we propose a novel sound source localization framework leveraging Multimodal Large Language Models (MLLMs) to generate detailed contextual information that explicitly distinguishes between sound-making foreground objects and silent background objects. To effectively integrate this detailed information, we introduce two novel loss functions: Object-aware Contrastive Alignment (OCA) loss and Object Region Isolation (ORI) loss. Extensive experimental results on MUSIC and VGGSound datasets demonstrate the effectiveness of our approach, significantly outperforming existing methods in both single-source and multi-source localization scenarios. Code and generated detailed contextual information are available at: https://github.com/VisualAIKHU/OA-SSL.

[Arxiv](https://arxiv.org/abs/2506.18557)