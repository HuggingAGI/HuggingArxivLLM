# ALAS：用于干扰感知规划的有状态多LLM代理框架

发布时间：2025年05月18日

`Agent` `工业制造` `调度规划`

> ALAS: A Stateful Multi-LLM Agent Framework for Disruption-Aware Planning

# 摘要

> 大型语言模型（LLMs）在生成文本和多模态内容方面表现出色，但在需要ACID特性保证和实时故障恢复的事务型规划任务上表现欠佳。为此，我们提出了自适应LLM代理系统（ALAS），该框架针对LLMs的四大核心缺陷进行改进：（i）缺乏自我验证，（ii）上下文侵蚀，（iii）下一词近视，（iv）缺乏持久状态。ALAS通过将每个计划分解为角色专用的代理，为它们配备自动状态跟踪，并通过轻量级协议进行协调。当出现中断时，代理会应用基于历史的局部补偿，避免代价高昂的全局重新规划，从而控制级联效应。在真实世界、大规模的作业车间调度基准测试中，ALAS在静态顺序规划中取得了新的最佳结果，并在存在意外中断的动态响应场景中表现出色。这些成果表明，通过模块化设计结合针对性补偿，可以利用LLMs实现可扩展且具备韧性的规划能力。

> Large language models (LLMs) excel at rapid generation of text and multimodal content, yet they falter on transaction-style planning that demands ACID-like guarantees and real-time disruption recovery. We present Adaptive LLM Agent System (ALAS), a framework that tackles four fundamental LLM deficits: (i) absence of self-verification, (ii) context erosion, (iii) next-token myopia, and (iv) lack of persistent state. ALAS decomposes each plan into role-specialized agents, equips them with automatic state tracking, and coordinates them through a lightweight protocol. When disruptions arise, agents apply history-aware local compensation, avoiding costly global replanning and containing cascade effects. On real-world, large-scale job-shop scheduling benchmarks, ALAS sets new best results for static sequential planning and excels in dynamic reactive scenarios with unexpected disruptions. These gains show that principled modularization plus targeted compensation can unlock scalable and resilient planning with LLMs.

[Arxiv](https://arxiv.org/abs/2505.12501)