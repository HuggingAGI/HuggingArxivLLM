# FlowKV：通过独立键值缓存管理提升LLM多轮对话连贯性

发布时间：2025年05月21日

`LLM应用` `对话系统`

> FlowKV: Enhancing Multi-Turn Conversational Coherence in LLMs via Isolated Key-Value Cache Management

# 摘要

> 大型语言模型（LLMs）在多轮对话应用中的部署日益广泛，但KV缓存管理成为性能瓶颈。现有方法通过反复压缩早期对话上下文，导致信息丢失和上下文遗忘。本文提出了一种无需训练的新型	extbf{多轮隔离机制}FlowKV，可与任何KV缓存压缩方法结合使用。FlowKV的核心创新是保留历史轮次的压缩缓存，并仅对最新一轮生成的新KV对进行压缩，有效避免旧上下文的重复压缩，显著缓解灾难性遗忘。实验表明，FlowKV在指令遵循准确性和用户偏好保留方面优于现有方法，提升幅度达10.90\%到75.40\%，尤其在对话后期表现突出。

> Large Language Models (LLMs) are increasingly deployed in multi-turn conversational applications, where the management of the Key-Value (KV) Cache presents a significant bottleneck. The linear growth of the KV Cache with dialogue history imposes substantial computational costs, and existing eviction strategies often degrade performance by repeatedly compressing early conversational context, leading to information loss and context forgetting. This paper introduces FlowKV, a novel \textbf{multi-turn isolation mechanism} for KV Cache management, which can be applied to any KV Cache compression method without training. FlowKV's core innovation is a multi-turn isolation mechanism that preserves the accumulated compressed KV cache from past turns. Compression is then strategically applied only to the newly generated KV pairs of the latest completed turn, effectively preventing the re-compression of older context and thereby mitigating catastrophic forgetting. Our results demonstrate that FlowKV consistently and significantly outperforms baseline strategies in maintaining instruction-following accuracy and user preference retention from 10.90\% to 75.40\%, particularly in later conversational turns.

[Arxiv](https://arxiv.org/abs/2505.15347)