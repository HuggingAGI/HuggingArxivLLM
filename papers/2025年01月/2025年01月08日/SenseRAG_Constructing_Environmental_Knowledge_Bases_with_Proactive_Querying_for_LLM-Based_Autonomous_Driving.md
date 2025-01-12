# SenseRAG：主动查询助力LLM自动驾驶构建环境知识库

发布时间：2025年01月08日

`LLM应用

理由：该论文主要探讨了如何利用大型语言模型（LLMs）的上下文推理能力来增强自动驾驶（AD）中的情境感知。论文中提到了使用检索增强生成（RAG）方法来克服LLMs的延迟和模态限制，并结合思维链提示机制来提升感知和预测性能。这些内容主要涉及LLM在实际应用中的使用和改进，因此将其分类为“LLM应用”。` `自动驾驶` `车联网`

> SenseRAG: Constructing Environmental Knowledge Bases with Proactive Querying for LLM-Based Autonomous Driving

# 摘要

> 本研究利用大型语言模型（LLMs）的上下文推理能力，解决了自动驾驶（AD）中增强情境感知的迫切需求。与依赖固定标签的传统感知系统不同，它将实时多模态传感器数据整合为LLMs可读的知识库，使LLMs能够动态理解并应对复杂驾驶环境。为克服LLMs的延迟和模态限制，我们设计了主动的检索增强生成（RAG）方法，结合思维链提示机制，确保快速且富含上下文的理解。基于真实车联网（V2X）数据集的实验表明，感知和预测性能显著提升，展现了该框架在提升下一代AD系统安全性、适应性和决策能力方面的巨大潜力。

> This study addresses the critical need for enhanced situational awareness in autonomous driving (AD) by leveraging the contextual reasoning capabilities of large language models (LLMs). Unlike traditional perception systems that rely on rigid, label-based annotations, it integrates real-time, multimodal sensor data into a unified, LLMs-readable knowledge base, enabling LLMs to dynamically understand and respond to complex driving environments. To overcome the inherent latency and modality limitations of LLMs, a proactive Retrieval-Augmented Generation (RAG) is designed for AD, combined with a chain-of-thought prompting mechanism, ensuring rapid and context-rich understanding. Experimental results using real-world Vehicle-to-everything (V2X) datasets demonstrate significant improvements in perception and prediction performance, highlighting the potential of this framework to enhance safety, adaptability, and decision-making in next-generation AD systems.

[Arxiv](https://arxiv.org/abs/2501.03535)