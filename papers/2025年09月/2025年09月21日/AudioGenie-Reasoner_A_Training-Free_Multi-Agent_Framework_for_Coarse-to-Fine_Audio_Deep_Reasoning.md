# AudioGenie-Reasoner：无需训练的多智能体框架，面向从粗到细的音频深度推理

发布时间：2025年09月21日

`Agent` `基础理论`

> AudioGenie-Reasoner: A Training-Free Multi-Agent Framework for Coarse-to-Fine Audio Deep Reasoning

# 摘要

> 音频深度推理是一项极具挑战性的任务，需要专家级感知能力、多步骤逻辑推理与上下文知识的深度整合。然而，现有模型因缺乏含显式推理链的训练数据，且缺少主动探索与迭代优化机制，导致音频感知与推理能力之间存在显著鸿沟。为应对这些挑战，我们提出了AudioGenie-Reasoner（AGR）——首个统一的免训练多智能体系统，可在动态演化的文本证据链上协同感知与推理。我们的核心创新在于一种范式转变：从全新视角将音频深度推理转化为复杂文本理解任务，进而充分释放大型语言模型的潜力。具体而言，AGR的设计借鉴了人类“由粗到细”的认知过程：首先将输入音频转换为粗略文本文档，随后构建新颖的主动迭代文档优化循环，结合工具增强路径与专用智能体，以“由粗到细”的方式持续搜索缺失信息、扩充证据链，直至收集到足够的问题相关信息以进行最终预测。实验结果显示，在多个基准测试中，AGR相较于现有开源音频深度推理模型，性能达到了最先进水平（SOTA）。相关代码将公开发布。

> Audio deep reasoning is a challenging task that requires expert-level perception, multi-step logical inference, and the integration of contextual knowledge. However, existing models suffer from a gap between audio perception and reasoning abilities due to the lack of training data with explicit reasoning chains and the absence of mechanisms for active exploration and iterative refinement. To address these challenges, we propose AudioGenie-Reasoner (AGR), the first unified training-free multi-agent system that coordinates perception and reasoning over an evolving chain of textual evidence. Our key idea is a paradigm shift that transforms audio deep reasoning into complex text understanding task from a new perspective, thereby unlocking the full potential of large language models. Specifically, the design of AGR mimics the human coarse-to-fine cognitive process. It first transforms the input audio into a coarse text-based document. Then, we design a novel proactive iterative document refinement loop, featuring tool-augmented routes and specialized agents, to continuously search for missing information and augment the evidence chain in a coarse-to-fine manner until sufficient question-related information is gathered for making final predictions. Experimental results show that AGR achieves state-of-the-art (SOTA) performance over existing open-source audio deep reasoning models across various benchmarks. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2509.16971)