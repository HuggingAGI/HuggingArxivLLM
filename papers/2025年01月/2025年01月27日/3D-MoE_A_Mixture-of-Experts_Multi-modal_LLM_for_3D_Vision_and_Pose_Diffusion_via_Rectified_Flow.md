# 3D-MoE: 一种多模态专家混合模型，通过修正流实现3D视觉与姿态扩散

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于3D视觉和空间推理任务，特别是通过将现有LLMs转换为专家混合（MoE）模型来提升3D问答和任务规划任务的性能。这属于LLM在实际应用中的扩展和改进，因此归类为LLM应用。` `3D视觉` `具身智能`

> 3D-MoE: A Mixture-of-Experts Multi-modal LLM for 3D Vision and Pose Diffusion via Rectified Flow

# 摘要

> 3D视觉和空间推理一直被认为比基于2D图像的传统视觉推理更能准确感知三维世界。然而，由于高质量3D数据难以获取，这一领域的研究直到最近才取得进展。随着大型语言模型（LLMs）的崛起，过去几年中已开发出多模态LLMs用于3D视觉。但这些模型大多聚焦于3D数据的视觉编码器。本文提出将现有密集激活的LLMs转换为专家混合（MoE）模型，该模型已被证明在多模态数据处理中表现优异。我们不仅利用这些模型的指令跟随能力，还通过引入扩散头Pose-DiT实现了具身任务规划，该扩散头采用了一种创新的校正流扩散调度器。实验表明，我们的3D-MoE框架在激活参数较少的情况下，显著提升了3D问答和任务规划任务的性能。

> 3D vision and spatial reasoning have long been recognized as preferable for accurately perceiving our three-dimensional world, especially when compared with traditional visual reasoning based on 2D images. Due to the difficulties in collecting high-quality 3D data, research in this area has only recently gained momentum. With the advent of powerful large language models (LLMs), multi-modal LLMs for 3D vision have been developed over the past few years. However, most of these models focus primarily on the vision encoder for 3D data. In this paper, we propose converting existing densely activated LLMs into mixture-of-experts (MoE) models, which have proven effective for multi-modal data processing. In addition to leveraging these models' instruction-following capabilities, we further enable embodied task planning by attaching a diffusion head, Pose-DiT, that employs a novel rectified flow diffusion scheduler. Experimental results on 3D question answering and task-planning tasks demonstrate that our 3D-MoE framework achieves improved performance with fewer activated parameters.

[Arxiv](https://arxiv.org/abs/2501.16698)