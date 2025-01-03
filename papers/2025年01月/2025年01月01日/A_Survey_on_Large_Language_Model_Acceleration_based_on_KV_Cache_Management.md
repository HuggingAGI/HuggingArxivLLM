# 基于KV缓存管理的大型语言模型加速研究综述

发布时间：2025年01月01日

`LLM应用

**理由**：这篇论文主要讨论了大型语言模型（LLMs）在推理过程中的优化技术，特别是键值（KV）缓存管理的优化策略。这些优化策略旨在提高LLMs在现实世界应用中的效率和可扩展性。因此，这篇论文属于LLM应用类别，因为它关注的是如何将LLMs应用于实际场景中的技术改进和优化。` `计算机视觉`

> A Survey on Large Language Model Acceleration based on KV Cache Management

# 摘要

> # 摘要
大型语言模型（LLMs）凭借其强大的上下文理解和逻辑推理能力，彻底革新了自然语言处理、计算机视觉和多模态任务等领域。然而，LLMs在推理过程中的高计算和内存需求，给其在现实世界、长上下文和实时应用中的扩展带来了巨大挑战。键值（KV）缓存管理作为一种关键优化技术，通过减少冗余计算和提高内存利用率，显著加速了LLM推理。本文全面梳理了KV缓存管理的优化策略，将其分为令牌级、模型级和系统级优化。令牌级策略涵盖KV缓存选择、预算分配、合并、量化和低秩分解；模型级优化则聚焦于架构创新和注意力机制，以提升KV重用效率；系统级方法则通过内存管理、调度和硬件感知设计，提升不同计算环境下的效率。此外，本文还介绍了用于评估这些策略的文本和多模态数据集及基准测试。通过详细的分类和对比分析，本文旨在为研究人员和从业者提供有价值的见解，推动高效、可扩展的KV缓存管理技术的发展，助力LLMs在现实世界中的实际应用。KV缓存管理的精选论文列表位于：\href{https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management}{https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management}。

> Large Language Models (LLMs) have revolutionized a wide range of domains such as natural language processing, computer vision, and multi-modal tasks due to their ability to comprehend context and perform logical reasoning. However, the computational and memory demands of LLMs, particularly during inference, pose significant challenges when scaling them to real-world, long-context, and real-time applications. Key-Value (KV) cache management has emerged as a critical optimization technique for accelerating LLM inference by reducing redundant computations and improving memory utilization. This survey provides a comprehensive overview of KV cache management strategies for LLM acceleration, categorizing them into token-level, model-level, and system-level optimizations. Token-level strategies include KV cache selection, budget allocation, merging, quantization, and low-rank decomposition, while model-level optimizations focus on architectural innovations and attention mechanisms to enhance KV reuse. System-level approaches address memory management, scheduling, and hardware-aware designs to improve efficiency across diverse computing environments. Additionally, the survey provides an overview of both text and multimodal datasets and benchmarks used to evaluate these strategies. By presenting detailed taxonomies and comparative analyses, this work aims to offer useful insights for researchers and practitioners to support the development of efficient and scalable KV cache management techniques, contributing to the practical deployment of LLMs in real-world applications. The curated paper list for KV cache management is in: \href{https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management}{https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management}.

[Arxiv](https://arxiv.org/abs/2412.19442)