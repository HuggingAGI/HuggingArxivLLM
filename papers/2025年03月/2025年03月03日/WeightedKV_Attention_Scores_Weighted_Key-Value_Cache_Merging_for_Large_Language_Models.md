# 加权键值：应用于大型语言模型的注意力分数加权键值缓存合并方法

发布时间：2025年03月03日

`LLM应用` `模型优化` `语言模型`

> WeightedKV: Attention Scores Weighted Key-Value Cache Merging for Large Language Models

# 摘要

> 大型语言模型（LLMs）借助键值（KV）缓存减少自回归生成中的重复计算。然而，生成过程中KV缓存的大小会线性增长，导致内存占用过高，尤其在处理长文本时更为明显。现有的KV缓存压缩方法通常通过移除不重要的KV对来维持固定缓存大小，但这会导致生成过程中永久丢失部分标记。奇异值分解表明，与	extit{键}相比，	extit{值}并不具备显著的低秩特性，这意味着信息在	extit{值}中的分布更为均匀，而	extit{键}中则更为冗余。因此，同时移除	extit{键}和	extit{值}的方法会面临丢失关键信息和破坏上下文完整性的风险，最终影响输出质量。为了解决这一问题，我们提出了WeightedKV，这是一种无需训练的新方法。该方法通过移除不重要标记的	extit{键}，同时将其	extit{值}与邻近标记的	extit{值}进行加权融合（基于平均注意力分数的凸组合）。这样一来，保留的	extit{键}充当生成过程的锚点，而融合后的	extit{值}则提供了丰富的上下文背景。我们在四个广泛使用的语言建模数据集上评估了该方法，结果表明其性能优于所有基线方法，尤其是在预算比例较低的情况下表现更为突出。

> Large Language Models (LLMs) use key-value (KV) cache to reduce redundant computation in autoregressive generation. However, the KV cache size increases linearly during generation, leading to excessive memory usage, especially for long texts. Most KV cache compression methods evict the unimportant KV pairs to maintain a fixed cache size, which leads to the permanent loss of tokens during generation. However, singular value decomposition shows that \textit{values} do not exhibit a strong low-rank property as \textit{keys} do, suggesting that information is distributed more evenly across \textit{values}, in contrast to its more redundant distribution within \textit{keys}. Therefore, methods that evict both \textit{keys} and \textit{values} risk losing crucial information and compromise context integrity, ultimately degrading the output quality. To address this problem, we propose WeightedKV, a novel, training-free approach that discards the \textit{keys} of less important tokens, while merging their \textit{values} into neighboring tokens via a convex combination weighted by their average attention scores. In this way, the retained \textit{keys} serve as anchors that guide the generation process, while the merged \textit{values} provide a rich contextual backdrop. We assess our method on four widely used language modeling datasets, demonstrating superior performance compared to all baseline methods, particularly with a lower budget ratio.

[Arxiv](https://arxiv.org/abs/2503.01330)