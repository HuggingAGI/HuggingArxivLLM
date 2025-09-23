# Asteria：面向智能体LLM工具访问的语义感知跨区域缓存

发布时间：2025年09月22日

`Agent` `基础理论`

> Asteria: Semantic-Aware Cross-Region Caching for Agentic LLM Tool Access

# 摘要

> 大型语言模型（LLM）智能体擅长处理深度研究、代码生成等数据密集型任务，但它们的效能依赖于与远程云或跨区域知识源的频繁交互，这会带来显著的延迟和成本瓶颈。现有缓存方案仅支持精确匹配查询，难以实现语义层面的知识复用。
  为此，我们提出Asteria——一种面向LLM智能体的新型跨区域知识缓存架构。其核心包含两个创新抽象：语义元素（SE）与语义检索索引（Sine）。语义元素不仅记录LLM查询的语义嵌入表示，还包含延迟、成本、静态性等性能感知元数据；Sine则实现两阶段检索：首先通过语义嵌入的向量相似性索引快速筛选候选结果，再借助轻量级LLM驱动的语义判断器进行精准验证。基于这些组件，Asteria构建了全新的缓存接口，涵盖语义感知的缓存命中定义、成本优化的驱逐策略及主动预取机制。为降低开销，Asteria通过自适应调度与资源共享，将小型LLM判断器与主LLM部署在同一位置。
  实验评估表明，Asteria在确保结果准确性的同时，实现了显著的性能提升：在典型搜索任务中，其缓存命中率超过85%，吞吐量提升高达【数学公式】，且准确性与无缓存基线几乎一致；在复杂编码任务中，吞吐量也提升了20%，充分体现其在各类智能体任务中的普适性。

> Large Language Model (LLM) agents tackle data-intensive tasks such as deep research and code generation. However, their effectiveness depends on frequent interactions with knowledge sources across remote clouds or regions. Such interactions can create non-trivial latency and cost bottlenecks. Existing caching solutions focus on exact-match queries, limiting their effectiveness for semantic knowledge reuse.
  To address this challenge, we introduce Asteria, a novel cross-region knowledge caching architecture for LLM agents. At its core are two abstractions: Semantic Element (SE) and Semantic Retrieval Index (Sine). A semantic element captures the semantic embedding representation of an LLM query together with performance-aware metadata such as latency, cost, and staticity. Sine then provides two-stage retrieval: a vector similar index with semantic embedding for fast candidate selection and a lightweight LLM-powered semantic judger for precise validation. Atop these primitives, Asteria builds a new cache interface that includes a new semantic-aware cache hit definition, a cost-efficient eviction policy, and proactive prefetching. To reduce overhead, Asteria co-locates the small LLM judger with the main LLM using adaptive scheduling and resource sharing. Our evaluation demonstrates that Asteria delivers substantial performance improvements without compromising correctness. On representative search workloads, Asteria achieves up to a 3.6$\times$ increase in throughput by maintaining cache hit rates of over 85%, while preserving accuracy virtually identical to non-cached baselines. Asteria also improves throughput for complex coding tasks by 20%, showcasing its versatility across diverse agentic workloads.

[Arxiv](https://arxiv.org/abs/2509.17360)