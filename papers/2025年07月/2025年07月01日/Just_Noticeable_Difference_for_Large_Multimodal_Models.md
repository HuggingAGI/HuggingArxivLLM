# # 刚刚可察觉差异：大型多模态模型的最小可觉差

发布时间：2025年07月01日

`其他` `计算机视觉` `人工智能`

> Just Noticeable Difference for Large Multimodal Models

# 摘要

> 刚刚可察觉差异（JND），即人类视觉系统（HVS）能感知的最小变化，已被研究数十年。近期工作虽将这一研究扩展至机器视觉领域，但在大型多模态模型（LMMs）快速发展的背景下，系统性探索其在多任务和多刺激类型下的感知边界的研究仍显不足。此外，LMMs的感知缺陷未被深入研究，可能导致安全问题和效率低下。本文初步尝试揭示了当前LMMs存在显著视觉盲点。为系统量化这一特性，我们提出新概念{f LMM-JND}及其确定流程。我们深入研究了多个LMM家族，构建了包含21.5k参考图像和489k刺激的VPA-JND数据集，涵盖12种失真类型，助力LMM-JND研究。实验显示，包括GPT-4o和InternVL2.5系列在内的先进LMMs在基本比较查询中表现欠佳，远低于人类视觉水平。我们还发现视觉和语言主干的设计理念间存在显著相关性，这为未来提升LMMs视觉能力提供了指导。本研究凸显了LMM-JND作为独特视角的重要性，其可预测性对安全问题至关重要。代码将在https://github.com/zijianchen98/LMM-JND公开。

> Just noticeable difference (JND), the minimum change that the human visual system (HVS) can perceive, has been studied for decades. Although recent work has extended this line of research into machine vision, there has been a scarcity of studies systematically exploring its perceptual boundaries across multiple tasks and stimulus types, particularly in the current era of rapidly advancing large multimodal models (LMMs), where studying the multifaceted capabilities of models has become a mainstream focus. Moreover, the perceptual defects of LMMs are not investigated thoroughly, resulting in potential security issues and suboptimal response efficiency. In this paper, we take an initial attempt and demonstrate that there exist significant visual blind spots in current LMMs. To systemically quantify this characteristic, we propose a new concept, {\bf LMM-JND}, together with its determination pipeline. Targeting uncovering the behavior commonalities in HVS-aligned visual perception tasks, we delve into several LMM families and construct a large-scale dataset, named VPA-JND, which contains 21.5k reference images with over 489k stimuli across 12 distortion types, to facilitate LMM-JND studies. VPA-JND exposes areas where state-of-the-art LMMs, including GPT-4o and the InternVL2.5 series, struggle with basic comparison queries and fall significantly short of human-level visual performance. We further explore the effects of vision and language backbones and find a notable correlation between their design philosophy that may instruct the future refinement of LMMs for their visual acuity. Together, our research underscores the significance of LMM-JND as a unique perspective for studying LMMs, and predictable LMM-JND is crucial for security concerns. This work will be available at https://github.com/zijianchen98/LMM-JND.

[Arxiv](https://arxiv.org/abs/2507.00490)