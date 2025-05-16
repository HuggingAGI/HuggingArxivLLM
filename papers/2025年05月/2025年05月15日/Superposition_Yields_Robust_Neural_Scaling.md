# 叠加：稳健神经缩放的秘诀

发布时间：2025年05月15日

`LLM理论

摘要讨论了大型语言模型（LLMs）的神经缩放定律，特别是损失随模型规模变化的规律。研究从表示叠加性和特征频率出发，构建理论模型，分析损失变化，并用几何原理解释现象，最终验证于实际模型。这属于理论层面的探讨，因此归类为LLM理论。` `人工智能`

> Superposition Yields Robust Neural Scaling

# 摘要

> 大型语言模型（LLMs）的成功源于“模型越大性能越优”这一现象，但这种神经缩放定律的起源仍不明朗——即损失为何会以幂律形式随着模型规模增长而递减。我们从两个经验原则出发：首先，LLMs的表示能力超越其模型维度（宽度），即具有叠加性；其次，语言中的词汇或概念出现频率各不相同。基于此，我们构建了一个简化模型来研究损失随模型规模的变化规律。

研究发现，当叠加性较弱时，即仅最频繁的特征被表示且无干扰，损失随模型规模的变化取决于基础特征频率；若特征频率遵循幂律分布，损失也将呈现类似规律。然而，在强叠加性情况下，即所有特征均被表示但彼此重叠，损失则与模型维度呈反比关系，这一结论在多种特征频率分布下均成立。

这种稳健的缩放行为可用几何原理解释：当大量向量被压缩至低维空间时，向量间的干扰（平方重叠）将与该维度呈反比关系。随后，我们分析了四个开源LLM家族，发现它们均表现出强叠加性，并与我们的简化模型预测结果高度吻合。Chinchilla缩放定律也证实了我们的研究发现。

由此，我们得出结论：表示叠加性是观察到的神经缩放定律背后的重要机制。我们期待这些洞见将启发新的训练策略和模型架构，以更少的计算量和参数实现更优性能。

> The success of today's large language models (LLMs) depends on the observation that larger models perform better. However, the origin of this neural scaling law -- the finding that loss decreases as a power law with model size -- remains unclear. Starting from two empirical principles -- that LLMs represent more things than the model dimensions (widths) they have (i.e., representations are superposed), and that words or concepts in language occur with varying frequencies -- we constructed a toy model to study the loss scaling with model size. We found that when superposition is weak, meaning only the most frequent features are represented without interference, the scaling of loss with model size depends on the underlying feature frequency; if feature frequencies follow a power law, so does the loss. In contrast, under strong superposition, where all features are represented but overlap with each other, the loss becomes inversely proportional to the model dimension across a wide range of feature frequency distributions. This robust scaling behavior is explained geometrically: when many more vectors are packed into a lower dimensional space, the interference (squared overlaps) between vectors scales inversely with that dimension. We then analyzed four families of open-sourced LLMs and found that they exhibit strong superposition and quantitatively match the predictions of our toy model. The Chinchilla scaling law turned out to also agree with our results. We conclude that representation superposition is an important mechanism underlying the observed neural scaling laws. We anticipate that these insights will inspire new training strategies and model architectures to achieve better performance with less computation and fewer parameters.

[Arxiv](https://arxiv.org/abs/2505.10465)