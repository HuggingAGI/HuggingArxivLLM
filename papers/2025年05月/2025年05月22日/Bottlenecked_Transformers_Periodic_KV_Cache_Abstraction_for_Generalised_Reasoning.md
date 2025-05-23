# 瓶颈型变压器：通用推理的周期性KV缓存抽象

发布时间：2025年05月22日

`LLM理论

这篇论文深入探讨了大型语言模型的泛化能力，从信息瓶颈理论出发，分析了模型的内在机制和局限性，并提出了一种创新的架构改进方案。研究集中在模型的理论分析和优化方法上，属于LLM理论范畴。` `大型语言模型` `Transformer架构`

> Bottlenecked Transformers: Periodic KV Cache Abstraction for Generalised Reasoning

# 摘要

> 大型语言模型尽管能力出众，但其泛化能力受限，往往擅长模式插值而非真正意义上的抽象推理。我们从信息瓶颈理论出发，揭示了模型泛化能力的本质：输入压缩与潜在表征中预测信息的保留需达到完美平衡。通过理论证明，仅解码器的Transformer模型在构建最优任务序列表征上存在固有局限。进一步研究表明，对KV缓存进行周期性全局变换是提升Transformer推理任务泛化能力的关键。基于此，我们提出了一种创新的Transformer架构改进方案，通过定期全局重写KV缓存，使其从记忆输入转向编码对未来预测最关键的特征。实验结果显示，改进后的模型在数学推理任务中表现优异，超越了参数量多出3.5倍的普通Transformer模型，同时也优于现有缓存压缩机制。我们的方法不仅扩展了现有KV缓存压缩技术，更通过信息论原理构建了一个全新的框架，解决了单纯依赖模型规模无法克服的推理局限。

> Despite their impressive capabilities, Large Language Models struggle with generalisation beyond their training distribution, often exhibiting sophisticated pattern interpolation rather than true abstract reasoning (extrapolation). In this work, we approach this limitation through the lens of Information Bottleneck (IB) theory, which posits that model generalisation emerges from an optimal balance between input compression and retention of predictive information in latent representations. We prove using IB theory that decoder-only Transformers are inherently constrained in their ability to form task-optimal sequence representations. We then use this result to demonstrate that periodic global transformation of the internal sequence-level representations (KV cache) is a necessary computational step for improving Transformer generalisation in reasoning tasks. Based on these theoretical insights, we propose a modification to the Transformer architecture, in the form of an additional module that globally rewrites the KV cache at periodic intervals, shifting its capacity away from memorising input prefixes and toward encoding features most useful for predicting future tokens. Our model delivers substantial gains on mathematical reasoning benchmarks, outperforming both vanilla Transformers with up to 3.5x more parameters, as well as heuristic-driven pruning mechanisms for cache compression. Our approach can be seen as a principled generalisation of existing KV-cache compression methods; whereas such methods focus solely on compressing input representations, they often do so at the expense of retaining predictive information, and thus their capabilities are inherently bounded by those of an unconstrained model. This establishes a principled framework to manipulate Transformer memory using information theory, addressing fundamental reasoning limitations that scaling alone cannot overcome.

[Arxiv](https://arxiv.org/abs/2505.16950)