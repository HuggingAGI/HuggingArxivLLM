# AViLA：用于流式多模态数据交互的异步视觉语言智能体

发布时间：2025年06月23日

`Agent` `自动驾驶` `流式数据处理`

> AViLA: Asynchronous Vision-Language Agent for Streaming Multimodal Data Interaction

# 摘要

> 一个理想的视觉语言代理在人类用户与其周围物理世界之间架起了一座桥梁，特别是在自动驾驶和具身智能体等实际应用中，能够根据用户意图主动提供准确且及时的响应。然而，当代理以动态数据流的形式与世界互动，并面对用户的临时查询时，一个引人入胜的挑战出现了：支持查询的知识，即证据，通常会与查询的到达时间不同步出现，而代理需要将响应基于历史数据、当前观察，甚至未来的数据流。我们将这一挑战定义为查询-证据异步性，在流式设置下，用户查询与其支持的证据通常会异步到达。这一设置不仅需要强大的推理能力，还需要代理能够保留过去的观察，并以时间感知的方式响应查询。在本文中，我们引入了一个诊断基准，用于评估多模态大语言模型（MLLMs）在处理与流式数据交互方面的能力。此外，我们提出了AViLA（用于流式数据交互的异步视频语言代理），它能够处理临时查询并提供时间感知的响应。为了实现这一目标，AViLA由三个关键模块组成：全面的记忆保留、证据识别和基于证据的触发机制，这些模块旨在维护一个通用记忆，并能够随时快速响应查询。我们的实验表明，现有模型常常无法在适当的时间做出响应，而AViLA在准确性和时间感知方面都有了显著提升。我们的代码和数据集将公开发布。

> An ideal vision-language agent serves as a bridge between the human users and their surrounding physical world in real-world applications like autonomous driving and embodied agents, and proactively provides accurate and timely responses given user intents. An intriguing challenge arises when agents interact with the world as a dynamic data stream and ad-hoc queries from users: supporting knowledge for queries, namely evidence, usually appears asynchronously with the arrival time of queries, and agents need to ground their responses in historical data, present observations, and even future streams. We frame this challenge as Query-Evidence Asynchrony, where user queries and their supporting evidence typically arrive asynchronously in the streaming setting. This setting requires not only strong reasoning capabilities but also the ability to retain past observations and respond to queries with temporal awareness. In this paper, we introduce a diagnostic benchmark that evaluates Multimodal Large Language Models (MLLMs) on their ability to handle interaction with streaming data. Further, we present AViLA, Asynchronous Video-Language Agent for streaming data interaction that can handle ad-hoc queries and give time-aware responses. For this purpose, AViLA consists of three key modules: comprehensive memory retention, evidence identification, and evidence-grounded trigger, that are designed to maintain a general-purpose memory and respond readily and timely to queries. Our experiments show that existing models often fail to respond at appropriate times, while AViLA significantly improves both accuracy and temporal awareness. Our code and dataset will be publicly available.

[Arxiv](https://arxiv.org/abs/2506.18472)