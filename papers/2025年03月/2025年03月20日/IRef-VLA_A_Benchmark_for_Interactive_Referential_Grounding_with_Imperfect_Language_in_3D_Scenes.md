# IRef-VLA：基于不完整语言的三维场景交互式参考定位基准测试

发布时间：2025年03月20日

`Agent

这篇论文专注于多模态机器人操作和室内导航，属于智能体（Agent）的应用领域，因此归类为Agent。` `机器人` `计算机视觉`

> IRef-VLA: A Benchmark for Interactive Referential Grounding with Imperfect Language in 3D Scenes

# 摘要

> 随着大型语言模型、视觉-语言模型等通用基础模型的崛起，基于自然语言输入实现多模态、多任务机器人操作的潜力日益凸显。其中一个典型应用是基于自然语言指令的室内导航。然而，尽管近期取得了一些进展，该问题仍具挑战性，主要源于其对3D空间推理和语义理解的要求。此外，所使用的语言可能不够完善或与场景不完全匹配，进一步增加了任务难度。为应对这一挑战，我们整理了一个基准数据集IRef-VLA，用于研究在3D场景中存在不完美参考的情况下，通过交互式指代视觉和语言引导动作。IRef-VLA是目前规模最大的面向指代定位任务的现实世界数据集，包含来自现有数据集的11.5K多个扫描3D房间、7.6M条启发式生成的语义关系以及4.7M条指代陈述。我们的数据集还包含语义物体和房间标注、场景图、可导航自由空间标注，并补充了语言存在不完美或歧义的陈述。我们通过使用当前最先进的模型进行评估，验证了数据集的通用性，获得了性能基线，并开发了一个基于图搜索的基线方法，以展示性能边界以及如何利用场景图知识生成替代方案。通过这一基准数据集，我们旨在为3D场景理解提供一个资源，助力开发健壮的交互式导航系统。数据集和所有源代码已公开发布于https://github.com/HaochenZ11/IRef-VLA。

> With the recent rise of large language models, vision-language models, and other general foundation models, there is growing potential for multimodal, multi-task robotics that can operate in diverse environments given natural language input. One such application is indoor navigation using natural language instructions. However, despite recent progress, this problem remains challenging due to the 3D spatial reasoning and semantic understanding required. Additionally, the language used may be imperfect or misaligned with the scene, further complicating the task. To address this challenge, we curate a benchmark dataset, IRef-VLA, for Interactive Referential Vision and Language-guided Action in 3D Scenes with imperfect references. IRef-VLA is the largest real-world dataset for the referential grounding task, consisting of over 11.5K scanned 3D rooms from existing datasets, 7.6M heuristically generated semantic relations, and 4.7M referential statements. Our dataset also contains semantic object and room annotations, scene graphs, navigable free space annotations, and is augmented with statements where the language has imperfections or ambiguities. We verify the generalizability of our dataset by evaluating with state-of-the-art models to obtain a performance baseline and also develop a graph-search baseline to demonstrate the performance bound and generation of alternatives using scene-graph knowledge. With this benchmark, we aim to provide a resource for 3D scene understanding that aids the development of robust, interactive navigation systems. The dataset and all source code is publicly released at https://github.com/HaochenZ11/IRef-VLA.

[Arxiv](https://arxiv.org/abs/2503.17406)