# 基于异构系统的高效可扩展智能体AI

发布时间：2025年07月25日

`Agent

理由：这篇论文主要探讨了AI代理的工作负载特性以及在异构计算基础设施上的动态编排系统设计，属于AI代理领域的研究。` `云计算` `系统架构`

> Efficient and Scalable Agentic AI with Heterogeneous Systems

# 摘要

> AI代理正在成为各类应用中的主导型工作负载，有望成为兑现AI为企业和消费者承诺的核心载体。与传统软件或静态推理不同，代理型工作负载呈现出动态特性且结构复杂。通常这些代理由计算和IO操作构成的有向图组成，涵盖多模态数据输入与转换、数据处理和上下文收集（如向量数据库查找）、多次LLM推理、工具调用等环节。

为应对这一挑战，本文提出了一种在异构计算基础设施上动态编排AI代理工作负载的系统设计，该基础设施涵盖来自不同供应商以及单一供应商内部不同性能层级的CPU和加速器。该系统提供了三个核心构建模块：

1. 一个基于成本模型的框架，用于规划和优化代理型AI执行图，这些成本模型考虑了不同硬件的计算、内存和带宽限制；
2. 一个基于MLIR的表示和编译系统，可以将AI代理执行图分解为细粒度的操作，并为不同硬件选项生成代码；
3. 一个动态编排系统，可以在异构计算基础设施上放置这些细粒度组件，并在满足端到端SLA的同时将它们连接起来。

我们的设计进行了系统级TCO优化，初步结果显示利用异构基础设施可以带来显著的TCO优势。一个初步的惊人发现是，对于某些工作负载，将旧一代GPU与新加速器组合使用可以达到与最新一代同构GPU基础设施设计相当的TCO，这可能延长已部署基础设施的使用寿命。

> AI agents are emerging as a dominant workload in a wide range of applications, promising to be the vehicle that delivers the promised benefits of AI to enterprises and consumers. Unlike conventional software or static inference, agentic workloads are dynamic and structurally complex. Often these agents are directed graphs of compute and IO operations that span multi-modal data input and conversion), data processing and context gathering (e.g vector DB lookups), multiple LLM inferences, tool calls, etc. To scale AI agent usage, we need efficient and scalable deployment and agent-serving infrastructure.
  To tackle this challenge, in this paper, we present a system design for dynamic orchestration of AI agent workloads on heterogeneous compute infrastructure spanning CPUs and accelerators, both from different vendors and across different performance tiers within a single vendor. The system delivers several building blocks: a framework for planning and optimizing agentic AI execution graphs using cost models that account for compute, memory, and bandwidth constraints of different HW; a MLIR based representation and compilation system that can decompose AI agent execution graphs into granular operators and generate code for different HW options; and a dynamic orchestration system that can place the granular components across a heterogeneous compute infrastructure and stitch them together while meeting an end-to-end SLA. Our design performs a systems level TCO optimization and preliminary results show that leveraging a heterogeneous infrastructure can deliver significant TCO benefits. A preliminary surprising finding is that for some workloads a heterogeneous combination of older generation GPUs with newer accelerators can deliver similar TCO as the latest generation homogenous GPU infrastructure design, potentially extending the life of deployed infrastructure.

[Arxiv](https://arxiv.org/abs/2507.19635)