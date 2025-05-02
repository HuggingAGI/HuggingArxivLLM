# FreqKV：高效扩展上下文窗口的频域键值压缩技术

发布时间：2025年05月01日

`LLM应用` `文本生成`

> FreqKV: Frequency Domain Key-Value Compression for Efficient Context Window Extension

# 摘要

> 长文本生成应用中，扩展大型语言模型（LLMs）的上下文窗口至关重要。然而，微调和推理过程中，键值（KV）缓存内存需求的线性增长以及自注意力机制在序列长度上的二次复杂度带来了巨大挑战。现有方法在扩展到更长上下文时都面临着性能下降的问题。本研究提出了一种全新的上下文扩展方法，旨在优化微调和推理效率。

我们的方法基于一个关键观察：在频域中，KV缓存的能量分布主要集中在低频成分上。通过滤除高频成分，KV缓存可以在几乎不损失信息的情况下得到有效压缩。基于这一发现，我们提出了一种高效的压缩技术——FreqKV，它能够在频域中将不断增长的KV缓存迭代压缩到固定大小，适用于微调和推理。FreqKV无需引入额外参数或修改模型架构。仅需少量微调，LLMs即可学会利用压缩后的有限缓存，并高效扩展上下文窗口。

在各种长上下文语言建模和理解任务上的实验结果证明了我们方法的高效性和有效性。


> Extending the context window in large language models (LLMs) is essential for applications involving long-form content generation. However, the linear increase in key-value (KV) cache memory requirements and the quadratic complexity of self-attention with respect to sequence length present significant challenges during fine-tuning and inference. Existing methods suffer from performance degradation when extending to longer contexts. In this work, we introduce a novel context extension method that optimizes both fine-tuning and inference efficiency. Our method exploits a key observation: in the frequency domain, the energy distribution of the KV cache is primarily concentrated in low-frequency components. By filtering out the high-frequency components, the KV cache can be effectively compressed with minimal information loss. Building on this insight, we propose an efficient compression technique, FreqKV, that iteratively compresses the increasing KV cache to a fixed size in the frequency domain, applicable to both fine-tuning and inference. FreqKV introduces no additional parameters or architectural modifications. With minimal fine-tuning, LLMs can learn to leverage the limited cache that is compressed in the frequency domain and extend the context window efficiently. Experiments on various long context language modeling and understanding tasks demonstrate the efficiency and efficacy of the proposed method.

[Arxiv](https://arxiv.org/abs/2505.00570)