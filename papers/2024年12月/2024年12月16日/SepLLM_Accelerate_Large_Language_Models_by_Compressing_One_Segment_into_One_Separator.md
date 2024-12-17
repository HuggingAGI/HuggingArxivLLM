# SepLLM：借由将一个片段压缩成一个分隔符来加快大型语言模型的速度

发布时间：2024年12月16日

`LLM应用` `计算机技术`

> SepLLM: Accelerate Large Language Models by Compressing One Segment into One Separator

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理任务中表现卓越。然而，其庞大的规模带来了诸多挑战，尤其是在计算需求和推理速度方面，因其具有二次复杂性。在此次研究中，我们发现了一个关键模式：某些看似毫无意义的特殊标记（比如分隔符），相比具有语义的标记，对注意力得分的贡献比例失衡。这一发现表明，这些分隔符标记之间的片段信息能够有效地浓缩至分隔符标记自身，且不会有显著的信息损失。基于此，我们引入了 SepLLM，这是一个即插即用的框架，它通过压缩这些片段并消除冗余标记来加快推理速度。另外，我们还实现了用于训练加速的高效内核。在无训练、从头训练和训练后等设置下的实验结果证明了 SepLLM 的有效性。特别要指出的是，使用 Llama-3-8B 骨干，SepLLM 在 GSM8K-CoT 基准测试中实现了超过 50％的 KV 缓存削减，同时性能相当。而且，在流设置中，SepLLM 能够有效处理多达 400 万个甚至更多的标记序列，同时保持稳定的语言建模能力。

> Large Language Models (LLMs) have exhibited exceptional performance across a spectrum of natural language processing tasks. However, their substantial sizes pose considerable challenges, particularly in computational demands and inference speed, due to their quadratic complexity. In this work, we have identified a key pattern: certain seemingly meaningless special tokens (i.e., separators) contribute disproportionately to attention scores compared to semantically meaningful tokens. This observation suggests that information of the segments between these separator tokens can be effectively condensed into the separator tokens themselves without significant information loss. Guided by this insight, we introduce SepLLM, a plug-and-play framework that accelerates inference by compressing these segments and eliminating redundant tokens. Additionally, we implement efficient kernels for training acceleration. Experimental results across training-free, training-from-scratch, and post-training settings demonstrate SepLLM's effectiveness. Notably, using the Llama-3-8B backbone, SepLLM achieves over 50% reduction in KV cache on the GSM8K-CoT benchmark while maintaining comparable performance. Furthermore, in streaming settings, SepLLM effectively processes sequences of up to 4 million tokens or more while maintaining consistent language modeling capabilities.

[Arxiv](https://arxiv.org/abs/2412.12094)