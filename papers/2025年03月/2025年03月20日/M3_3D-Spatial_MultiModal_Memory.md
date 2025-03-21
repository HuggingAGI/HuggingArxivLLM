# **M3: 三维空间多模态记忆**

发布时间：2025年03月20日

`其他` `计算机视觉` `机器人学`

> M3: 3D-Spatial MultiModal Memory

# 摘要

> 我们提出了一种名为3D空间多模态记忆（M3）的多模态记忆系统，旨在通过视频源保留中型静态场景的视觉感知信息。通过将3D高斯散射技术与基础模型相结合，M3构建了一个多模态记忆系统，能够渲染不同粒度的特征表示，涵盖广泛的知识范围。

在研究过程中，我们发现以往在特征散射方面存在两个主要问题：（1）为每个高斯基元存储高维特征的计算约束；（2）蒸馏特征与基础模型特征之间的对齐问题或信息丢失。针对这些问题，我们提出了M3，其关键组件包括主场景组件和高斯记忆注意力，从而实现高效训练和推理。

为了验证M3的效果，我们进行了全面的定量评估，涵盖特征相似性和下游任务，并进行了定性可视化，以突出高斯记忆注意力的像素轨迹。我们的方法涵盖了多种基础模型，包括视觉语言模型（VLMs）、感知模型以及大型多模态和语言模型（LMMs/LLMs）。

此外，为了展示其在现实世界中的应用潜力，我们将M3的功能场部署在四足机器人上的室内场景中。值得注意的是，我们声称M3是首个解决三维特征蒸馏核心压缩挑战的工作。


> We present 3D Spatial MultiModal Memory (M3), a multimodal memory system designed to retain information about medium-sized static scenes through video sources for visual perception. By integrating 3D Gaussian Splatting techniques with foundation models, M3 builds a multimodal memory capable of rendering feature representations across granularities, encompassing a wide range of knowledge. In our exploration, we identify two key challenges in previous works on feature splatting: (1) computational constraints in storing high-dimensional features for each Gaussian primitive, and (2) misalignment or information loss between distilled features and foundation model features. To address these challenges, we propose M3 with key components of principal scene components and Gaussian memory attention, enabling efficient training and inference. To validate M3, we conduct comprehensive quantitative evaluations of feature similarity and downstream tasks, as well as qualitative visualizations to highlight the pixel trace of Gaussian memory attention. Our approach encompasses a diverse range of foundation models, including vision-language models (VLMs), perception models, and large multimodal and language models (LMMs/LLMs). Furthermore, to demonstrate real-world applicability, we deploy M3's feature field in indoor scenes on a quadruped robot. Notably, we claim that M3 is the first work to address the core compression challenges in 3D feature distillation.

[Arxiv](https://arxiv.org/abs/2503.16413)