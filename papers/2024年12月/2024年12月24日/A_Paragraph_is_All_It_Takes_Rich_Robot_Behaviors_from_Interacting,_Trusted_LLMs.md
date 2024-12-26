# 仅需一段文字：从交互且可信的大型语言模型中获取丰富的机器人行为

发布时间：2024年12月24日

`LLM应用` `机器人` `人工智能`

> A Paragraph is All It Takes: Rich Robot Behaviors from Interacting, Trusted LLMs

# 摘要

> 大型语言模型（LLMs）是我们所处物理环境以及动物和人类行为等所有公共知识的精简呈现。将 LLMs 应用于机器人领域，或许能为打造出在多数人类任务中表现出色、甚至只需少量或无需调试的高性能机器人开辟道路。除了愈发精妙的推理和任务规划，（精心设计的）LLMs 网络便于升级能力，还能让人类直接观察机器人的思考过程。在此，我们探究使用 LLMs 操控实体机器人的优势、局限和特性。基本系统由四个通过人类语言数据总线通信的 LLMs 构成，该总线通过网络套接字和 ROS2 消息传递来实现。令人惊奇的是，即便机器人的数据融合周期仅为 1Hz，中央数据总线的运行速率也极其有限，约为人脑的 40 位/秒，但仍能达成丰富的机器人行为和在不同任务中的出色表现。采用自然语言进行 LLMs 间的通信，使得人类能够直接观察机器人的推理和决策，而且通过用简单英语编写的规则集来影响系统行为也变得轻而易举。这些规则被不可更改地写入以太坊，这是一个全球性、公开且抗审查的图灵完备计算机。我们认为，以自然语言作为交互 AI 间的数据总线，并利用不可更改的公共账本存储行为约束，就有可能造出兼具出色性能、可升级性以及与人类长期协调一致的机器人。

> Large Language Models (LLMs) are compact representations of all public knowledge of our physical environment and animal and human behaviors. The application of LLMs to robotics may offer a path to highly capable robots that perform well across most human tasks with limited or even zero tuning. Aside from increasingly sophisticated reasoning and task planning, networks of (suitably designed) LLMs offer ease of upgrading capabilities and allow humans to directly observe the robot's thinking. Here we explore the advantages, limitations, and particularities of using LLMs to control physical robots. The basic system consists of four LLMs communicating via a human language data bus implemented via web sockets and ROS2 message passing. Surprisingly, rich robot behaviors and good performance across different tasks could be achieved despite the robot's data fusion cycle running at only 1Hz and the central data bus running at the extremely limited rates of the human brain, of around 40 bits/s. The use of natural language for inter-LLM communication allowed the robot's reasoning and decision making to be directly observed by humans and made it trivial to bias the system's behavior with sets of rules written in plain English. These rules were immutably written into Ethereum, a global, public, and censorship resistant Turing-complete computer. We suggest that by using natural language as the data bus among interacting AIs, and immutable public ledgers to store behavior constraints, it is possible to build robots that combine unexpectedly rich performance, upgradability, and durable alignment with humans.

[Arxiv](https://arxiv.org/abs/2412.18588)