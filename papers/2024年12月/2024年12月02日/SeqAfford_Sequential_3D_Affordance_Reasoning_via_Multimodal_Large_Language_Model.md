# SeqAfford：借助多模态大型语言模型实现顺序 3D 可供性推理

发布时间：2024年12月02日

`LLM应用` `3D 技术` `具身操作`

> SeqAfford: Sequential 3D Affordance Reasoning via Multimodal Large Language Model

# 摘要

> 3D 可供性分割旨在将人类指令与 3D 物体的可触摸区域相连接，以实现具身操作。现有的工作通常遵循单物体、单可供性的范式，即每种可供性类型或明确指令都严格对应特定的可供性区域，无法处理长期任务。这种范式难以主动推断复杂的用户意图，而这些意图往往意味着连续的可供性。在本文中，我们引入了顺序 3D 可供性推理任务，通过对繁杂的用户意图进行推理，再将其分解为一系列分割图，从而拓展了传统范式。为此，我们构建了首个基于指令的可供性分割基准，涵盖了对单个和连续可供性的推理，包含 18 万组指令 - 点云对。基于该基准，我们提出了模型 SeqAfford，以解锁具有额外可供性分割能力的 3D 多模态大型语言模型，确保在一个紧密的框架中结合世界知识和细粒度的可供性基础进行推理。我们还进一步引入了一个多粒度语言 - 点集成模块，以实现 3D 密集预测。大量的实验评估显示，我们的模型优于已有的成熟方法，并在具有顺序推理能力的开放世界中展现出泛化能力。

> 3D affordance segmentation aims to link human instructions to touchable regions of 3D objects for embodied manipulations. Existing efforts typically adhere to single-object, single-affordance paradigms, where each affordance type or explicit instruction strictly corresponds to a specific affordance region and are unable to handle long-horizon tasks. Such a paradigm cannot actively reason about complex user intentions that often imply sequential affordances. In this paper, we introduce the Sequential 3D Affordance Reasoning task, which extends the traditional paradigm by reasoning from cumbersome user intentions and then decomposing them into a series of segmentation maps. Toward this, we construct the first instruction-based affordance segmentation benchmark that includes reasoning over both single and sequential affordances, comprising 180K instruction-point cloud pairs. Based on the benchmark, we propose our model, SeqAfford, to unlock the 3D multi-modal large language model with additional affordance segmentation abilities, which ensures reasoning with world knowledge and fine-grained affordance grounding in a cohesive framework. We further introduce a multi-granular language-point integration module to endow 3D dense prediction. Extensive experimental evaluations show that our model excels over well-established methods and exhibits open-world generalization with sequential reasoning abilities.

[Arxiv](https://arxiv.org/abs/2412.01550)