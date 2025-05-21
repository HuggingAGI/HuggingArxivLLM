# 语言模型能够实现对内部激活的元认知监控与控制

发布时间：2025年05月19日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的元认知能力，即模型如何监控和控制自身的内部激活过程。研究引入了神经反馈范式，分析了模型在不同条件下的表现，并揭示了元认知空间的维度。这些内容属于对LLMs内在机制和能力的理论研究，因此归类为LLM理论。` `人工智能` `AI安全`

> Language Models Are Capable of Metacognitive Monitoring and Control of Their Internal Activations

# 摘要

> 大型语言模型 (LLMs) 有时会报告它们解决问题的策略，但有时也会失败。这种现象表明，它们具备一定程度的元认知能力，即能够监控自身认知过程以进行后续报告和自我控制。元认知能力虽然能增强 AI 的能力，但也带来了安全风险，因为模型可能会隐藏内部过程，以规避旨在检测有害行为的监督机制。鉴于社会对这些模型的依赖日益增加，我们需要深入理解其元认知能力的局限性，特别是监控内部激活的能力。

为此，我们引入了一种受神经科学启发的神经反馈范式，旨在量化 LLMs 显式报告和控制其激活模式的能力。通过向模型展示句子-标签对，其中标签对应于句子在特定神经表征空间方向上引发的内部激活，我们证明 LLMs 可以学习报告和控制这些激活。性能受多个因素影响：提供的示例对数量、目标神经方向的语义可解释性，以及该方向解释的方差。这些结果揭示了一个维度远低于模型神经空间的“元认知空间”，表明 LLMs 只能监控其神经机制的一部分。我们的发现提供了量化 LLMs 元认知能力的实证证据，对 AI 安全具有重要意义。

> Large language models (LLMs) can sometimes report the strategies they actually use to solve tasks, but they can also fail to do so. This suggests some degree of metacognition -- the capacity to monitor one's own cognitive processes for subsequent reporting and self-control. Metacognitive abilities enhance AI capabilities but raise safety concerns, as models might obscure their internal processes to evade neural-activation-based oversight mechanisms designed to detect harmful behaviors. Given society's increased reliance on these models, it is critical that we understand the limits of their metacognitive abilities, particularly their ability to monitor their internal activations. To address this, we introduce a neuroscience-inspired neurofeedback paradigm designed to quantify the ability of LLMs to explicitly report and control their activation patterns. By presenting models with sentence-label pairs where labels correspond to sentence-elicited internal activations along specific directions in the neural representation space, we demonstrate that LLMs can learn to report and control these activations. The performance varies with several factors: the number of example pairs provided, the semantic interpretability of the target neural direction, and the variance explained by that direction. These results reveal a "metacognitive space" with dimensionality much lower than the model's neural space, suggesting LLMs can monitor only a subset of their neural mechanisms. Our findings provide empirical evidence quantifying metacognitive capabilities in LLMs, with significant implications for AI safety.

[Arxiv](https://arxiv.org/abs/2505.13763)