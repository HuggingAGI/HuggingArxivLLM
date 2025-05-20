# ALAS：面向干扰的规划的有状态多LLM智能体框架

发布时间：2025年05月18日

`LLM应用` `制造业` `工业自动化`

> ALAS: A Stateful Multi-LLM Agent Framework for Disruption-Aware Planning

# 摘要

> 大型语言模型（LLMs）擅长快速生成文本和多模态内容，但在需要ACID-like保证和实时故障恢复的事务型规划任务上表现欠佳。我们推出自适应LLM代理系统（ALAS），这一框架针对LLM的四大根本缺陷：（i）缺乏自我验证，（ii）上下文侵蚀，（iii）下一个词预测短视，（iv）缺乏持久状态。ALAS通过将每个计划分解为角色专用代理，配备自动状态跟踪，并通过轻量级协议进行协调。当出现中断时，代理应用历史感知的局部补偿机制，避免昂贵的全局重新规划并有效控制级联效应。在真实世界的大规模作业车间调度基准测试中，ALAS不仅为静态顺序规划设定了新最佳结果，还在存在意外中断的动态响应场景中表现出色。这些成果表明，基于原理的模块化设计加上有针对性的补偿机制能够解锁使用LLMs实现的可扩展且有韧性的规划能力。

> Large language models (LLMs) excel at rapid generation of text and multimodal content, yet they falter on transaction-style planning that demands ACID-like guarantees and real-time disruption recovery. We present Adaptive LLM Agent System (ALAS), a framework that tackles four fundamental LLM deficits: (i) absence of self-verification, (ii) context erosion, (iii) next-token myopia, and (iv) lack of persistent state. ALAS decomposes each plan into role-specialized agents, equips them with automatic state tracking, and coordinates them through a lightweight protocol. When disruptions arise, agents apply history-aware local compensation, avoiding costly global replanning and containing cascade effects. On real-world, large-scale job-shop scheduling benchmarks, ALAS sets new best results for static sequential planning and excels in dynamic reactive scenarios with unexpected disruptions. These gains show that principled modularization plus targeted compensation can unlock scalable and resilient planning with LLMs.

[Arxiv](https://arxiv.org/abs/2505.12501)