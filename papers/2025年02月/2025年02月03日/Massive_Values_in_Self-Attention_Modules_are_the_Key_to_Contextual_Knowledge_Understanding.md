# 自注意力模块中的大量值是理解上下文知识的关键

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中注意力机制的具体运作机制，特别是注意力查询（Q）和键（K）的特定区域中集中出现的大值现象，并分析了这些现象对模型性能的影响。论文还研究了这些现象的来源，并提出了对模型设计与优化的实用指导。这些内容属于对LLM内部机制的理论性研究，因此分类为LLM理论。` `机器学习`

> Massive Values in Self-Attention Modules are the Key to Contextual Knowledge Understanding

# 摘要

> 大型语言模型（LLMs）在上下文知识理解方面表现卓越。本文揭示，在基于Transformer的现代LLMs中，注意力查询（Q）和键（K）的特定区域持续出现集中的大值，而值（V）中则无此现象。通过大量实验，我们进一步证实，这些大值在解释上下文知识（即从当前上下文窗口获取的知识）中起关键作用，而非用于检索模型参数中的知识。量化策略的研究表明，忽略这些大值会导致需要丰富上下文理解的任务性能显著下降，与我们的分析一致。最后，我们发现这些大值的集中源于旋转位置编码（RoPE），且从模型的第一层就开始出现。这些发现为LLMs中Q和K的运作机制提供了新视角，并为模型设计与优化提供了实用指导。代码已开源：https://github.com/MingyuJ666/Rope_with_LLM。

> Large language models (LLMs) have achieved remarkable success in contextual knowledge understanding. In this paper, we show that these concentrated massive values consistently emerge in specific regions of attention queries (Q) and keys (K) while not having such patterns in values (V) in various modern transformer-based LLMs (Q, K, and V mean the representations output by the query, key, and value layers respectively). Through extensive experiments, we further demonstrate that these massive values play a critical role in interpreting contextual knowledge (knowledge obtained from the current context window) rather than in retrieving parametric knowledge stored within the model's parameters. Our further investigation of quantization strategies reveals that ignoring these massive values leads to a pronounced drop in performance on tasks requiring rich contextual understanding, aligning with our analysis. Finally, we trace the emergence of concentrated massive values and find that such concentration is caused by Rotary Positional Encoding (RoPE), which has appeared since the first layers. These findings shed new light on how Q and K operate in LLMs and offer practical insights for model design and optimization. The Code is Available at https://github.com/MingyuJ666/Rope_with_LLM.

[Arxiv](https://arxiv.org/abs/2502.01563)