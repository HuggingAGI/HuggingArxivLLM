# 宇宙推理1：从物理常识到具身推理

发布时间：2025年03月18日

`LLM应用` `物理AI` `机器人学`

> Cosmos-Reason1: From Physical Common Sense To Embodied Reasoning

# 摘要

> 物理AI系统需要在现实世界中实现感知、理解和复杂动作的执行。本文介绍了我们的Cosmos-Reason1模型，它能够通过长链式推理过程理解物理世界，并生成自然语言形式的具身化决策（如下一步动作）。我们首先界定了物理AI推理的三大核心能力：物理常识与具身化推理。在物理常识的表达上，我们采用了层次化知识图谱，涵盖空间、时间和物理的基本要素；而在具身化推理方面，我们构建了跨形态通用的二维知识图谱。基于这些能力，我们开发了多模态大型语言模型Cosmos-Reason1系列，包括80亿和560亿参数两个版本。我们的训练流程分为四个阶段：视觉预训练、通用监督微调、物理AI专项微调以及强化学习优化。为全面评估模型性能，我们根据知识图谱构建了专用评测基准。实验结果表明，物理AI专项微调和强化学习显著提升了模型性能。为了推动物理AI领域的发展，我们将在NVIDIA开源许可下开放代码和预训练模型，项目地址为https://github.com/nvidia-cosmos/cosmos-reason1。


> Physical AI systems need to perceive, understand, and perform complex actions in the physical world. In this paper, we present the Cosmos-Reason1 models that can understand the physical world and generate appropriate embodied decisions (e.g., next step action) in natural language through long chain-of-thought reasoning processes. We begin by defining key capabilities for Physical AI reasoning, with a focus on physical common sense and embodied reasoning. To represent physical common sense, we use a hierarchical ontology that captures fundamental knowledge about space, time, and physics. For embodied reasoning, we rely on a two-dimensional ontology that generalizes across different physical embodiments. Building on these capabilities, we develop two multimodal large language models, Cosmos-Reason1-8B and Cosmos-Reason1-56B. We curate data and train our models in four stages: vision pre-training, general supervised fine-tuning (SFT), Physical AI SFT, and Physical AI reinforcement learning (RL) as the post-training. To evaluate our models, we build comprehensive benchmarks for physical common sense and embodied reasoning according to our ontologies. Evaluation results show that Physical AI SFT and reinforcement learning bring significant improvements. To facilitate the development of Physical AI, we will make our code and pre-trained models available under the NVIDIA Open Model License at https://github.com/nvidia-cosmos/cosmos-reason1.

[Arxiv](https://arxiv.org/abs/2503.15558)