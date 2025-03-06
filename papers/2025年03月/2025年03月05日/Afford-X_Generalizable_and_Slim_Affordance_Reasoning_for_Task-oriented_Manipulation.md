# Afford-X：面向任务导向操作的通用精简可及性推理机制

发布时间：2025年03月05日

`LLM应用` `机器人` `人工智能`

> Afford-X: Generalizable and Slim Affordance Reasoning for Task-oriented Manipulation

# 摘要

> 物体可及性推理，即根据物体的物理特性推断其功能的能力，对于人类和AI在任务导向型活动中的规划和执行至关重要。这一能力不仅依赖于简单的物体识别，还需要基于对物体物理特性和功能的常识性理解。然而，目前基于感知的可及性推理计算模型缺乏泛化能力，难以在新场景中应用。同时，尽管具有新兴推理能力的大型语言模型（LLMs）在理论上具有潜力，但其在本地设备上进行任务导向型操作的部署仍面临挑战。

为解决这些问题，我们推出了LVIS-Aff数据集，包含1,496个任务和119,000张图像，旨在提升基于感知的可及性推理的泛化能力。基于该数据集，我们开发了Afford-X，一个端到端可训练的可及性推理模型。该模型通过集成动词注意力和双融合模块，显著提升了多模态理解能力。在性能方面，Afford-X较非LLM方法的最佳报告结果提升了12.1%，较我们之前的会议论文也提高了1.2%。此外，该模型仅需1.87亿参数，推理速度几乎是GPT-4V API的50倍。

我们的研究表明，高效、通用的可及性推理模型在本地设备上实现任务导向型操作具有巨大潜力。通过在各种任务和环境中的实验，Afford-X展示了其在机器人任务导向型操作中的有效性，不仅体现了其高效性，也为推动机器人和AI系统在现实世界中的广泛应用奠定了基础。

> Object affordance reasoning, the ability to infer object functionalities based on physical properties, is fundamental for task-oriented planning and activities in both humans and Artificial Intelligence (AI). This capability, required for planning and executing daily activities in a task-oriented manner, relies on commonsense knowledge of object physics and functionalities, extending beyond simple object recognition. Current computational models for affordance reasoning from perception lack generalizability, limiting their applicability in novel scenarios. Meanwhile, comprehensive Large Language Models (LLMs) with emerging reasoning capabilities are challenging to deploy on local devices for task-oriented manipulations. Here, we introduce LVIS-Aff, a large-scale dataset comprising 1,496 tasks and 119k images, designed to enhance the generalizability of affordance reasoning from perception. Utilizing this dataset, we develop Afford-X, an end-to-end trainable affordance reasoning model that incorporates Verb Attention and Bi-Fusion modules to improve multi-modal understanding. This model achieves up to a 12.1% performance improvement over the best-reported results from non-LLM methods, while also demonstrating a 1.2% enhancement compared to our previous conference paper. Additionally, it maintains a compact 187M parameter size and infers nearly 50 times faster than the GPT-4V API. Our work demonstrates the potential for efficient, generalizable affordance reasoning models that can be deployed on local devices for task-oriented manipulations. We showcase Afford-X's effectiveness in enabling task-oriented manipulations for robots across various tasks and environments, underscoring its efficiency and broad implications for advancing robotics and AI systems in real-world applications.

[Arxiv](https://arxiv.org/abs/2503.03556)