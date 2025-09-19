# 机器人控制栈：面向大规模机器人学习的精简生态系统

发布时间：2025年09月18日

`其他` `工业与制造`

> Robot Control Stack: A Lean Ecosystem for Robot Learning at Scale

# 摘要

> 视觉-语言-动作模型（VLAs）为机器人学习带来了重大变革。这类模型不再依赖专家策略中的专用架构和任务定制组件，而是采用大规模数据收集与特定场景微调的方式。在这种以机器学习为核心、聚焦模型与可扩展训练的工作流程中，传统机器人软件框架逐渐成为瓶颈，而机器人仿真对虚实实验的双向过渡支持也十分有限。为此，本研究提出了机器人控制栈（RCS）——一个从头构建的精简生态系统，专为支持基于大规模通用策略的机器人学习研究而设计，以填补这一空白。RCS的核心是模块化且易于扩展的分层架构，它为仿真与实体机器人提供统一接口，从而助力虚实迁移。尽管RCS占用空间小、依赖项少，却具备完整功能，可同时支持真实世界实验与大规模仿真训练。我们的贡献主要有两点：一是详细介绍了RCS的架构及其设计原则；二是在VLA和强化学习（RL）策略的开发全周期中，对其可用性和性能进行了评估。此外，我们的实验还在多台机器人上对Octo、OpenVLA和Pi Zero进行了全面评估，并揭示了仿真数据提升真实世界策略性能的机制。相关代码、数据集、权重及视频已开源，获取地址：https://robotcontrolstack.github.io/

> Vision-Language-Action models (VLAs) mark a major shift in robot learning. They replace specialized architectures and task-tailored components of expert policies with large-scale data collection and setup-specific fine-tuning. In this machine learning-focused workflow that is centered around models and scalable training, traditional robotics software frameworks become a bottleneck, while robot simulations offer only limited support for transitioning from and to real-world experiments. In this work, we close this gap by introducing Robot Control Stack (RCS), a lean ecosystem designed from the ground up to support research in robot learning with large-scale generalist policies. At its core, RCS features a modular and easily extensible layered architecture with a unified interface for simulated and physical robots, facilitating sim-to-real transfer. Despite its minimal footprint and dependencies, it offers a complete feature set, enabling both real-world experiments and large-scale training in simulation. Our contribution is twofold: First, we introduce the architecture of RCS and explain its design principles. Second, we evaluate its usability and performance along the development cycle of VLA and RL policies. Our experiments also provide an extensive evaluation of Octo, OpenVLA, and Pi Zero on multiple robots and shed light on how simulation data can improve real-world policy performance. Our code, datasets, weights, and videos are available at: https://robotcontrolstack.github.io/

[Arxiv](https://arxiv.org/abs/2509.14932)