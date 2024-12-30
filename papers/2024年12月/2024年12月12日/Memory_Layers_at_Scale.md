# 规模化的内存层

发布时间：2024年12月12日

`LLM应用` `计算机` `人工智能`

> Memory Layers at Scale

# 摘要

> 摘要：内存层借助可训练的键值查找机制为模型增添额外参数，且不会增加 FLOPs。从概念上说，稀疏激活的内存层对计算繁重的密集前馈层形成补充，能以较低成本提供专门用于存储和检索信息的能力。此项工作让内存层不再停留在概念验证阶段，证实了其在当下规模中的实用性。在下游任务里，采用我们改进的内存层强化的语言模型，胜过计算预算两倍多的密集模型，以及在计算和参数匹配时的专家混合模型。我们发现，对于事实类任务，增益效果尤其显著。我们给出了一个完全可并行化的内存层实现，展示了高达 128B 内存参数的缩放规律，预训练达 1 万亿个标记，并与最高 8B 参数的基础模型作对比。

> 
Abstract:Memory layers use a trainable key-value lookup mechanism to add extra parameters to a model without increasing FLOPs. Conceptually, sparsely activated memory layers complement compute-heavy dense feed-forward layers, providing dedicated capacity to store and retrieve information cheaply. This work takes memory layers beyond proof-of-concept, proving their utility at contemporary scale. On downstream tasks, language models augmented with our improved memory layer outperform dense models with more than twice the computation budget, as well as mixture-of-expert models when matched for both compute and parameters. We find gains are especially pronounced for factual tasks. We provide a fully parallelizable memory layer implementation, demonstrating scaling laws with up to 128B memory parameters, pretrained to 1 trillion tokens, comparing to base models with up to 8B parameters.
    

[Arxiv](https://arxiv.org/pdf/2412.09764)