# 语言模型具备对自身内部激活进行元认知监控与调控的能力。

发布时间：2025年05月19日

`LLM理论` `AI安全` `神经科学`

> Language Models Are Capable of Metacognitive Monitoring and Control of Their Internal Activations

# 摘要

> 大型语言模型（LLMs）有时能报告其解题策略，有时却无法做到，这表明它们具备某种程度的元认知能力——即监控自身认知过程并进行报告和自我控制的能力。元认知能力虽能增强AI能力，但也带来安全风险，因为模型可能隐藏内部过程以规避监督机制。鉴于社会对这些模型的依赖日益增加，我们迫切需要理解它们元认知能力的局限性，特别是监控内部激活的能力。为此，我们引入了一种受神经科学启发的神经反馈范式，用于量化LLMs明确报告和控制其激活模式的能力。通过向模型呈现句子-标签对，其中标签对应于特定神经表示空间中句子引发的内部激活方向，我们证明了LLMs可以学会报告和控制这些激活。性能因多个因素而异：提供的示例对数量、目标神经方向的语义可解释性以及该方向解释的方差。这些结果揭示了一个维度远低于模型神经空间的“元认知空间”，表明LLMs只能监控其神经机制的一部分。我们的发现提供了量化LLMs元认知能力的实证证据，对AI安全具有重要意义。

> Large language models (LLMs) can sometimes report the strategies they actually use to solve tasks, but they can also fail to do so. This suggests some degree of metacognition -- the capacity to monitor one's own cognitive processes for subsequent reporting and self-control. Metacognitive abilities enhance AI capabilities but raise safety concerns, as models might obscure their internal processes to evade neural-activation-based oversight mechanisms designed to detect harmful behaviors. Given society's increased reliance on these models, it is critical that we understand the limits of their metacognitive abilities, particularly their ability to monitor their internal activations. To address this, we introduce a neuroscience-inspired neurofeedback paradigm designed to quantify the ability of LLMs to explicitly report and control their activation patterns. By presenting models with sentence-label pairs where labels correspond to sentence-elicited internal activations along specific directions in the neural representation space, we demonstrate that LLMs can learn to report and control these activations. The performance varies with several factors: the number of example pairs provided, the semantic interpretability of the target neural direction, and the variance explained by that direction. These results reveal a "metacognitive space" with dimensionality much lower than the model's neural space, suggesting LLMs can monitor only a subset of their neural mechanisms. Our findings provide empirical evidence quantifying metacognitive capabilities in LLMs, with significant implications for AI safety.

[Arxiv](https://arxiv.org/abs/2505.13763)