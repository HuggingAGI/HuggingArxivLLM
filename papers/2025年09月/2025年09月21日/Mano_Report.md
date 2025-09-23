# Mano报告

发布时间：2025年09月21日

`Agent` `基础理论`

> Mano Report

# 摘要

> 图形用户界面（GUIs）是人机交互的主要载体，但自动化GUI交互仍面临挑战——视觉元素复杂、环境动态多变，还需多步推理。现有基于视觉语言模型（VLMs）的方法往往存在分辨率有限、领域适配性差和顺序决策能力不足等问题。为此，我们提出Mano：一个基于多模态基础模型打造的鲁棒GUI智能体，该模型已在海量网络与计算机系统数据上完成预训练。我们的方案融合了三大核心：用于高保真数据生成的全新模拟环境、三阶段训练流程（监督微调、离线强化学习、在线强化学习），以及负责错误恢复的验证模块。Mano在Mind2Web、OSWorld等多个GUI基准测试中展现了最先进的性能，成功率与操作准确性均取得显著提升。这项研究为强化学习与VLMs的高效融合及GUI智能体的实际部署提供了新的思路，同时凸显了领域专属数据、迭代训练与整体奖励设计的关键价值。

> Graphical user interfaces (GUIs) are the primary medium for human-computer interaction, yet automating GUI interactions remains challenging due to the complexity of visual elements, dynamic environments, and the need for multi-step reasoning. Existing methods based on vision-language models (VLMs) often suffer from limited resolution, domain mismatch, and insufficient sequential decisionmaking capability. To address these issues, we propose Mano, a robust GUI agent built upon a multi-modal foundation model pre-trained on extensive web and computer system data. Our approach integrates a novel simulated environment for high-fidelity data generation, a three-stage training pipeline (supervised fine-tuning, offline reinforcement learning, and online reinforcement learning), and a verification module for error recovery. Mano demonstrates state-of-the-art performance on multiple GUI benchmarks, including Mind2Web and OSWorld, achieving significant improvements in success rate and operational accuracy. Our work provides new insights into the effective integration of reinforcement learning with VLMs for practical GUI agent deployment, highlighting the importance of domain-specific data, iterative training, and holistic reward design.

[Arxiv](https://arxiv.org/abs/2509.17336)