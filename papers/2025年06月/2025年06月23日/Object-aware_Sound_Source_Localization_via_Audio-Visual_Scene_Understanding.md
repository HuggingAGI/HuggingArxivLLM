# # 基于音频-视觉场景理解的物体感知声音定位

发布时间：2025年06月23日

`LLM应用

摘要中提到的研究利用多模态大型语言模型（MLLMs）来生成详细上下文信息，以解决声音源定位问题。这属于将大型语言模型应用于具体任务的范畴，因此归类为LLM应用。` `声音源定位` `多模态学习`

> Object-aware Sound Source Localization via Audio-Visual Scene Understanding

# 摘要

> 音频-视觉声音源定位任务通过整合视觉和音频线索，在视觉场景中对发声物体进行空间定位。然而，现有方法在复杂场景下精确定位声音源物体时面临挑战，尤其是在存在视觉上相似但无声物体的情况下。这一局限主要源于它们依赖简单的视听对应关系，无法捕捉发声物体与无声物体之间的细微语义差异。为了解决这些挑战，我们提出了一种新型声音源定位框架，利用多模态大型语言模型（MLLMs）生成详细上下文信息，以明确区分发声前景物体与无声背景物体。为了有效整合这些详细信息，我们引入了两个新型损失函数：基于对象感知的对比对齐（OCA）损失和对象区域隔离（ORI）损失。在MUSIC和VGGSound数据集上的大量实验结果证明了我们方法的有效性，在单源和多源定位场景中显著超越现有方法。代码和生成的详细上下文信息可访问：https://github.com/VisualAIKHU/OA-SSL。

> Audio-visual sound source localization task aims to spatially localize sound-making objects within visual scenes by integrating visual and audio cues. However, existing methods struggle with accurately localizing sound-making objects in complex scenes, particularly when visually similar silent objects coexist. This limitation arises primarily from their reliance on simple audio-visual correspondence, which does not capture fine-grained semantic differences between sound-making and silent objects. To address these challenges, we propose a novel sound source localization framework leveraging Multimodal Large Language Models (MLLMs) to generate detailed contextual information that explicitly distinguishes between sound-making foreground objects and silent background objects. To effectively integrate this detailed information, we introduce two novel loss functions: Object-aware Contrastive Alignment (OCA) loss and Object Region Isolation (ORI) loss. Extensive experimental results on MUSIC and VGGSound datasets demonstrate the effectiveness of our approach, significantly outperforming existing methods in both single-source and multi-source localization scenarios. Code and generated detailed contextual information are available at: https://github.com/VisualAIKHU/OA-SSL.

[Arxiv](https://arxiv.org/abs/2506.18557)