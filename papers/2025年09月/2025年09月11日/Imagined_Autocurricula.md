# 设想的自主课程

发布时间：2025年09月11日

`Agent` `基础理论`

> Imagined Autocurricula

# 摘要

> 训练智能体在具身环境中行动通常需要海量训练数据或精确模拟环境，但现实世界里很多场景两者皆缺。相反，世界模型正崛起为替代方案：它们借助离线、被动收集的数据，能在模拟中生成多样化世界以训练智能体。本研究中，我们利用世界模型构建想象环境，旨在训练出可泛化至新任务变体的鲁棒智能体。此间的核心挑战在于确保智能体学习的生成数据是有用的。为此，我们提出新方法IMAC（想象自动课程，Imagined Autocurricula）——它通过无监督环境设计（UED）在生成世界上自动构建训练课程。在一系列高难度程序化生成环境中，我们验证：仅用窄数据集训练的世界模型，就能让智能体在未见过的保留环境中展现优异迁移性能。这为利用大规模基础世界模型开发通用智能体铺平了道路。

> Training agents to act in embodied environments typically requires vast training data or access to accurate simulation, neither of which exists for many cases in the real world. Instead, world models are emerging as an alternative leveraging offline, passively collected data, they make it possible to generate diverse worlds for training agents in simulation. In this work, we harness world models to generate imagined environments to train robust agents capable of generalizing to novel task variations. One of the challenges in doing this is ensuring the agent trains on useful generated data. We thus propose a novel approach, IMAC (Imagined Autocurricula), leveraging Unsupervised Environment Design (UED), which induces an automatic curriculum over generated worlds. In a series of challenging, procedurally generated environments, we show it is possible to achieve strong transfer performance on held-out environments, having trained only inside a world model learned from a narrower dataset. We believe this opens the path to utilizing larger-scale, foundation world models for generally capable agents.

[Arxiv](https://arxiv.org/abs/2509.13341)