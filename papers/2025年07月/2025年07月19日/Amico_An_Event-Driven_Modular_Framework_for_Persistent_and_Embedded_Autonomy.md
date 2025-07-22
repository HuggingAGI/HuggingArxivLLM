# Amico：一个事件驱动、模块化的持久嵌入式自主性框架

发布时间：2025年07月19日

`Agent` `嵌入式系统` `Web开发`

> Amico: An Event-Driven Modular Framework for Persistent and Embedded Autonomy

# 摘要

> 大型语言模型 (LLMs) 和自主代理的最新进展使跨领域复杂任务的实现成为可能，涵盖人机交互、规划和网络导航等多个领域。然而，现有框架在现实或资源受限环境中表现欠佳，主要归因于对云计算的依赖、动态环境下的鲁棒性不足，以及缺乏持续自主性和环境感知能力。我们推出 Amico，一个专为嵌入式系统优化的模块化、事件驱动框架，用于构建自主代理。Amico 采用 Rust 编写，兼顾安全与性能，支持反应式、持久化代理在嵌入式平台及通过 WebAssembly 的浏览器环境中高效运行。它提供了事件处理、状态管理、行为执行以及与推理模块集成的清晰抽象。Amico 构建了一个统一的基础设施，助力打造健壮、交互式的代理，尤其适用于计算资源有限和网络连接不稳定的环境。

> Recent advances in large language models (LLMs) and autonomous agents have enabled systems capable of performing complex tasks across domains such as human-computer interaction, planning, and web navigation. However, many existing frameworks struggle in real-world or resource-constrained environments due to their reliance on cloud-based computation, limited robustness in dynamic contexts, and lack of persistent autonomy and environmental awareness.
  We present Amico, a modular, event-driven framework for building autonomous agents optimized for embedded systems. Written in Rust for safety and performance, Amico supports reactive, persistent agents that operate efficiently across embedded platforms and browser environments via WebAssembly. It provides clean abstractions for event handling, state management, behavior execution, and integration with reasoning modules. Amico delivers a unified infrastructure for constructing resilient, interactive agents suitable for deployment in settings with limited compute and intermittent connectivity.

[Arxiv](https://arxiv.org/abs/2507.14513)