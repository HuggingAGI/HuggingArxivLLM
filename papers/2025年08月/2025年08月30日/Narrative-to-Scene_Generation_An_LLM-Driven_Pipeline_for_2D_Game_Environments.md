# 叙事转场景生成：面向2D游戏环境的LLM驱动流水线

发布时间：2025年08月30日

`LLM应用` `媒体与娱乐`

> Narrative-to-Scene Generation: An LLM-Driven Pipeline for 2D Game Environments

# 摘要

> 大型语言模型（LLMs）的最新进展已能生成引人入胜的故事，但在程序内容生成（PCG）领域，如何将叙事文本转化为可交互的视觉环境仍是亟待攻克的难题。我们研发了一种轻量级流程，可将简短的叙事提示转化为2D瓦片式游戏场景序列，直观呈现故事的时间脉络。对于LLM生成的叙事文本，系统会先锁定三个关键时间帧，提取“对象-关系-对象”三元组形式的空间谓词，再借助GameTileNet数据集的功能感知语义嵌入检索视觉资源。通过元胞自动机生成分层地形后，依据谓词结构中的空间规则完成对象布局。我们在十个不同类型的故事上对系统展开评估，分析了跨帧的瓦片-对象匹配度、功能层对齐情况及空间约束满足度。该原型为叙事驱动的场景生成提供了可扩展的解决方案，也为未来在故事中心PCG中探索多帧连续性、符号跟踪与多智能体协作奠定了基础。

> Recent advances in large language models(LLMs) enable compelling story generation, but connecting narrative text to playable visual environments remains an open challenge in procedural content generation(PCG). We present a lightweight pipeline that transforms short narrative prompts into a sequence of 2D tile-based game scenes, reflecting the temporal structure of stories. Given an LLM-generated narrative, our system identifies three key time frames, extracts spatial predicates in the form of "Object-Relation-Object" triples, and retrieves visual assets using affordance-aware semantic embeddings from the GameTileNet dataset. A layered terrain is generated using Cellular Automata, and objects are placed using spatial rules grounded in the predicate structure. We evaluated our system in ten diverse stories, analyzing tile-object matching, affordance-layer alignment, and spatial constraint satisfaction across frames. This prototype offers a scalable approach to narrative-driven scene generation and lays the foundation for future work on multi-frame continuity, symbolic tracking, and multi-agent coordination in story-centered PCG.

[Arxiv](https://arxiv.org/abs/2509.04481)