# 别关注

发布时间：2025年06月12日

`LLM理论` `神经架构`

> Don't Pay Attention

# 摘要

> Transformer 已经成为大型语言模型和跨领域下游任务的事实标准。尽管它拥有训练并行性等众多优势，但 Transformer 仍面临两个关键挑战：无法有效处理超出固定上下文窗口的序列，以及注意力机制的二次复杂度。这些挑战重新激发了对 RNN 架构的兴趣，这类架构虽然并行能力有限，但能以线性扩展处理序列长度，并改善对长距离依赖关系的处理。本文中，我们提出了一种新的神经基础架构 Avey，它打破了注意力机制和循环结构的限制。Avey 由排序器和自回归神经处理器组成，协同识别并为任何给定标记上下文化其最相关的标记，无论其在序列中的位置。具体而言，Avey 将序列长度与上下文宽度解耦，从而能够有效处理任意长度的序列。实验结果表明，Avey 在各种标准短距离 NLP 基准测试中与 Transformer 表现相当，同时在捕捉长距离依赖关系方面表现尤为出色。

> The Transformer has become the de facto standard for large language models and a wide range of downstream tasks across various domains. Despite its numerous advantages like inherent training parallelism, the Transformer still faces key challenges due to its inability to effectively process sequences beyond a fixed context window and the quadratic complexity of its attention mechanism. These challenges have renewed interest in RNN-like architectures, which offer linear scaling with sequence length and improved handling of long-range dependencies, albeit with limited parallelism due to their inherently recurrent nature. In this paper, we propose Avey, a new neural foundational architecture that breaks away from both attention and recurrence. Avey comprises a ranker and an autoregressive neural processor, which collaboratively identify and contextualize only the most relevant tokens for any given token, regardless of their positions in the sequence. Specifically, Avey decouples sequence length from context width, thus enabling effective processing of arbitrarily long sequences. Experimental results show that Avey compares favorably to the Transformer across a variety of standard short-range NLP benchmarks, while notably excelling at capturing long-range dependencies.

[Arxiv](https://arxiv.org/abs/2506.11305)