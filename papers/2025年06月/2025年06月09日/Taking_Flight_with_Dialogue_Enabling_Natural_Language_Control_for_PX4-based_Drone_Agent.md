# 对话赋能飞行，实现PX4无人机的自然语言控制

发布时间：2025年06月09日

`Agent` `无人机` `机器人技术`

> Taking Flight with Dialogue: Enabling Natural Language Control for PX4-based Drone Agent

# 摘要

> 近年来，智能体和物理人工智能（AI）的研究主要集中在人形机器人和轮式机器人等地面平台上，而对飞行机器人的研究则相对较少。与此同时，最先进的无人机多模态视觉语言系统通常依赖于闭源模型，这些模型仅对资源充足的组织开放。为了实现自主无人机的自然语言控制民主化，我们提出一个开源智能体框架，集成了基于PX4的飞行控制、机器人操作系统2（ROS 2）中间件以及使用Ollama本地托管的模型。我们在仿真环境和定制的四旋翼平台上评估了性能，基准测试了四个大型语言模型（LLM）家族用于指令生成，以及三个视觉语言模型（VLM）家族用于场景理解。

> Recent advances in agentic and physical artificial intelligence (AI) have largely focused on ground-based platforms such as humanoid and wheeled robots, leaving aerial robots relatively underexplored. Meanwhile, state-of-the-art unmanned aerial vehicle (UAV) multimodal vision-language systems typically rely on closed-source models accessible only to well-resourced organizations. To democratize natural language control of autonomous drones, we present an open-source agentic framework that integrates PX4-based flight control, Robot Operating System 2 (ROS 2) middleware, and locally hosted models using Ollama. We evaluate performance both in simulation and on a custom quadcopter platform, benchmarking four large language model (LLM) families for command generation and three vision-language model (VLM) families for scene understanding.

[Arxiv](https://arxiv.org/abs/2506.07509)