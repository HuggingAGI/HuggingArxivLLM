# ORAN-GUIDE: RAG驱动的提示学习，助力LLM增强的强化学习，应用于O-RAN网络切片。

发布时间：2025年05月31日

`LLM应用` `无线通信` `人工智能`

> ORAN-GUIDE: RAG-Driven Prompt Learning for LLM-Augmented Reinforcement Learning in O-RAN Network Slicing

# 摘要

> 先进无线网络必须能够满足高度动态和异构的服务需求。开放无线接入网络（O-RAN）架构通过模块化、分散化的组件（如RIC、CU和DU）实现了这种灵活性，并支持通过机器学习进行智能控制。虽然深度强化学习（DRL）是管理动态资源分配和切片的强大工具，但它在处理射频特征、服务质量指标和流量趋势等原始非结构化输入时常常力不从心。这些限制影响了其在部分可观测和动态变化环境中的策略泛化和决策效率。为解决这一问题，我们提出了	extit{ORAN-GUIDE}，一个双大型语言模型（LLM）框架，通过任务相关的语义丰富状态表示来增强多智能体强化学习（MARL）。该架构采用了基于O-RAN控制和配置数据预训练的领域特定语言模型ORANSight，用于生成结构化的、上下文感知的提示。这些提示与可学习标记融合后，传递给一个冻结的基于GPT的编码器，生成高层次语义表示供DRL代理使用。这一设计采用了针对无线系统技术决策的检索增强生成（RAG）风格的流水线。实验结果表明，与标准MARL和单LLM基线相比，ORAN-GUIDE在样本效率、策略收敛和性能泛化方面均有显著提升。

> Advanced wireless networks must support highly dynamic and heterogeneous service demands. Open Radio Access Network (O-RAN) architecture enables this flexibility by adopting modular, disaggregated components, such as the RAN Intelligent Controller (RIC), Centralized Unit (CU), and Distributed Unit (DU), that can support intelligent control via machine learning (ML). While deep reinforcement learning (DRL) is a powerful tool for managing dynamic resource allocation and slicing, it often struggles to process raw, unstructured input like RF features, QoS metrics, and traffic trends. These limitations hinder policy generalization and decision efficiency in partially observable and evolving environments. To address this, we propose \textit{ORAN-GUIDE}, a dual-LLM framework that enhances multi-agent RL (MARL) with task-relevant, semantically enriched state representations. The architecture employs a domain-specific language model, ORANSight, pretrained on O-RAN control and configuration data, to generate structured, context-aware prompts. These prompts are fused with learnable tokens and passed to a frozen GPT-based encoder that outputs high-level semantic representations for DRL agents. This design adopts a retrieval-augmented generation (RAG) style pipeline tailored for technical decision-making in wireless systems. Experimental results show that ORAN-GUIDE improves sample efficiency, policy convergence, and performance generalization over standard MARL and single-LLM baselines.

[Arxiv](https://arxiv.org/abs/2506.00576)