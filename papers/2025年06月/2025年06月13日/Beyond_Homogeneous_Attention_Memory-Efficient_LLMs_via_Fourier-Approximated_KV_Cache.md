# 超越同质化注意力：利用傅里叶近似 KV 缓存实现内存高效的 LLM

发布时间：2025年06月13日

`LLM理论

理由：这篇论文提出了一种新的注意力机制（FourierAttention），优化了Transformer模型在处理长上下文时的内存使用和计算效率，属于对大型语言模型的理论改进和优化，因此归类为LLM理论。` `计算机体系结构`

> Beyond Homogeneous Attention: Memory-Efficient LLMs via Fourier-Approximated KV Cache

# 摘要

> 随着上下文长度的增加，大型语言模型面临着日益增长的键值（KV）缓存内存需求带来的挑战。现有的压缩方法要么通过统一注意力头维度，要么依赖注意力引导的标记剪枝，但这些方法往往以牺牲准确性或增加计算开销为代价。我们提出了FourierAttention，一个无需训练的框架，它巧妙地利用了Transformer头维度的异质性：较低维度的头专注于局部上下文，而较高维度的头则捕捉长距离依赖关系。通过将对长上下文不敏感的维度投影到正交的Fourier基上，FourierAttention使用固定长度的频谱系数近似其时间演化。在LLaMA模型上的评估显示，FourierAttention在LongBench和Needle-In-A-Haystack（NIAH）基准测试中实现了最佳的长上下文准确性。此外，我们设计了一个自定义的Triton内核FlashFourierAttention，通过优化读写操作来减少内存占用，从而在不妥协性能的前提下实现高效部署。

> Large Language Models struggle with memory demands from the growing Key-Value (KV) cache as context lengths increase. Existing compression methods homogenize head dimensions or rely on attention-guided token pruning, often sacrificing accuracy or introducing computational overhead. We propose FourierAttention, a training-free framework that exploits the heterogeneous roles of transformer head dimensions: lower dimensions prioritize local context, while upper ones capture long-range dependencies. By projecting the long-context-insensitive dimensions onto orthogonal Fourier bases, FourierAttention approximates their temporal evolution with fixed-length spectral coefficients. Evaluations on LLaMA models show that FourierAttention achieves the best long-context accuracy on LongBench and Needle-In-A-Haystack (NIAH). Besides, a custom Triton kernel, FlashFourierAttention, is designed to optimize memory via streamlined read-write operations, enabling efficient deployment without performance compromise.

[Arxiv](https://arxiv.org/abs/2506.11886)