# EmbodiedOneVision：交织式视觉-文本-动作预训练面向通用机器人控制

发布时间：2025年08月28日

`Agent` `工业与制造`

> EmbodiedOneVision: Interleaved Vision-Text-Action Pretraining for General Robot Control

# 摘要

> 在开放世界中无缝实现多模态推理与物理交互，是通用具身智能系统追求的核心目标。近年来，在大规模机器人与视觉文本数据上联合训练的视觉-语言-动作（VLA）模型，已在通用机器人控制领域取得显著进展。但在交错推理与交互的灵活性上，这些模型仍与人类水平存在差距。为此，本研究提出EO-Robotics，该框架包含EO-1模型与EO-Data1.5M数据集。EO-1作为统一的具身基础模型，通过交错视觉-文本-动作预训练，在多模态具身推理与机器人控制任务中表现卓越。EO-1的研发依托两大核心支柱：（i）统一架构，能无差别处理图像、文本、视频、动作等多模态输入；（ii）大规模高质量多模态具身推理数据集EO-Data1.5M，包含150余万样本，专注于交错视觉-文本-动作理解。EO-1在EO-Data1.5M上通过自回归解码与流匹配去噪的协同训练，实现了机器人动作的无缝生成与多模态具身推理。大量实验表明，交错视觉-文本-动作学习在开放世界理解与泛化中成效显著，这一结论已通过多种具身形态下的长时程灵巧操作任务验证。本文详细阐述了EO-1的架构设计、EO-Data1.5M的数据构建策略及训练方法，为先进具身基础模型的研发提供了宝贵启示。

> The human ability to seamlessly perform multimodal reasoning and physical interaction in the open world is a core goal for general-purpose embodied intelligent systems. Recent vision-language-action (VLA) models, which are co-trained on large-scale robot and visual-text data, have demonstrated notable progress in general robot control. However, they still fail to achieve human-level flexibility in interleaved reasoning and interaction. In this work, introduce EO-Robotics, consists of EO-1 model and EO-Data1.5M dataset. EO-1 is a unified embodied foundation model that achieves superior performance in multimodal embodied reasoning and robot control through interleaved vision-text-action pre-training. The development of EO-1 is based on two key pillars: (i) a unified architecture that processes multimodal inputs indiscriminately (image, text, video, and action), and (ii) a massive, high-quality multimodal embodied reasoning dataset, EO-Data1.5M, which contains over 1.5 million samples with emphasis on interleaved vision-text-action comprehension. EO-1 is trained through synergies between auto-regressive decoding and flow matching denoising on EO-Data1.5M, enabling seamless robot action generation and multimodal embodied reasoning. Extensive experiments demonstrate the effectiveness of interleaved vision-text-action learning for open-world understanding and generalization, validated through a variety of long-horizon, dexterous manipulation tasks across multiple embodiments. This paper details the architecture of EO-1, the data construction strategy of EO-Data1.5M, and the training methodology, offering valuable insights for developing advanced embodied foundation models.

[Arxiv](https://arxiv.org/abs/2508.21112)