# SegChange-R1：基于大型语言模型的增强推理在遥感变化检测中的应用

发布时间：2025年06月22日

`LLM应用` `城市规划`

> SegChange-R1:Augmented Reasoning for Remote Sensing Change Detection via Large Language Models

# 摘要

> 遥感变化检测在城市规划、地形分析和环境监测等领域广泛应用，主要通过分析同一区域不同时期的特征变化（如建筑物变化）来实现。本文提出了一种基于大型语言模型（LLM）增强推理的方法SegChange-R1，通过整合文本描述信息提升检测能力，引导模型更关注变化区域，从而加速收敛。我们还设计了一个基于线性注意力的空间变换模块BEV，通过统一不同时间视角的特征到BEV空间，解决了变化检测中的模态对齐问题。此外，我们构建了首个基于无人机视角的建筑物变化检测数据集DVCD，并在四个常用数据集上的实验表明，SegChange-R1显著优于现有方法。代码和预训练模型可在GitHub上获取：https://github.com/Yu-Zhouz/SegChange-R1。

> Remote sensing change detection is widely used in a variety of fields such as urban planning, terrain and geomorphology analysis, and environmental monitoring, mainly by analyzing the significant change differences of features (e.g., building changes) in the same spatial region at different time phases. In this paper, we propose a large language model (LLM) augmented inference approach (SegChange-R1), which enhances the detection capability by integrating textual descriptive information and aims at guiding the model to segment the more interested change regions, thus accelerating the convergence speed. Moreover, we design a spatial transformation module (BEV) based on linear attention, which solves the problem of modal misalignment in change detection by unifying features from different temporal perspectives onto the BEV space. In addition, we construct the first dataset for building change detection from UAV viewpoints (DVCD ), and our experiments on four widely-used change detection datasets show a significant improvement over existing methods. The code and pre-trained models are available in https://github.com/Yu-Zhouz/SegChange-R1.

[Arxiv](https://arxiv.org/abs/2506.17944)