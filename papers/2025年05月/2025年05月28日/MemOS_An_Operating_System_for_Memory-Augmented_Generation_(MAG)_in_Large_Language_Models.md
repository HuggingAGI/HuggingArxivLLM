# MemOS: 面向大型语言模型的内存增强生成 (MAG) 操作系统

发布时间：2025年05月28日

`LLM应用` `人工智能` `内存管理`

> MemOS: An Operating System for Memory-Augmented Generation (MAG) in Large Language Models

# 摘要

> 大型语言模型（LLMs）在通用人工智能（AGI）追求中扮演了基础性角色。尽管在语言处理方面表现出色，但现有LLMs缺乏统一的内存架构，主要依赖参数记忆和短暂激活记忆。新兴方法如RAG虽引入明文记忆，但缺乏管理和整合能力。为此，我们推出MemOS——首个为LLMs设计的内存操作系统，首次将内存提升为关键资源。MemOS统一了三种核心内存的处理机制，并以MemCube为核心，实现异构内存的追踪与融合。它构建了一个以内存为中心的智能框架，填补了现有LLM基础设施的空白，为下一代智能系统奠定了基础。


> Large Language Models (LLMs) have emerged as foundational infrastructure in the pursuit of Artificial General Intelligence (AGI). Despite their remarkable capabilities in language perception and generation, current LLMs fundamentally lack a unified and structured architecture for handling memory. They primarily rely on parametric memory (knowledge encoded in model weights) and ephemeral activation memory (context-limited runtime states). While emerging methods like Retrieval-Augmented Generation (RAG) incorporate plaintext memory, they lack lifecycle management and multi-modal integration, limiting their capacity for long-term knowledge evolution. To address this, we introduce MemOS, a memory operating system designed for LLMs that, for the first time, elevates memory to a first-class operational resource. It builds unified mechanisms for representation, organization, and governance across three core memory types: parametric, activation, and plaintext. At its core is the MemCube, a standardized memory abstraction that enables tracking, fusion, and migration of heterogeneous memory, while offering structured, traceable access across tasks and contexts. MemOS establishes a memory-centric execution framework with strong controllability, adaptability, and evolvability. It fills a critical gap in current LLM infrastructure and lays the groundwork for continual adaptation, personalized intelligence, and cross-platform coordination in next-generation intelligent systems.

[Arxiv](https://arxiv.org/abs/2505.22101)