# AsyncFlow：专为高效大语言模型后训练设计的异步流式强化学习框架。

发布时间：2025年07月02日

`其他

理由：这篇论文主要讨论的是强化学习框架的设计与优化，虽然提到了大型语言模型（LLMs）的应用，但其核心内容是关于强化学习框架的架构和性能提升，属于系统设计和优化的范畴，因此归类为“其他”。` `系统优化` `人工智能`

> AsyncFlow: An Asynchronous Streaming RL Framework for Efficient LLM Post-Training

# 摘要

> 强化学习（RL）已成为大型语言模型（LLMs）后训练阶段的关键技术。传统任务共置型RL框架面临扩展性瓶颈，而任务分离型框架则因复杂数据流导致资源空闲和负载不均。此外，现有框架多与训练或推理引擎深度绑定，难以支持定制化需求。为解决这些问题，我们提出AsyncFlow——一款高效后训练的异步流式强化学习框架。

AsyncFlow的核心创新包括：
1. 分布式数据存储与传输模块：以全流式方式实现统一数据管理和细粒度调度
2. 天然支持RL任务间的流水线重叠与动态负载均衡
3. 基于生产者-消费者模式的异步工作流：通过智能推迟参数更新最大限度减少计算空闲
4. 核心能力与引擎解耦：通过服务化接口提供模块化、可定制的用户体验

实验表明，AsyncFlow较现有最优方案平均提升1.59倍吞吐量。本文架构为下一代RL训练系统设计提供了重要参考。

> Reinforcement learning (RL) has become a pivotal technology in the post-training phase of large language models (LLMs). Traditional task-colocated RL frameworks suffer from significant scalability bottlenecks, while task-separated RL frameworks face challenges in complex dataflows and the corresponding resource idling and workload imbalance. Moreover, most existing frameworks are tightly coupled with LLM training or inference engines, making it difficult to support custom-designed engines. To address these challenges, we propose AsyncFlow, an asynchronous streaming RL framework for efficient post-training. Specifically, we introduce a distributed data storage and transfer module that provides a unified data management and fine-grained scheduling capability in a fully streamed manner. This architecture inherently facilitates automated pipeline overlapping among RL tasks and dynamic load balancing. Moreover, we propose a producer-consumer-based asynchronous workflow engineered to minimize computational idleness by strategically deferring parameter update process within staleness thresholds. Finally, the core capability of AsynFlow is architecturally decoupled from underlying training and inference engines and encapsulated by service-oriented user interfaces, offering a modular and customizable user experience. Extensive experiments demonstrate an average of 1.59 throughput improvement compared with state-of-the-art baseline. The presented architecture in this work provides actionable insights for next-generation RL training system designs.

[Arxiv](https://arxiv.org/abs/2507.01663)