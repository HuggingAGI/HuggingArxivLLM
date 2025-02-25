# 潜在思维推理：循环式变换器的力量解析

发布时间：2025年02月24日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）在推理任务中的表现，特别是循环模型与非循环模型的比较。研究从理论角度分析了模型的深度、参数数量以及循环机制对推理能力的影响，揭示了循环模型在推理任务中的优势，并进一步探讨了推理与记忆的关系。这些内容属于LLM的理论研究，因此归类为LLM理论。` `人工智能`

> Reasoning with Latent Thoughts: On the Power of Looped Transformers

# 摘要

> 大型语言模型展现出了非凡的推理能力，而规模定律表明，较大的参数数量，尤其是在深度维度上，是主要的驱动力。在本研究中，我们提出一个更强的论点——许多推理问题需要较大的深度，但并不一定需要大量的参数。这为循环模型在推理任务中的应用开辟了新的可能性。

首先，我们发现，对于许多合成推理问题，如加法、$p$-跳归纳和数学问题，一个$k$层的Transformer循环$L$次几乎可以达到$kL$层非循环模型的性能，且显著优于$k$层模型。这一发现得到了理论结果的进一步支持，这些结果显示许多这样的推理问题可以通过迭代算法来解决，因此，可以使用循环模型以接近最优的深度有效地解决。

也许令人惊讶的是，这些优势也延伸到了语言建模的实际应用中——在许多下游推理任务中，一个循环$L$次的$k$层语言模型可以与，甚至优于，一个$kL$层的语言模型相媲美。实际上，我们的实证分析揭示了一个引人入胜的现象：循环模型和非循环模型的扩展行为取决于它们的有效深度，类似于链式推理（CoT）在推理时的扩展行为。

我们进一步阐明了与CoT推理的联系，证明循环模型可以隐式生成潜在的思考，并通过$T$次循环模拟$T$步的CoT推理。受这些发现的启发，我们还揭示了推理与记忆之间的有趣二分法，并设计了一种基于循环的正则化方法，该方法在两个方面都表现出有效性。


> Large language models have shown remarkable reasoning abilities and scaling laws suggest that large parameter count, especially along the depth axis, is the primary driver. In this work, we make a stronger claim -- many reasoning problems require a large depth but not necessarily many parameters. This unlocks a novel application of looped models for reasoning. Firstly, we show that for many synthetic reasoning problems like addition, $p$-hop induction, and math problems, a $k$-layer transformer looped $L$ times nearly matches the performance of a $kL$-layer non-looped model, and is significantly better than a $k$-layer model. This is further corroborated by theoretical results showing that many such reasoning problems can be solved via iterative algorithms, and thus, can be solved effectively using looped models with nearly optimal depth. Perhaps surprisingly, these benefits also translate to practical settings of language modeling -- on many downstream reasoning tasks, a language model with $k$-layers looped $L$ times can be competitive to, if not better than, a $kL$-layer language model. In fact, our empirical analysis reveals an intriguing phenomenon: looped and non-looped models exhibit scaling behavior that depends on their effective depth, akin to the inference-time scaling of chain-of-thought (CoT) reasoning. We further elucidate the connection to CoT reasoning by proving that looped models implicitly generate latent thoughts and can simulate $T$ steps of CoT with $T$ loops. Inspired by these findings, we also present an interesting dichotomy between reasoning and memorization, and design a looping-based regularization that is effective on both fronts.

[Arxiv](https://arxiv.org/abs/2502.17416)