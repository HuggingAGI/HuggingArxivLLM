# InternLM-XComposer2.5-OmniLive：一个用于长期流媒体视频及音频交互的综合性多模态系统

发布时间：2024年12月12日

`LLM应用` `人工智能` `多模态交互`

> InternLM-XComposer2.5-OmniLive: A Comprehensive Multimodal System for Long-term Streaming Video and Audio Interactions

# 摘要

> 创建能像人类认知那样长期与环境交互的人工智能系统，一直是长期以来的研究目标。多模态大型语言模型（MLLMs）的最新进展在开放世界理解方面成果显著。然而，连续且同步的流式感知、记忆与推理所面临的挑战，在很大程度上仍未被探索。当前的 MLLMs 受其序列到序列架构的制约，限制了其同时处理输入和生成响应的能力，就好比在感知时无法思考。此外，依靠长上下文来存储历史数据对于长期交互并不现实，因为保留所有信息成本高昂且效率低下。所以，本项目并非依赖单个基础模型来实现所有功能，而是从专业通才人工智能的理念中获取灵感，引入解耦的流式感知、推理和记忆机制，实现与流式视频和音频输入的实时交互。所提出的框架 InternLM-XComposer2.5-OmniLive（IXC2.5-OL）包含三个关键模块：（1）流式感知模块：实时处理多模态信息，将关键细节存入内存，并根据用户查询触发推理。（2）多模态长记忆模块：整合短期和长期记忆，将短期记忆压缩为长期记忆，以实现高效检索和提高准确性。（3）推理模块：响应查询并执行推理任务，与感知和记忆模块协同工作。本项目模拟人类认知，让多模态大型语言模型能够随时间推移提供持续且自适应的服务。

> Creating AI systems that can interact with environments over long periods, similar to human cognition, has been a longstanding research goal. Recent advancements in multimodal large language models (MLLMs) have made significant strides in open-world understanding. However, the challenge of continuous and simultaneous streaming perception, memory, and reasoning remains largely unexplored. Current MLLMs are constrained by their sequence-to-sequence architecture, which limits their ability to process inputs and generate responses simultaneously, akin to being unable to think while perceiving. Furthermore, relying on long contexts to store historical data is impractical for long-term interactions, as retaining all information becomes costly and inefficient. Therefore, rather than relying on a single foundation model to perform all functions, this project draws inspiration from the concept of the Specialized Generalist AI and introduces disentangled streaming perception, reasoning, and memory mechanisms, enabling real-time interaction with streaming video and audio input. The proposed framework InternLM-XComposer2.5-OmniLive (IXC2.5-OL) consists of three key modules: (1) Streaming Perception Module: Processes multimodal information in real-time, storing key details in memory and triggering reasoning in response to user queries. (2) Multi-modal Long Memory Module: Integrates short-term and long-term memory, compressing short-term memories into long-term ones for efficient retrieval and improved accuracy. (3) Reasoning Module: Responds to queries and executes reasoning tasks, coordinating with the perception and memory modules. This project simulates human-like cognition, enabling multimodal large language models to provide continuous and adaptive service over time.

[Arxiv](https://arxiv.org/abs/2412.09596)