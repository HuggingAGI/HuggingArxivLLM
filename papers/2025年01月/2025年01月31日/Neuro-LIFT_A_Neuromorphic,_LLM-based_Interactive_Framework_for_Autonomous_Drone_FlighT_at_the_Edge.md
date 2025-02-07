# Neuro-LIFT: 基于神经形态和LLM的边缘自主无人机飞行交互框架

发布时间：2025年01月31日

`Agent

理由：这篇论文主要讨论的是将大型语言模型（LLMs）与自主导航系统结合，通过自然语言处理实现人类指令与机器人行动的连接。论文的核心是开发了一个名为Neuro-LIFT的实时神经形态导航框架，该框架在无人机上实现，能够将人类语音转化为高级规划指令，并利用神经形态视觉和物理规划自主执行任务。这涉及到自主系统的行为决策和执行，符合“Agent”这一分类的定义，即能够感知环境并采取行动以实现特定目标的智能体。` `机器人` `无人机`

> Neuro-LIFT: A Neuromorphic, LLM-based Interactive Framework for Autonomous Drone FlighT at the Edge

# 摘要

> # 摘要
将人类直观交互融入自主系统的能力一直受限。传统自然语言处理（NLP）系统在上下文和意图理解上表现不佳，严重制约了人机交互。然而，大型语言模型（LLMs）的突破性进展改变了这一局面，通过语音和文本实现了直观且高效的交流，成功连接了人类指令与机器人行动。与此同时，自主导航成为机器人研究的核心领域，人工智能（AI）被广泛用于提升系统性能。然而，现有基于AI的导航算法在需要快速决策的延迟关键任务中面临巨大挑战。传统基于帧的视觉系统虽适用于高级决策，但高能耗和高延迟限制了其在实时场景中的应用。神经形态视觉系统结合事件相机和脉冲神经网络（SNNs），提供了一种高效能、低延迟的导航方案。尽管潜力巨大，这些系统在物理平台（如无人机）上的实际应用仍较为罕见。本研究提出了Neuro-LIFT，一种在Parrot Bebop2四旋翼无人机上实现的实时神经形态导航框架。通过LLM进行自然语言处理，Neuro-LIFT将人类语音转化为高级规划指令，并利用事件驱动的神经形态视觉和物理规划自主执行。该框架展示了其在动态环境中导航、避障以及实时响应人类指令的强大能力。

> The integration of human-intuitive interactions into autonomous systems has been limited. Traditional Natural Language Processing (NLP) systems struggle with context and intent understanding, severely restricting human-robot interaction. Recent advancements in Large Language Models (LLMs) have transformed this dynamic, allowing for intuitive and high-level communication through speech and text, and bridging the gap between human commands and robotic actions. Additionally, autonomous navigation has emerged as a central focus in robotics research, with artificial intelligence (AI) increasingly being leveraged to enhance these systems. However, existing AI-based navigation algorithms face significant challenges in latency-critical tasks where rapid decision-making is critical. Traditional frame-based vision systems, while effective for high-level decision-making, suffer from high energy consumption and latency, limiting their applicability in real-time scenarios. Neuromorphic vision systems, combining event-based cameras and spiking neural networks (SNNs), offer a promising alternative by enabling energy-efficient, low-latency navigation. Despite their potential, real-world implementations of these systems, particularly on physical platforms such as drones, remain scarce. In this work, we present Neuro-LIFT, a real-time neuromorphic navigation framework implemented on a Parrot Bebop2 quadrotor. Leveraging an LLM for natural language processing, Neuro-LIFT translates human speech into high-level planning commands which are then autonomously executed using event-based neuromorphic vision and physics-driven planning. Our framework demonstrates its capabilities in navigating in a dynamic environment, avoiding obstacles, and adapting to human instructions in real-time.

[Arxiv](https://arxiv.org/abs/2501.19259)