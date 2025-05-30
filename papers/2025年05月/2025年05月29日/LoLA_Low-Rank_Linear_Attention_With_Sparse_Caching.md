# # 摘要
LoLA：低秩线性注意力机制结合稀疏缓存

发布时间：2025年05月29日

`LLM理论

摘要中的论文主要探讨了大型语言模型在处理长序列时的注意力机制问题，并提出了一种新的方法（LoLA）来优化线性注意力机制。这种方法涉及到模型内部的工作机制和优化，属于大型语言模型的理论研究。因此，这篇论文被归类为LLM理论。`

> LoLA: Low-Rank Linear Attention With Sparse Caching

# 摘要

> 基于Transformer的大型语言模型在处理长序列时面临二次复杂度的挑战。线性注意力方法虽高效，但无法准确模拟softmax注意力。通过在每个线性注意力头中加入滑动窗口注意力，我们弥补了短上下文任务中的性能差距。然而，这些方法因“内存碰撞”而无法有效检索长上下文信息。为此，我们提出LoLA：低秩线性注意力结合稀疏缓存。LoLA通过独立存储可能干扰记忆的关键值对，避免信息冲突。进一步，LoLA将关键值对分配到三种记忆形式中：(i) 近期关键值对存储在本地滑动窗口；(ii) 难以记忆的关键值对存储在稀疏全局缓存；(iii) 通用关键值对存储在线性注意力的循环隐藏状态。作为仅用于推理的策略，LoLA在RULER的“针在 haystack中”任务中支持长达8K的上下文检索。在4K上下文长度下，LoLA将基础次二次模型的准确率从0.6%提升至97.4%，且缓存大小仅为Llama-3.1 8B的4.6分之一。LoLA在10亿和80亿参数的次二次模型中表现出色，尤其在零样本常识推理任务中表现优异。最后，LoLA是一种极其轻量级的方法：几乎所有的实验结果都可以在单个消费级GPU上复现。

> Transformer-based large language models suffer from quadratic complexity at inference on long sequences. Linear attention methods are efficient alternatives, however, they fail to provide an accurate approximation of softmax attention. By additionally incorporating sliding window attention into each linear attention head, this gap can be closed for short context-length tasks. Unfortunately, these approaches cannot recall important information from long contexts due to "memory collisions". In this paper , we propose LoLA: Low-rank Linear Attention with sparse caching. LoLA separately stores additional key-value pairs that would otherwise interfere with past associative memories. Moreover, LoLA further closes the gap between linear attention models and transformers by distributing past key-value pairs into three forms of memory: (i) recent pairs in a local sliding window; (ii) difficult-to-memorize pairs in a sparse, global cache; and (iii) generic pairs in the recurrent hidden state of linear attention. As an inference-only strategy, LoLA enables pass-key retrieval on up to 8K context lengths on needle-in-a-haystack tasks from RULER. It boosts the accuracy of the base subquadratic model from 0.6% to 97.4% at 4K context lengths, with a 4.6x smaller cache than that of Llama-3.1 8B. LoLA demonstrates strong performance on zero-shot commonsense reasoning tasks among 1B and 8B parameter subquadratic models. Finally, LoLA is an extremely lightweight approach: Nearly all of our results can be reproduced on a single consumer GPU.

[Arxiv](https://arxiv.org/abs/2505.23666)