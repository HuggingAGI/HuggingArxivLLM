# M3LLM: 基于模型上下文协议的视觉专家混合模型，实现网络中多模态大语言模型的优化

发布时间：2025年08月03日

`LLM应用` `无线网络` `分布式计算`

> M3LLM: Model Context Protocol-aided Mixture of Vision Experts For Multimodal LLMs in Networks

# 摘要

> 现有的多模态大语言模型（MLLMs）采用集中式架构，常因输入任务与固定视觉编码模块的对齐问题而影响在多样化动态视觉任务中的表现。随着无线网络中资源高效模型向边缘设备的部署，我们提出了一种新方法：动态利用分布式视觉专家提升MLLM推理质量。为此，我们开发了M3LLM，其中模型上下文协议（MCP）协调多种视觉专家实现分布式推理。MCP是一个开放协议，将任务上下文转化为可解释的表示形式，使中心模型主干与边缘视觉专家能在无线网络环境下协同工作。基于MCP表示，M3LLM将视觉专家路由定义为平衡任务-专家语义匹配与信道性能的联合优化问题。为解决梯度冲突，我们提出了双流软演员-评论家（SAC）算法，采用解耦奖励信号，并结合分层贝叶斯建模的自适应稳定性增强模块（ASEM），确保有效路由。实验结果表明，M3LLM在动态无线网络条件下显著提升了任务准确性，降低了通信成本，并增强了专家路由的适应性。

> Current Multimodal Large Language Models (MLLMs) rely on centralized architectures and often suffer from poor alignment between the input task and their fixed visual encoding modules, which limits performance on diverse and dynamic visual tasks. With the increasing deployment of resource-efficient models on edge devices in wireless networks, a new opportunity emerges to dynamically use distributed vision experts for improved MLLM inference quality. To enable this, we propose M3LLM, where the Model Context Protocol (MCP) coordinates a mixture of vision experts to achieve distributed MLLMs. Specifically, MCP is an open protocol that structures the input task context into interpretable representations, enabling wireless network-aware coordination between the central model backbone and edge-hosted vision experts. Based on the MCP representation, M3LLM formulates vision expert routing as a joint optimization problem that balances task-expert semantic compatibility and channel performance. To solve the resulting gradient conflicts, we develop a dual-stream Soft Actor-Critic (SAC) algorithm with decoupled reward signals and introduce an Adaptive Stability Enhancement Module (ASEM) based on hierarchical Bayesian modeling to ensure effective routing. Experiments show that M3LLM improves task accuracy, reduces communication cost, and enhances expert routing adaptability under dynamic wireless network conditions.

[Arxiv](https://arxiv.org/abs/2508.01805)