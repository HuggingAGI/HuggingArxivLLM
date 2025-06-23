# LazyEviction：通过观察注意力模式实现延迟键值驱逐，提升长推理效率

发布时间：2025年06月18日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在推理任务中的内存使用问题，并提出了一种新的优化框架LazyEviction。研究的重点在于理解模型内部的工作机制，特别是Token重要性循环现象，以及如何通过优化缓存策略来提高模型的推理效率和性能。这些内容属于对LLM本身的理论和机制的研究，因此归类到“LLM理论”类别中。` `模型优化` `人工智能`

> LazyEviction: Lagged KV Eviction with Attention Pattern Observation for Efficient Long Reasoning

# 摘要

> 大型语言模型（LLMs）通过思维链（CoT）方法展现了增强的推理能力，但这种能力的提升也带来了显著的GPU内存负担，尤其是在数学和编程等需要长推理序列的任务中。现有KV缓存压缩方法虽能缓解内存瓶颈，但在长推理任务中表现不佳。我们通过对推理任务注意力模式的分析，揭示了Token重要性循环现象：大量Token在多次解码后重新获得关注，这一现象未被现有方法捕捉，可能导致关键Token被不可预测地驱逐。为解决这一问题，我们提出了LazyEviction框架，通过延迟驱逐策略在减少KV内存的同时保持推理性能。LazyEviction包含两个关键组件：（1）循环间隔追踪，用于捕捉Token重要性的时序变化；（2）基于最大循环间隔的驱逐策略，根据Token循环模式优先驱逐。实验表明，LazyEviction在数学推理任务中将KV缓存规模减少50%，同时保持可比准确性，优于现有方法。我们的研究强调了保留循环Token的重要性，这些Token对维护多步推理任务的知识连续性至关重要。

> Large Language Models (LLMs) exhibit enhanced reasoning capabilities by employing Chain-of-Thought (CoT). However, the extended reasoning sequences introduce significant GPU memory overhead due to increased key-value (KV) cache size, particularly in tasks requiring long reasoning sequences, such as mathematics and programming. Existing KV cache compression methods mitigate memory bottlenecks but struggle in long reasoning tasks. In this paper, we analyze attention patterns in reasoning tasks and reveal a Token Importance Recurrence phenomenon: a large proportion of tokens receive renewed attention after multiple decoding steps, which is failed to capture by existing works and may lead to unpredictable eviction on such periodically critical tokens. To address this, we propose LazyEviction, a lagged KV eviction framework designed to maintain reasoning performance while reducing KV memory. LazyEviction is an Observation Window-based Lagged Eviction Mechanism retaining latent recurring tokens by performing lagged evictions across decoding steps, which contains two key components: (1) Recurrence Interval Tracking for capturing temporal variations in token importance, and (2) an Maximum Recurrence Interval-Centric Eviction Policy that prioritizes eviction based on tokens' recurrence patterns. Extensive experiments demonstrate that LazyEviction reduces KV cache size by 50% while maintaining comparable accuracy on mathematics reasoning datasets, outperforming state-of-the-art methods. Our findings highlight the importance of preserving recurring tokens, which are critical for maintaining knowledge continuity in multi-step reasoning tasks.

[Arxiv](https://arxiv.org/abs/2506.15969)