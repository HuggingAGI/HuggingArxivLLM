# 词元粒度对语言模型预测能力的影响

发布时间：2024年12月16日

`LLM理论

理由：这篇论文主要探讨了语言模型中的标记粒度对 surprisal 预测能力的影响，特别是对认知建模的影响。这涉及到语言模型的内部机制和理论分析，属于对语言模型的理论研究，因此归类为LLM理论。` `认知科学`

> The Impact of Token Granularity on the Predictive Power of Language Model Surprisal

# 摘要

> 逐字语言模型的 surprisal 常用于模拟人类读者的增量处理过程，但语言建模中的选择如何影响其预测能力仍是一个问题。在认知建模中，子词标记的粒度常被忽视，但它直接影响词长、词频的编码以及向量表示的质量。本文通过实验调整标记粒度，评估其对 surprisal 解释自然文本和处理花园路径结构困难的影响。实验发现，词汇量为 8,000 的标记生成的 surprisal 最具预测性。而在花园路径结构上，使用较粗粒度标记训练的语言模型对关键区域分配更高的 surprisal，表明其对句法更敏感。这些结果表明，标记粒度对语言模型 surprisal 在认知建模中的质量至关重要。

> Word-by-word language model surprisal is often used to model the incremental processing of human readers, which raises questions about how various choices in language modeling influence its predictive power. One factor that has been overlooked in cognitive modeling is the granularity of subword tokens, which explicitly encodes information about word length and frequency, and ultimately influences the quality of vector representations that are learned. This paper presents experiments that manipulate the token granularity and evaluate its impact on the ability of surprisal to account for processing difficulty of naturalistic text and garden-path constructions. Experiments with naturalistic reading times reveal a substantial influence of token granularity on surprisal, with tokens defined by a vocabulary size of 8,000 resulting in surprisal that is most predictive. In contrast, on garden-path constructions, language models trained on coarser-grained tokens generally assigned higher surprisal to critical regions, suggesting their increased sensitivity to syntax. Taken together, these results suggest a large role of token granularity on the quality of language model surprisal for cognitive modeling.

[Arxiv](https://arxiv.org/abs/2412.11940)