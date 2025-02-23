# # 无限检索：长上下文处理中的注意力增强大语言模型。

发布时间：2025年02月18日

`LLM应用

理由：这篇论文提出了一种新的方法InfiniRetri，用于解决大型语言模型（LLMs）在处理长文本时的上下文窗口限制问题。通过利用LLMs自身的注意力机制，该方法能够在不增加额外训练成本或模块的情况下，实现对无限长度输入的精准检索，并在实际任务中表现出色。因此，它属于LLM应用的范畴。` `信息检索`

> Infinite Retrieval: Attention Enhanced LLMs in Long-Context Processing

# 摘要

> 大型语言模型（LLMs）的上下文窗口大小限制了其处理能力，无论是简单的直接检索任务，还是复杂的多跳推理任务，当输入标记超过上限时，都会面临挑战。尽管提出了多种方法来增强LLMs的长上下文处理能力，但它们要么显著增加后训练成本，要么需要额外工具模块（如RAG），要么在实际任务中未见明显改进。我们的研究发现各层注意力分布与生成答案之间的关联，并通过实验验证注意力分配与增强检索能力的一致性。基于此，我们提出了一种新方法InfiniRetri，该方法利用LLMs自身的注意力信息，实现对无限长度输入的精准检索。实验结果显示，InfiniRetri在100万标记的Needle-In-a-Haystack（NIH）测试中，使用0.5B参数模型实现了100%的准确率，超越了其他方法及更大模型，创下了新最先进水平（SOTA）。此外，该方法在现实世界基准测试中实现了显著性能提升，最高达288%。值得注意的是，InfiniRetri无需额外训练即可应用于任何基于Transformer的LLMs，并在长文本处理中大幅降低了推理延迟和计算开销。综上所述，我们的研究表明InfiniRetri在实际应用中的巨大潜力，并为利用LLMs自身能力在无限长度标记下检索信息开创了一种新范式。代码将在链接中发布。

> Limited by the context window size of Large Language Models(LLMs), handling various tasks with input tokens exceeding the upper limit has been challenging, whether it is a simple direct retrieval task or a complex multi-hop reasoning task. Although various methods have been proposed to enhance the long-context processing capabilities of LLMs, they either incur substantial post-training costs, or require additional tool modules(e.g.,RAG), or have not shown significant improvement in realistic tasks. Our work observes the correlation between the attention distribution and generated answers across each layer, and establishes the attention allocation aligns with retrieval-augmented capabilities through experiments. Drawing on the above insights, we propose a novel method InfiniRetri that leverages the LLMs's own attention information to enable accurate retrieval across inputs of infinitely length. Our evaluations indicate that InfiniRetri achieves 100% accuracy in the Needle-In-a-Haystack(NIH) test over 1M tokens using a 0.5B parameter model, surpassing other method or larger models and setting a new state-of-the-art(SOTA). Moreover, our method achieves significant performance improvements on real-world benchmarks, with a maximum 288% improvement. In addition, InfiniRetri can be applied to any Transformer-based LLMs without additional training and substantially reduces inference latency and compute overhead in long texts. In summary, our comprehensive studies show InfiniRetri's potential for practical applications and creates a paradigm for retrievaling information using LLMs own capabilities under infinite-length tokens. Code will be released in link.

[Arxiv](https://arxiv.org/abs/2502.12962)