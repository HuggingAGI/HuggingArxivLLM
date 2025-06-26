# PaceLLM: 基于大脑启发的大型语言模型，专为长上下文理解而设计

发布时间：2025年06月18日

`LLM理论` `人工智能`

> PaceLLM: Brain-Inspired Large Language Models for Long-Context Understanding

# 摘要

> 尽管大型语言模型（LLMs）在各领域表现出色，但其长上下文能力受限于瞬时神经激活导致的信息衰减，以及无结构前馈网络（FFN）权重引发的语义碎片化。受大脑工作记忆和皮层模块化的启发，我们提出了PaceLLM，该模型具有两大创新点：（1）通过引入激活水平记忆库，模拟前额叶皮层（PFC）神经元的持续放电，动态检索、复用和更新关键FFN状态，以解决上下文衰减问题；（2）通过任务自适应神经特化，将FFN权重重组为语义模块，建立跨标记依赖关系，缓解碎片化问题。大量评估表明，PaceLLM在LongBench的多文档问答任务中提升了6%的性能，在Infinite-Bench任务中实现了12.5-17.5%的性能提升，同时在针在稻草堆（NIAH）测试中将可测量上下文长度扩展至200K标记。这项研究开创了基于大脑启发的LLM优化，并与现有研究相辅相成。此外，PaceLLM还可推广至任何模型，无需结构大改即可提升其长上下文性能和可解释性。

> While Large Language Models (LLMs) demonstrate strong performance across domains, their long-context capabilities are limited by transient neural activations causing information decay and unstructured feed-forward network (FFN) weights leading to semantic fragmentation. Inspired by the brain's working memory and cortical modularity, we propose PaceLLM, featuring two innovations: (1) a Persistent Activity (PA) Mechanism that mimics prefrontal cortex (PFC) neurons' persistent firing by introducing an activation-level memory bank to dynamically retrieve, reuse, and update critical FFN states, addressing contextual decay; and (2) Cortical Expert (CE) Clustering that emulates task-adaptive neural specialization to reorganize FFN weights into semantic modules, establishing cross-token dependencies and mitigating fragmentation. Extensive evaluations show that PaceLLM achieves 6% improvement on LongBench's Multi-document QA and 12.5-17.5% performance gains on Infinite-Bench tasks, while extending measurable context length to 200K tokens in Needle-In-A-Haystack (NIAH) tests. This work pioneers brain-inspired LLM optimization and is complementary to other works. Besides, it can be generalized to any model and enhance their long-context performance and interpretability without structural overhauls.

[Arxiv](https://arxiv.org/abs/2506.17310)