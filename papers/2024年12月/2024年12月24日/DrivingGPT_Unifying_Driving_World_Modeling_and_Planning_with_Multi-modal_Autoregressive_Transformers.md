# DrivingGPT：借助多模态自回归 Transformer 实现驾驶世界建模与规划的统一

发布时间：2024年12月24日

`LLM应用` `物理智能`

> DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers

# 摘要

> 基于世界模型的搜索与规划，被公认为是通往人类水平物理智能的一条充满希望的道路。然而，当下的驾驶世界模型主要依赖视频扩散模型，此类模型擅长视觉生成，却缺乏整合动作等其他模态的灵活性。相较而言，自回归变压器在多模态数据建模方面展现出了非凡能力。我们的工作旨在将驾驶模型模拟和轨迹规划统一成一个单一的序列建模问题。我们引入了一种基于交错图像和动作标记的多模态驾驶语言，并开发了 DrivingGPT，通过标准的下一个标记预测来学习联合世界建模与规划。我们的 DrivingGPT 在动作条件视频生成和端到端规划中均表现出色，在大规模的 nuPlan 和 NAVSIM 基准测试中超越了强大的基线。

> World model-based searching and planning are widely recognized as a promising path toward human-level physical intelligence. However, current driving world models primarily rely on video diffusion models, which specialize in visual generation but lack the flexibility to incorporate other modalities like action. In contrast, autoregressive transformers have demonstrated exceptional capability in modeling multimodal data. Our work aims to unify both driving model simulation and trajectory planning into a single sequence modeling problem. We introduce a multimodal driving language based on interleaved image and action tokens, and develop DrivingGPT to learn joint world modeling and planning through standard next-token prediction. Our DrivingGPT demonstrates strong performance in both action-conditioned video generation and end-to-end planning, outperforming strong baselines on large-scale nuPlan and NAVSIM benchmarks.

[Arxiv](https://arxiv.org/abs/2412.18607)