# osmAG-LLM：基于语义地图和大型语言模型推理的零样本开放词汇目标导航

发布时间：2025年07月16日

`Agent` `机器人技术` `人工智能`

> osmAG-LLM: Zero-Shot Open-Vocabulary Object Navigation via Semantic Maps and Large Language Models Reasoning

# 摘要

> 开放词汇机器人映射方法通过预训练的视觉-语言特征丰富了密集几何地图，实现了高度细节化，并能根据开放词汇语言指令引导机器人找到指定物体。尽管这些方法的可扩展性已受到关注，但更关键的问题在于，高细节物体映射会迅速过时，因为物体经常被移动。我们开发了一个面向物体目标导航的全新映射与导航系统，该系统从设计之初就考虑了所查询物体可能已经移动或从未被映射的可能性。我们不再追求高保真度细节映射，而是认为地图的主要作用是提供环境定位和上下文，因此我们将LLMs的语义先验与主动在线导航方法相结合，用于推理物体位置。通过模拟和真实世界的实验，我们发现，与现有方法相比，我们的方法在静态物体上往往能够在更短的路径长度内实现更高的检索成功率，并且在动态物体或未映射物体的查询场景中表现远超先前方法。我们提供了我们的代码和数据集，地址为：https://anonymous.4open.science/r/osmAG-LLM。
    

> Recent open-vocabulary robot mapping methods enrich dense geometric maps with pre-trained visual-language features, achieving a high level of detail and guiding robots to find objects specified by open-vocabulary language queries. While the issue of scalability for such approaches has received some attention, another fundamental problem is that high-detail object mapping quickly becomes outdated, as objects get moved around a lot. In this work, we develop a mapping and navigation system for object-goal navigation that, from the ground up, considers the possibilities that a queried object can have moved, or may not be mapped at all. Instead of striving for high-fidelity mapping detail, we consider that the main purpose of a map is to provide environment grounding and context, which we combine with the semantic priors of LLMs to reason about object locations and deploy an active, online approach to navigate to the objects. Through simulated and real-world experiments we find that our approach tends to have higher retrieval success at shorter path lengths for static objects and by far outperforms prior approaches in cases of dynamic or unmapped object queries. We provide our code and dataset at: https://anonymous.4open.science/r/osmAG-LLM.

[Arxiv](https://arxiv.org/abs/2507.12753)