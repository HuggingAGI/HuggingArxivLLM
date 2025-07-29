# 围绕：认知启发的反应式机器人推理

发布时间：2025年07月28日

`Agent` `机器人` `人工智能`

> Hanging Around: Cognitive Inspired Reasoning for Reactive Robotics

# 摘要

> 在自然环境中表现出色的情境感知型人工智能代理，面临着诸多挑战：空间感知能力、物体可操作性检测、动态变化及不可预测性。其中，代理能否识别并持续监测与其目标相关的环境要素，是一个关键挑战。我们提出了一种用于反应式机器人技术的神经符号模块化架构。我们的系统结合了神经网络组件（用于环境中的物体识别及光流等图像处理技术）与符号表征和推理机制。推理系统基于具身认知范式，通过在本体结构中整合图像图式知识来实现。该本体结构用于生成对感知系统的查询、决定行动方案，以及从感知数据中推断出实体的能力。推理与图像处理的结合使代理能够在正常运行中集中其感知能力，同时发现与特定交互相关联的部分物体的新概念。这些发现的概念使机器人能够自主获取训练数据，并调整其子符号感知以识别这些部分，同时通过聚焦于相关物体部分来使更复杂任务的规划成为可能。我们在模拟环境中演示了我们的方法，在此情境下，一个代理学习识别参与支撑关系的物体部分。尽管该代理最初没有“手柄”的概念，但它通过观察被支撑物体悬挂在钩子上的示例，学会了识别建立支撑关系所涉及的部分，并能够规划支撑关系的建立/破坏。这凸显了代理通过系统化观察扩展其知识的能力，并展示了深度推理与感知结合的潜力。

> Situationally-aware artificial agents operating with competence in natural environments face several challenges: spatial awareness, object affordance detection, dynamic changes and unpredictability. A critical challenge is the agent's ability to identify and monitor environmental elements pertinent to its objectives. Our research introduces a neurosymbolic modular architecture for reactive robotics. Our system combines a neural component performing object recognition over the environment and image processing techniques such as optical flow, with symbolic representation and reasoning. The reasoning system is grounded in the embodied cognition paradigm, via integrating image schematic knowledge in an ontological structure. The ontology is operatively used to create queries for the perception system, decide on actions, and infer entities' capabilities derived from perceptual data. The combination of reasoning and image processing allows the agent to focus its perception for normal operation as well as discover new concepts for parts of objects involved in particular interactions. The discovered concepts allow the robot to autonomously acquire training data and adjust its subsymbolic perception to recognize the parts, as well as making planning for more complex tasks feasible by focusing search on those relevant object parts. We demonstrate our approach in a simulated world, in which an agent learns to recognize parts of objects involved in support relations. While the agent has no concept of handle initially, by observing examples of supported objects hanging from a hook it learns to recognize the parts involved in establishing support and becomes able to plan the establishment/destruction of the support relation. This underscores the agent's capability to expand its knowledge through observation in a systematic way, and illustrates the potential of combining deep reasoning [...].

[Arxiv](https://arxiv.org/abs/2507.20832)