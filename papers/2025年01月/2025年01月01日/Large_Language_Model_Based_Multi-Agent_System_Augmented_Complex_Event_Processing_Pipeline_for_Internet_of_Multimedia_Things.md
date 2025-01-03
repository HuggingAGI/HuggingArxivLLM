# 基于大型语言模型的多智能体系统增强的复杂事件处理管道，应用于多媒体物联网

发布时间：2025年01月01日

`Agent

理由：这篇论文描述了一个基于大型语言模型（LLM）的多智能体系统框架，专注于复杂事件处理（CEP）中的视频查询处理用例。它涉及多个智能体的协作和自主工作流的处理，符合“Agent”分类的定义，即涉及多智能体系统和智能体之间的协作与交互。` `视频处理` `分布式系统`

> Large Language Model Based Multi-Agent System Augmented Complex Event Processing Pipeline for Internet of Multimedia Things

# 摘要

> 本文介绍了一种基于大型语言模型（LLM）的多智能体系统框架的开发与评估，专注于复杂事件处理（CEP）中的视频查询处理用例。目标是构建一个概念验证（POC），将先进的LLM编排框架与发布/订阅（pub/sub）工具结合，解决LLM与现有CEP系统的集成问题。通过Autogen框架与Kafka消息代理的结合，系统展示了能够处理复杂工作流的自主CEP管道。大量实验评估了系统在不同配置、复杂性和视频分辨率下的性能，揭示了功能与延迟的权衡。结果显示，尽管智能体数量和视频复杂性增加会提升延迟，但系统在叙事一致性上表现优异。本研究为分布式AI系统提供了新思路，并详细探讨了如何将其集成到现有基础设施中。

> This paper presents the development and evaluation of a Large Language Model (LLM), also known as foundation models, based multi-agent system framework for complex event processing (CEP) with a focus on video query processing use cases. The primary goal is to create a proof-of-concept (POC) that integrates state-of-the-art LLM orchestration frameworks with publish/subscribe (pub/sub) tools to address the integration of LLMs with current CEP systems. Utilizing the Autogen framework in conjunction with Kafka message brokers, the system demonstrates an autonomous CEP pipeline capable of handling complex workflows. Extensive experiments evaluate the system's performance across varying configurations, complexities, and video resolutions, revealing the trade-offs between functionality and latency. The results show that while higher agent count and video complexities increase latency, the system maintains high consistency in narrative coherence. This research builds upon and contributes to, existing novel approaches to distributed AI systems, offering detailed insights into integrating such systems into existing infrastructures.

[Arxiv](https://arxiv.org/abs/2501.00906)