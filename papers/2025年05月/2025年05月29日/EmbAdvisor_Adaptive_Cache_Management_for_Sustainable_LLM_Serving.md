# EmbAdvisor：可持续大语言模型服务的自适应缓存管理方案

发布时间：2025年05月29日

`LLM应用`

> EmbAdvisor: Adaptive Cache Management for Sustainable LLM Serving

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，它们对环境的影响$unicode{x2014}$特别是碳排放$unicode{x2014}$日益受到关注。以往研究主要聚焦于计算相关的碳排放，而我们在本文中发现，存储同样是碳排放的重要来源。LLM缓存通过保存并复用重复上下文的KV缓存，减少了因避免冗余计算而产生的运营碳排放。然而，这一优势是以高容量、高速SSD的 embodied carbon 为代价的。随着LLMs规模的扩大，存储的 embodied carbon 显著增加。
  为了解决这一权衡，我们提出了EmbAdvisor，这是一个碳感知的缓存框架，用于选择LLM服务的最优缓存大小。EmbAdvisor分析不同的LLM任务，并使用整数线性规划（ILP）求解器选择既能满足服务级别目标（SLOs）又能最小化总碳排放的缓存大小。总体而言，与非自适应缓存场景相比，EmbAdvisor将Llama-3 70B模型在各种碳强度下的平均碳排放降低了9.5%，并且在碳强度较低时可节省高达31.2%的碳排放。

> As large language models (LLMs) become widely used, their environmental impact$\unicode{x2014}$especially carbon emissions$\unicode{x2014}$has attracted more attention. Prior studies focus on compute-related carbon emissions. In this paper, we find that storage is another key contributor. LLM caching, which saves and reuses KV caches for repeated context, reduces operational carbon by avoiding redundant computation. However, this benefit comes at the cost of embodied carbon from high-capacity, high-speed SSDs. As LLMs scale, the embodied carbon of storage grows significantly.
  To address this tradeoff, we present EmbAdvisor, a carbon-aware caching framework that selects the optimal cache size for LLM serving. EmbAdvisor profiles different LLM tasks and uses an Integer Linear Programming (ILP) solver to select cache sizes that meet SLOs while minimizing total carbon emissions. Overall, EmbAdvisor reduces the average carbon emissions of a Llama-3 70B model by 9.5% under various carbon intensities compared to a non-adaptive cache scenario, and can save up to 31.2% when the carbon intensity is low.

[Arxiv](https://arxiv.org/abs/2505.23970)