# 打造可靠的离线个人AI助手，助力长时间太空飞行

发布时间：2024年10月21日

`Agent

理由：这篇论文主要讨论的是开发一个AI助手（METIS）来帮助宇航员在太空任务中自主操作，处理日常任务、监控系统并检测异常。虽然提到了GPT模型和检索增强生成（RAG），但核心内容是构建一个能够自主执行任务的智能代理（Agent），因此将其分类为Agent更为合适。` `航空航天` `人工智能`

> Towards a Reliable Offline Personal AI Assistant for Long Duration Spaceflight

# 摘要

> 随着人类准备踏上月球和火星的新征程，宇航员将面临更大的自主操作挑战，因为通信延迟使得地球的实时支持变得困难。例如，火星与地球之间的消息传输可能需要长达24分钟，快速响应几乎不可能。这一限制对宇航员构成了严峻挑战，他们必须依赖现场工具来访问来自航天器传感器、探测器和卫星的大量数据，而这些数据往往分散且难以使用。为了应对这一挑战，火星探索遥测驱动信息系统（METIS）等系统正在开发中。METIS是一个AI助手，旨在处理日常任务、监控航天器系统并检测异常，同时减少对任务控制的依赖。尽管当前的生成预训练变换器（GPT）模型功能强大，但在安全关键环境中表现不佳，可能生成看似合理但不正确的响应，这种现象被称为“幻觉”，可能危及宇航员的安全。为了克服这些限制，本文提出通过整合GPT、检索增强生成（RAG）、知识图谱（KGs）和增强现实（AR）来增强METIS等系统。其目标是让宇航员能够更直观地与数据交互，使用自然语言查询并通过AR可视化实时信息。KGs将用于轻松访问实时遥测和多模态数据，确保宇航员在关键时刻获得准确信息。通过结合AI、KGs和AR，这一新系统将使宇航员在未来的太空任务中能够更自主、安全和高效地工作。

> As humanity prepares for new missions to the Moon and Mars, astronauts will need to operate with greater autonomy, given the communication delays that make real-time support from Earth difficult. For instance, messages between Mars and Earth can take up to 24 minutes, making quick responses impossible. This limitation poses a challenge for astronauts who must rely on in-situ tools to access the large volume of data from spacecraft sensors, rovers, and satellites, data that is often fragmented and difficult to use. To bridge this gap, systems like the Mars Exploration Telemetry-Driven Information System (METIS) are being developed. METIS is an AI assistant designed to handle routine tasks, monitor spacecraft systems, and detect anomalies, all while reducing the reliance on mission control. Current Generative Pretrained Transformer (GPT) Models, while powerful, struggle in safety-critical environments. They can generate plausible but incorrect responses, a phenomenon known as "hallucination," which could endanger astronauts. To overcome these limitations, this paper proposes enhancing systems like METIS by integrating GPTs, Retrieval-Augmented Generation (RAG), Knowledge Graphs (KGs), and Augmented Reality (AR). The idea is to allow astronauts to interact with their data more intuitively, using natural language queries and visualizing real-time information through AR. KGs will be used to easily access live telemetry and multimodal data, ensuring that astronauts have the right information at the right time. By combining AI, KGs, and AR, this new system will empower astronauts to work more autonomously, safely, and efficiently during future space missions.

[Arxiv](https://arxiv.org/abs/2410.16397)