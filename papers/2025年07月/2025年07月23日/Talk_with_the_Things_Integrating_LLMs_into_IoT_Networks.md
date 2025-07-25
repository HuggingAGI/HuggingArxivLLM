# 与万物对话：将大型语言模型融入物联网网络

发布时间：2025年07月23日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在物联网（IoT）中的应用，特别是通过边缘计算和RAG框架来实现智能控制和自动化。虽然提到了RAG，但主要关注的是应用层面，因此归类为LLM应用。` `物联网` `边缘计算`

> Talk with the Things: Integrating LLMs into IoT Networks

# 摘要

> 大型语言模型 (LLMs) 与物联网 (IoT) 的融合为构建智能、响应式和用户友好的系统带来了新机遇。本研究提出了一种以边缘计算为中心的框架，将 LLMs 集成到 IoT 架构中，实现基于自然语言的控制、上下文感知的决策制定和增强的自动化。我们设计了一种模块化且轻量级的基于检索增强生成 (RAG) 的 LLMs，并将其部署在连接到 IoT 网关的边缘计算设备上，从而实现用户命令和传感器数据的本地处理，显著降低了延迟、提升了隐私性并增强了推理质量。通过使用 LLaMA 3 和 Gemma 2B 模型控制智能设备的智能家居原型，我们验证了该框架的有效性。实验结果展示了模型大小与推理时间之间的权衡关系。最后，我们探讨了基于 LLM 的 IoT 系统的潜在应用场景，并指出了这些系统面临的一些关键挑战。

> The convergence of Large Language Models (LLMs) and Internet of Things (IoT) networks open new opportunities for building intelligent, responsive, and user-friendly systems. This work presents an edge-centric framework that integrates LLMs into IoT architectures to enable natural language-based control, context-aware decision-making, and enhanced automation. The proposed modular and lightweight Retrieval Augmented Generation (RAG)-based LLMs are deployed on edge computing devices connected to IoT gateways, enabling local processing of user commands and sensor data for reduced latency, improved privacy, and enhanced inference quality. We validate the framework through a smart home prototype using LLaMA 3 and Gemma 2B models for controlling smart devices. Experimental results highlight the trade-offs between model accuracy and inference time with respect to models size. At last, we also discuss the potential applications that can use LLM-based IoT systems, and a few key challenges associated with such systems.

[Arxiv](https://arxiv.org/abs/2507.17865)