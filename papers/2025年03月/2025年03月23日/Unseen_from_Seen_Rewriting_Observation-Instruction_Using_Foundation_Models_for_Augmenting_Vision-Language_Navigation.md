# # 从已知推未知：利用基础模型重写观察指令提升视觉语言导航能力

发布时间：2025年03月23日

`Agent

理由：论文主要探讨了视觉语言导航（VLN）领域中智能体的数据增强方法，旨在提升其泛化能力。虽然涉及大型语言模型（LLMs），但其核心在于智能体的导航和数据生成，因此归类于Agent。` `视觉语言导航` `机器人`

> Unseen from Seen: Rewriting Observation-Instruction Using Foundation Models for Augmenting Vision-Language Navigation

# 摘要

> 数据稀缺性一直是视觉语言导航 (VLN) 领域的长期难题，严重制约了智能体在新环境中的泛化能力。传统方法主要依赖仿真器数据或网络收集的图像/视频来提升泛化，但前者多样性不足，后者需要大量人工去噪。本文提出了一种面向 VLN 的重写驱动增强范式 (RAM)，通过重写人工标注数据直接生成新观测-指令对。我们的重写机制无需仿真器，且节省人力，显著提升泛化能力。具体来说，我们首先结合视觉语言模型 (VLMs) 和大型语言模型 (LLMs) 提出增强型观测重写方法，生成多样化物体和空间布局的观测合成。其次，我们提出观测对比指令重写方法，通过 LLMs 推理观测差异生成对齐指令。此外，我们开发了一种混合后聚焦的训练策略，并采用随机裁剪方案，在提升数据多样性的同时抑制噪声。实验结果表明，我们的方法在离散环境（R2R、REVERIE、R4R）和连续环境（R2R-CE）中均表现出色，泛化能力尤为突出。代码已开源，地址为 https://github.com/SaDil13/VLN-RAM。

> Data scarcity is a long-standing challenge in the Vision-Language Navigation (VLN) field, which extremely hinders the generalization of agents to unseen environments. Previous works primarily rely on additional simulator data or web-collected images/videos to improve the generalization. However, the simulator environments still face limited diversity, and the web-collected data often requires extensive labor to remove the noise. In this paper, we propose a Rewriting-driven AugMentation (RAM) paradigm for VLN, which directly creates the unseen observation-instruction pairs via rewriting human-annotated training data. Benefiting from our rewriting mechanism, new observation-instruction can be obtained in both simulator-free and labor-saving manners to promote generalization. Specifically, we first introduce Object-Enriched Observation Rewriting, where we combine Vision-Language Models (VLMs) and Large Language Models (LLMs) to derive rewritten object-enriched scene descriptions, enabling observation synthesis with diverse objects and spatial layouts via Text-to-Image Generation Models (T2IMs). Then, we propose Observation-Contrast Instruction Rewriting, which generates observation-aligned rewritten instructions by requiring LLMs to reason the difference between original and new observations. We further develop a mixing-then-focusing training strategy with a random observation cropping scheme, effectively enhancing data distribution diversity while suppressing augmentation data noise during training. Experiments on both the discrete environments (R2R, REVERIE, and R4R datasets) and continuous environments (R2R-CE dataset) show the superior performance and impressive generalization ability of our method. Code is available at https://github.com/SaDil13/VLN-RAM.

[Arxiv](https://arxiv.org/abs/2503.18065)