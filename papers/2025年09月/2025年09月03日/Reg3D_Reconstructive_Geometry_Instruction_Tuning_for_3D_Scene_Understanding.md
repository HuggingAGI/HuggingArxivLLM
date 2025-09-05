# Reg3D：面向3D场景理解的几何重建指令微调

发布时间：2025年09月03日

`其他` `工业与制造`

> Reg3D: Reconstructive Geometry Instruction Tuning for 3D Scene Understanding

# 摘要

> 大型多模态模型（LMMs）的快速发展推动了2D视觉理解的显著进步，然而将这些能力拓展至3D场景理解仍面临重大挑战。现有方法多依赖纯文本监督，难以提供学习鲁棒3D空间表示所需的几何约束。为此，本文提出Reg3D——一种新颖的重建几何指令调优框架，通过将几何感知监督直接融入训练过程，解决了这一局限。我们的核心思路是：有效的3D理解需重建底层几何结构，而非仅对其进行描述。与现有仅在输入层注入3D信息的方法不同，Reg3D采用双监督范式，将3D几何信息同时作为输入和显式学习目标。具体而言，我们在双编码器架构中设计了对象级与帧级互补重建任务，通过强化几何一致性促进空间推理能力的培养。在ScanQA、Scan2Cap、ScanRefer和SQA3D数据集上的大量实验表明，Reg3D实现了显著性能提升，为具备空间感知能力的多模态模型开辟了新的训练范式。

> The rapid development of Large Multimodal Models (LMMs) has led to remarkable progress in 2D visual understanding; however, extending these capabilities to 3D scene understanding remains a significant challenge. Existing approaches predominantly rely on text-only supervision, which fails to provide the geometric constraints required for learning robust 3D spatial representations. In this paper, we introduce Reg3D, a novel Reconstructive Geometry Instruction Tuning framework that addresses this limitation by incorporating geometry-aware supervision directly into the training process. Our key insight is that effective 3D understanding necessitates reconstructing underlying geometric structures rather than merely describing them. Unlike existing methods that inject 3D information solely at the input level, Reg3D adopts a dual-supervision paradigm that leverages 3D geometric information both as input and as explicit learning targets. Specifically, we design complementary object-level and frame-level reconstruction tasks within a dual-encoder architecture, enforcing geometric consistency to encourage the development of spatial reasoning capabilities. Extensive experiments on ScanQA, Scan2Cap, ScanRefer, and SQA3D demonstrate that Reg3D delivers substantial performance improvements, establishing a new training paradigm for spatially aware multimodal models.

[Arxiv](https://arxiv.org/abs/2509.03635)