# MLLM-Search：一种借助多模态大型语言模型来查找人员的零样本方式

发布时间：2024年11月27日

`LLM应用` `机器人`

> MLLM-Search: A Zero-Shot Approach to Finding People using Multimodal Large Language Models

# 摘要

> 在以人为本的环境（如医疗保健场所）中，机器人对人员的搜索颇具挑战，因为自主机器人在没有人员日程、计划或位置的完整或任何先验知识的情况下就得定位人员。而且，机器人还得能适应可能影响环境中人员计划的实时事件。在本文中，我们提出了 MLLM-Search 这一全新的零样本人员搜索架构，它借助多模态大型语言模型（MLLM）来解决在事件驱动场景和不同用户日程下移动机器人搜索人员的难题。我们的方法引入了新颖的视觉提示手段，通过生成空间基础的航路点地图，以拓扑图表示可导航的航路点，用语义标签表示区域，从而为机器人提供对环境的空间理解。这被融入到带有区域规划器的 MLLM 中，区域规划器依据与搜索场景的语义相关性选定下一个搜索区域，还有航路点规划器，它通过我们独特的空间思维链提示方法，综合考虑语义相关对象和局部空间上下文来生成搜索路径。开展了大量的 3D 逼真实验，以验证 MLLM-Search 在不同环境中搜索日程变化人员的性能。还进行了消融研究，以验证 MLLM-Search 的主要设计选择。此外，与最先进的搜索方法的对比研究表明，MLLM-Search 在搜索效率方面优于现有方法。在建筑物多房间楼层中用移动机器人进行的真实世界实验显示，MLLM-Search 能够推广到在新的未见过的环境中寻找人员。

> Robotic search of people in human-centered environments, including healthcare settings, is challenging as autonomous robots need to locate people without complete or any prior knowledge of their schedules, plans or locations. Furthermore, robots need to be able to adapt to real-time events that can influence a person's plan in an environment. In this paper, we present MLLM-Search, a novel zero-shot person search architecture that leverages multimodal large language models (MLLM) to address the mobile robot problem of searching for a person under event-driven scenarios with varying user schedules. Our approach introduces a novel visual prompting method to provide robots with spatial understanding of the environment by generating a spatially grounded waypoint map, representing navigable waypoints by a topological graph and regions by semantic labels. This is incorporated into a MLLM with a region planner that selects the next search region based on the semantic relevance to the search scenario, and a waypoint planner which generates a search path by considering the semantically relevant objects and the local spatial context through our unique spatial chain-of-thought prompting approach. Extensive 3D photorealistic experiments were conducted to validate the performance of MLLM-Search in searching for a person with a changing schedule in different environments. An ablation study was also conducted to validate the main design choices of MLLM-Search. Furthermore, a comparison study with state-of-the art search methods demonstrated that MLLM-Search outperforms existing methods with respect to search efficiency. Real-world experiments with a mobile robot in a multi-room floor of a building showed that MLLM-Search was able to generalize to finding a person in a new unseen environment.

[Arxiv](https://arxiv.org/abs/2412.00103)