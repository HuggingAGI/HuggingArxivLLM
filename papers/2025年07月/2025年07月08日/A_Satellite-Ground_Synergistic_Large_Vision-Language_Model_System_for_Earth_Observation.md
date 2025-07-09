# 星地协同的大规模视觉-语言模型系统，专为地球观测而设计

发布时间：2025年07月08日

`其他` `地球观测`

> A Satellite-Ground Synergistic Large Vision-Language Model System for Earth Observation

# 摘要

> 大型视觉语言模型（LVLMs）在低地球轨道（LEO）卫星地球观测图像分析中展现了强大的能力，但卫星快速移动、接触窗口短暂及图像规模庞大给数据下载带来了挑战。为实现近实时地球观测应用（如灾害和极端天气监测），我们提出在LEO卫星网络中部署LVLM，并设计了SpaceVerse，一个高效的卫星-地面协同推理系统。SpaceVerse通过将轻量级LVLM部署在卫星处理简单任务，常规LVLM在地面站处理复杂任务，并结合渐进式置信网络和多尺度预处理框架，有效识别在轨推理数据并减少传输冗余。实验结果显示，SpaceVerse在真实LEO卫星系统中实现了31.2%的精度提升和51.2%的延迟降低。

> Recently, large vision-language models (LVLMs) unleash powerful analysis capabilities for low Earth orbit (LEO) satellite Earth observation images in the data center. However, fast satellite motion, brief satellite-ground station (GS) contact windows, and large size of the images pose a data download challenge. To enable near real-time Earth observation applications (e.g., disaster and extreme weather monitoring), we should explore how to deploy LVLM in LEO satellite networks, and design SpaceVerse, an efficient satellite-ground synergistic LVLM inference system. To this end, firstly, we deploy compact LVLMs on satellites for lightweight tasks, whereas regular LVLMs operate on GSs to handle computationally intensive tasks. Then, we propose a computing and communication co-design framework comprised of a progressive confidence network and an attention-based multi-scale preprocessing, used to identify on-satellite inferring data, and reduce data redundancy before satellite-GS transmission, separately. We implement and evaluate SpaceVerse on real-world LEO satellite constellations and datasets, achieving a 31.2% average gain in accuracy and a 51.2% reduction in latency compared to state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2507.05731)