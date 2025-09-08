# VoltanaLLM：反馈驱动频率控制与状态空间路由——助力LLM高效节能服务

发布时间：2025年09月05日

`LLM应用` `能源与环保`

> VoltanaLLM: Feedback-Driven Frequency Control and State-Space Routing for Energy-Efficient LLM Serving

# 摘要

> 如今，大型语言模型（LLM）服务系统日益支持各类交互式应用，例如实时聊天助手、代码生成工具和智能体工作流。但LLM推理的能源成本急剧攀升，给可持续且经济高效的部署带来了越来越大的挑战。本文提出了VoltanaLLM——一个从控制理论角度构建的SLO感知型高能效LLM服务系统。该系统在新兴的预填充/解码分离架构中协同设计频率缩放与请求路由机制，借助架构的解耦执行特性实现细粒度的阶段化控制。其核心包含两部分：一是反馈驱动的频率控制器，可为预填充和解码阶段动态调整GPU频率；二是状态空间路由器，能够在频率缩放的实例间探索路由策略，从而在满足延迟约束的前提下最小化能耗。我们在SGLang中实现了VoltanaLLM，并在多个最先进的LLM和真实世界数据集上对其性能进行了评估。结果显示，VoltanaLLM在保持近乎完美的SLO达标率的同时，实现了高达36.3%的能耗降低，为可持续且智能的LLM服务奠定了基础。

> Modern Large Language Model (LLM) serving systems increasingly support interactive applications, like real-time chat assistants, code generation tools, and agentic workflows. However, the soaring energy cost of LLM inference presents a growing challenge for sustainable and cost-effective deployment. This paper introduces VoltanaLLM, a system for SLO-aware, energy-efficient LLM serving, built from a control theory perspective. VoltanaLLM co-designs frequency scaling and request routing in emerging prefill/decode disaggregated architectures, leveraging their decoupled execution to enable fine-grained phase-specific control. It consists of a feedback-driven frequency controller that dynamically adapts GPU frequency for prefill and decode phases, and a state-space router that explores routing decisions across frequency-scaled instances to minimize energy under latency constraints. We implement VoltanaLLM in SGLang and evaluate its performance over multiple state-of-the-art LLMs and real-world datasets. The results demonstrate that VoltanaLLM achieves up to 36.3% energy savings while maintaining near-perfect SLO attainment rate, paving the way for sustainable and intelligent LLM serving.

[Arxiv](https://arxiv.org/abs/2509.04827)