# # 利用 StateGraph 和 LLM 实现 Kubernetes 根本原因分析的简化

发布时间：2025年06月03日

`LLM应用` `云计算` `系统运维`

> Simplifying Root Cause Analysis in Kubernetes with StateGraph and LLM

# 摘要

> Kubernetes 是一个复杂且分布式的系统，通过控制器维护集群管理逻辑。然而，在动态云环境中，状态一致性面临诸多挑战，如故障和网络中断，导致运营中断和经济损失。为提升可靠性，我们亟需强大的根本原因分析（RCA）。大型语言模型（LLMs）为 RCA 提供了新方向，但现有方法面临事件多样性和复杂背景等挑战。本文介绍 SynergyRCA，一个结合图数据库和专家提示的创新工具。它构建 StateGraph 和 MetaGraph，捕获空间时间关系和实体连接。发生事件时，LLM 预测关键资源，SynergyRCA 查询图谱提供上下文见解。实验结果表明，SynergyRCA 在两分钟内以 0.90 的精度高效识别根本原因，包括新颖案例。

> Kubernetes, a notably complex and distributed system, utilizes an array of controllers to uphold cluster management logic through state reconciliation. Nevertheless, maintaining state consistency presents significant challenges due to unexpected failures, network disruptions, and asynchronous issues, especially within dynamic cloud environments. These challenges result in operational disruptions and economic losses, underscoring the necessity for robust root cause analysis (RCA) to enhance Kubernetes reliability. The development of large language models (LLMs) presents a promising direction for RCA. However, existing methodologies encounter several obstacles, including the diverse and evolving nature of Kubernetes incidents, the intricate context of incidents, and the polymorphic nature of these incidents. In this paper, we introduce SynergyRCA, an innovative tool that leverages LLMs with retrieval augmentation from graph databases and enhancement with expert prompts. SynergyRCA constructs a StateGraph to capture spatial and temporal relationships and utilizes a MetaGraph to outline entity connections. Upon the occurrence of an incident, an LLM predicts the most pertinent resource, and SynergyRCA queries the MetaGraph and StateGraph to deliver context-specific insights for RCA. We evaluate SynergyRCA using datasets from two production Kubernetes clusters, highlighting its capacity to identify numerous root causes, including novel ones, with high efficiency and precision. SynergyRCA demonstrates the ability to identify root causes in an average time of about two minutes and achieves an impressive precision of approximately 0.90.

[Arxiv](https://arxiv.org/abs/2506.02490)