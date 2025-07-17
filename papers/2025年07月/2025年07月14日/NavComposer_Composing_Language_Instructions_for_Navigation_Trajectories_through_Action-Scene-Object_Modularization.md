# NavComposer：通过动作-场景-物体模块化生成语言指令实现导航轨迹规划

发布时间：2025年07月14日

`Agent` `导航指令生成`

> NavComposer: Composing Language Instructions for Navigation Trajectories through Action-Scene-Object Modularization

# 摘要

> 语言引导导航是具身人工智能的核心，使智能体能够理解语言指令并在复杂环境中导航。然而，专家提供的指令数量有限，而合成的注释通常质量不高，难以满足大规模研究的需求。为了解决这一问题，我们提出了一种全新的框架 NavComposer，用于自动生成高质量的导航指令。NavComposer 明确分解动作、场景和物体等语义实体，并将它们重新组合成自然语言指令。其模块化架构支持灵活地集成最先进技术，而语义实体的显式使用提升了指令的丰富性和准确性。此外，NavComposer 以数据不可知的方式运行，支持适应多种导航轨迹，无需特定领域训练。作为补充，我们推出了 NavInstrCritic，一个全面的无注释评估系统，从对比匹配、语义一致性和语言多样性三个维度评估导航指令。NavInstrCritic 提供了对指令质量的全面评估，弥补了传统依赖专家注释指标的不足。通过将指令生成和评估与特定导航智能体解耦，我们的方法使研究更具扩展性和通用性。广泛的实验结果直接且有力地证明了我们方法的有效性。

> Language-guided navigation is a cornerstone of embodied AI, enabling agents to interpret language instructions and navigate complex environments. However, expert-provided instructions are limited in quantity, while synthesized annotations often lack quality, making them insufficient for large-scale research. To address this, we propose NavComposer, a novel framework for automatically generating high-quality navigation instructions. NavComposer explicitly decomposes semantic entities such as actions, scenes, and objects, and recomposes them into natural language instructions. Its modular architecture allows flexible integration of state-of-the-art techniques, while the explicit use of semantic entities enhances both the richness and accuracy of instructions. Moreover, it operates in a data-agnostic manner, supporting adaptation to diverse navigation trajectories without domain-specific training. Complementing NavComposer, we introduce NavInstrCritic, a comprehensive annotation-free evaluation system that assesses navigation instructions on three dimensions: contrastive matching, semantic consistency, and linguistic diversity. NavInstrCritic provides a holistic evaluation of instruction quality, addressing limitations of traditional metrics that rely heavily on expert annotations. By decoupling instruction generation and evaluation from specific navigation agents, our method enables more scalable and generalizable research. Extensive experiments provide direct and practical evidence for the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2507.10894)