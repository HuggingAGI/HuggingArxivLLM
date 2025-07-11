# KVFlow：加速基于LLM的多智能体工作流的高效前缀缓存方案

发布时间：2025年07月09日

`Agent` `智能体` `分布式计算`

> KVFlow: Efficient Prefix Caching for Accelerating LLM-Based Multi-Agent Workflows

# 摘要

> 基于大型语言模型（LLM）的智能体工作流已成为一种流行的范式，用于协调多个专业智能体解决复杂任务。现有的LLM系统通过前缀缓存技术复用与智能体固定提示对应的键值（KV）张量，从而避免重复调用中的冗余计算。然而，当前系统通常使用最近最少使用（LRU）策略来清除KV缓存，这种方法无法预测未来智能体的使用情况，常常在KV缓存即将被重用前将其丢弃，导致频繁的缓存缺失和大量的重新计算或交换开销。

我们提出了KVFlow，一个专为智能体负载设计的工作流感知的键值缓存管理框架。KVFlow将智能体执行计划抽象为智能体步骤图，并为每个智能体分配一个步骤到执行的值，以估计其在未来激活的时间邻近性。这些值指导KV节点级别的细粒度缓存替换策略，使KVFlow能够保留可能被重用的条目，并高效管理树状结构缓存中的共享前缀。此外，KVFlow引入了完全重叠的KV预取机制，该机制主动将所需张量从CPU加载到GPU的后台线程中，用于下一步计划的智能体，从而避免生成过程中的缓存缺失停滞。

与分层基数缓存的SGLang相比，KVFlow在处理大提示的单个工作流时，速度提升了1.83倍；在处理多个并发工作流的场景中，速度提升了2.19倍。

> Large language model (LLM) based agentic workflows have become a popular paradigm for coordinating multiple specialized agents to solve complex tasks. To improve serving efficiency, existing LLM systems employ prefix caching to reuse key-value (KV) tensors corresponding to agents' fixed prompts, thereby avoiding redundant computation across repeated invocations. However, current systems typically evict KV caches using a Least Recently Used (LRU) policy, which fails to anticipate future agent usage and often discards KV caches shortly before their reuse. This leads to frequent cache misses and substantial recomputation or swapping overhead. We present KVFlow, a workflow-aware KV cache management framework tailored for agentic workloads. KVFlow abstracts the agent execution schedule as an Agent Step Graph and assigns each agent a steps-to-execution value that estimates its temporal proximity to future activation. These values guide a fine-grained eviction policy at the KV node level, allowing KVFlow to preserve entries likely to be reused and efficiently manage shared prefixes in tree-structured caches. Moreover, KVFlow introduces a fully overlapped KV prefetching mechanism, which proactively loads required tensors from CPU to GPU in background threads for agents scheduled in the next step, thereby avoiding cache miss stalls during generation. Compared to SGLang with hierarchical radix cache, KVFlow achieves up to 1.83$\times$ speedup for single workflows with large prompts, and up to 2.19$\times$ speedup for scenarios with many concurrent workflows.

[Arxiv](https://arxiv.org/abs/2507.07400)