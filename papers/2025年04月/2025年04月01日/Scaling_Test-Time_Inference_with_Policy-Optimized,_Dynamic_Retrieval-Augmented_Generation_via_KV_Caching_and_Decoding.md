# # 研究标题  
基于策略优化的动态检索增强生成，通过 KV 缓存与解码扩展测试时推理能力

发布时间：2025年04月01日

`RAG` `知识密集型任务` `问答系统`

> Scaling Test-Time Inference with Policy-Optimized, Dynamic Retrieval-Augmented Generation via KV Caching and Decoding

# 摘要

> 我们提出了一套全新的框架，通过动态检索策略与强化微调技术，全面升级检索增强生成（RAG）系统。该方案显著提升了大型语言模型在知识密集型任务中的表现，涵盖开放领域问答与复杂推理等场景。框架巧妙融合两大核心技术：基于策略优化的增强生成（PORAG），专注于优化检索信息的运用；以及自适应令牌层注意力评分（ATLAS），可根据上下文需求动态调整检索时机与内容。两者相辅相成，不仅提升了检索内容的利用率，更确保了其相关性，从而显著改善了事实准确性与响应质量。

这套框架作为轻量级解决方案，与任何基于Transformer的大型语言模型无缝兼容，无需额外训练即可投入使用。在知识密集型任务中，它展现了卓越的性能，显著提升了RAG场景下的输出准确性。我们还创新性地提出了CRITIC方法，通过令牌重要性评估实现键值缓存的选择性压缩，有效缓解了长上下文应用中的内存瓶颈。框架内置的推理时缩放技术，能够动态平衡推理深度与计算资源，配合优化的解码策略，进一步提升了推理速度。

实验结果表明，与传统RAG系统相比，我们的框架在基准数据集上实现了三大突破：显著减少了幻觉现象，大幅增强了领域特定推理能力，同时在效率与可扩展性方面取得了显著提升。这一集成方案为打造更稳健、更高效、更具扩展性的RAG系统开辟了全新道路，为多领域应用注入了强大动力。

> We present a comprehensive framework for enhancing Retrieval-Augmented Generation (RAG) systems through dynamic retrieval strategies and reinforcement fine-tuning. This approach significantly improves large language models on knowledge-intensive tasks, including opendomain question answering and complex reasoning. Our framework integrates two complementary techniques: Policy-Optimized RetrievalAugmented Generation (PORAG), which optimizes the use of retrieved information, and Adaptive Token-Layer Attention Scoring (ATLAS), which dynamically determines retrieval timing and content based on contextual needs. Together, these techniques enhance both the utilization and relevance of retrieved content, improving factual accuracy and response quality. Designed as a lightweight solution compatible with any Transformer-based LLM without requiring additional training, our framework excels in knowledge-intensive tasks, boosting output accuracy in RAG settings. We further propose CRITIC, a novel method to selectively compress key-value caches by token importance, mitigating memory bottlenecks in long-context applications. The framework also incorporates test-time scaling techniques to dynamically balance reasoning depth and computational resources, alongside optimized decoding strategies for faster inference. Experiments on benchmark datasets show that our framework reduces hallucinations, strengthens domain-specific reasoning, and achieves significant efficiency and scalability gains over traditional RAG systems. This integrated approach advances the development of robust, efficient, and scalable RAG systems across diverse applications.

[Arxiv](https://arxiv.org/abs/2504.01281)