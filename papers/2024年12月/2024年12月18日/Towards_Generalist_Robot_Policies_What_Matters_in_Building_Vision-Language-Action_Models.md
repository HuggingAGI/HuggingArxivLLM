# 迈向通用型机器人策略：构建视觉 - 语言 - 动作模型的关键所在

发布时间：2024年12月18日

`LLM应用` `计算机视觉` `多模态学习`

> Towards Generalist Robot Policies: What Matters in Building Vision-Language-Action Models

# 摘要

> 基础的视觉语言模型（VLMs）在多模态表示学习、理解与推理方面展现出强大的实力。将动作组件注入 VLMs 中，就能自然形成视觉语言动作模型（VLAs），而且性能出色。现有工作已在多个场景和任务里证实了 VLAs 的有效性和泛化能力。然而，从 VLMs 到 VLAs 的转变并非轻而易举，因为现有的 VLAs 在骨干架构、动作预测方式、数据分布和训练策略上存在差异，致使对 VLAs 设计选择的系统理解存在缺失。在本研究中，我们揭示了对 VLA 性能有显著影响的关键因素，并着重回答了三个核心的设计选择问题：选用何种骨干架构、如何构建 VLA 架构以及何时添加跨实体数据。所得结果让我们坚信并解释了为何需要 VLA，还开发出了新的 VLA 家族——RoboVLMs，其所需人工设计极少，在三个模拟任务和真实世界实验中达到了新的顶尖性能。通过我们广泛的实验，涵盖超过 8 个 VLM 骨干架构、4 种策略架构以及 600 多个不同的设计实验，为未来的 VLA 设计提供了详尽的指南。除了研究本身，高度灵活的 RoboVLMs 框架也已公开，它支持新 VLMs 的轻松集成以及各种设计选择的自由组合，以助力未来的研究。我们在 robovlms.github.io 开源了所有细节，包括代码、模型、数据集和工具包，还有详细的训练和评估方法。

> Foundation Vision Language Models (VLMs) exhibit strong capabilities in multi-modal representation learning, comprehension, and reasoning. By injecting action components into the VLMs, Vision-Language-Action Models (VLAs) can be naturally formed and also show promising performance. Existing work has demonstrated the effectiveness and generalization of VLAs in multiple scenarios and tasks. Nevertheless, the transfer from VLMs to VLAs is not trivial since existing VLAs differ in their backbones, action-prediction formulations, data distributions, and training recipes. This leads to a missing piece for a systematic understanding of the design choices of VLAs. In this work, we disclose the key factors that significantly influence the performance of VLA and focus on answering three essential design choices: which backbone to select, how to formulate the VLA architectures, and when to add cross-embodiment data. The obtained results convince us firmly to explain why we need VLA and develop a new family of VLAs, RoboVLMs, which require very few manual designs and achieve a new state-of-the-art performance in three simulation tasks and real-world experiments. Through our extensive experiments, which include over 8 VLM backbones, 4 policy architectures, and over 600 distinct designed experiments, we provide a detailed guidebook for the future design of VLAs. In addition to the study, the highly flexible RoboVLMs framework, which supports easy integrations of new VLMs and free combinations of various design choices, is made public to facilitate future research. We open-source all details, including codes, models, datasets, and toolkits, along with detailed training and evaluation recipes at: robovlms.github.io.

[Arxiv](https://arxiv.org/abs/2412.14058)