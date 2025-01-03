# 从注意力到激活：解密大型语言模型的奥秘

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要研究了自回归Transformer中的两个现象，并提出了改进方案。这些研究涉及到Transformer模型的内部机制和优化方法，属于对大型语言模型（LLM）的理论研究和改进。因此，将其分类为“LLM理论”是合适的。`

> From Attention to Activation: Unravelling the Enigmas of Large Language Models

# 摘要

> 我们研究了自回归Transformer中的两个奇特现象：（1）注意力头中第一个token的主导地位；（2）隐藏状态中的大异常激活。我们发现，像Llama这样的流行大型语言模型在98%的注意力头中最大程度地关注第一个token，这归因于softmax函数。为此，我们提出了softmax-1的改进方案。此外，我们确定自适应优化器（如Adam）是大异常激活的主因，并引入了OrthoAdam，一种利用正交矩阵转换梯度的新型优化器，以解决这一问题。最终，我们的方法不仅防止了这些现象的发生，还使Transformer在使用基本算法进行量化时保持性能，这是标准方法无法做到的。总之，我们的方法将第一个token的注意力比例从65%降至3.3%，隐藏状态中的激活峰度从1657降至3.1，4位权重量化下的困惑度惩罚从3565降至0.3。

> We study two strange phenomena in auto-regressive Transformers: (1) the dominance of the first token in attention heads; (2) the occurrence of large outlier activations in the hidden states. We find that popular large language models, such as Llama attend maximally to the first token in 98% of attention heads, a behaviour we attribute to the softmax function. To mitigate this issue, we propose a reformulation of softmax to softmax-1. Furthermore, we identify adaptive optimisers, e.g. Adam, as the primary contributor to the large outlier activations and introduce OrthoAdam, a novel optimiser that utilises orthogonal matrices to transform gradients, to address this issue. Finally, not only do our methods prevent these phenomena from occurring, but additionally, they enable Transformers to sustain their performance when quantised using basic algorithms, something that standard methods are unable to do. In summary, our methods reduce the attention proportion on the first token from 65% to 3.3%, the activation kurtosis in the hidden states from 1657 to 3.1, and perplexity penalty under 4-bit weight quantisation from 3565 to 0.3.

[Arxiv](https://arxiv.org/abs/2410.17174)