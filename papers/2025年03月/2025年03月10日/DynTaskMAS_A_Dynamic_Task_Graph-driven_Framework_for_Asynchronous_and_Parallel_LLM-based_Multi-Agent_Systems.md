# DynTaskMAS：基于LLM的异步并行多智能体系统动态任务图驱动框架

发布时间：2025年03月10日

`Agent` `人工智能` `分布式系统`

> DynTaskMAS: A Dynamic Task Graph-driven Framework for Asynchronous and Parallel LLM-based Multi-Agent Systems

# 摘要

> 大型语言模型（LLMs）在多智能体系统（MAS）中的出现为人工智能带来了新的可能性，但现有实现仍面临资源管理、任务协调和系统效率上的挑战。尽管现有框架展示了基于LLM的代理在协作问题解决中的潜力，但它们往往缺乏并行执行和动态任务管理的复杂机制。本文介绍的DynTaskMAS是一个创新框架，通过动态任务图编排基于LLM的MAS的异步和并行操作。该框架的四大创新包括：智能分解任务的动态任务图生成器、优化资源利用的异步并行执行引擎、促进信息共享的语义感知上下文管理系统，以及动态优化性能的自适应工作流管理器。实验结果表明，与传统方法相比，DynTaskMAS在执行时间、资源利用率和吞吐量扩展方面均取得显著提升。这一框架为构建高效处理复杂动态任务的可扩展、高性能基于LLM的多智能体系统奠定了基础。

> The emergence of Large Language Models (LLMs) in Multi-Agent Systems (MAS) has opened new possibilities for artificial intelligence, yet current implementations face significant challenges in resource management, task coordination, and system efficiency. While existing frameworks demonstrate the potential of LLM-based agents in collaborative problem-solving, they often lack sophisticated mechanisms for parallel execution and dynamic task management. This paper introduces DynTaskMAS, a novel framework that orchestrates asynchronous and parallel operations in LLM-based MAS through dynamic task graphs. The framework features four key innovations: (1) a Dynamic Task Graph Generator that intelligently decomposes complex tasks while maintaining logical dependencies, (2) an Asynchronous Parallel Execution Engine that optimizes resource utilization through efficient task scheduling, (3) a Semantic-Aware Context Management System that enables efficient information sharing among agents, and (4) an Adaptive Workflow Manager that dynamically optimizes system performance. Experimental evaluations demonstrate that DynTaskMAS achieves significant improvements over traditional approaches: a 21-33% reduction in execution time across task complexities (with higher gains for more complex tasks), a 35.4% improvement in resource utilization (from 65% to 88%), and near-linear throughput scaling up to 16 concurrent agents (3.47X improvement for 4X agents). Our framework establishes a foundation for building scalable, high-performance LLM-based multi-agent systems capable of handling complex, dynamic tasks efficiently.

[Arxiv](https://arxiv.org/abs/2503.07675)