# 提示工程与大型语言模型：等长机器翻译中的长度控制研究

发布时间：2025年06月05日

`LLM应用` `机器翻译`

> Prompting LLMs: Length Control for Isometric Machine Translation

# 摘要

> 本研究探讨了在2022年IWSLT等距共享任务框架下，等距机器翻译在En$	o$De、En$	o$Fr和En$	o$Es三个语言对中的表现。我们采用八种不同规模的开源大型语言模型（LLMs），深入分析了提示策略、少样本示例数量以及示例选择对翻译质量与长度控制的影响。研究发现，指令的措辞需与提供的示例特性相匹配，方能在输出长度控制中发挥关键作用。实验结果表明，大型语言模型仅在面对极端示例时才会生成较短的译文，而等距示例往往导致模型忽视长度限制。尽管少样本提示通常能提升翻译质量，但在5、10和20样本设置下，改进幅度较为有限。最后，通过综合考虑多个输出结果，我们成功在翻译长度与质量之间实现了显著的优化平衡，为部分语言对取得了当前最优的性能表现。

> In this study, we explore the effectiveness of isometric machine translation across multiple language pairs (En$\to$De, En$\to$Fr, and En$\to$Es) under the conditions of the IWSLT Isometric Shared Task 2022. Using eight open-source large language models (LLMs) of varying sizes, we investigate how different prompting strategies, varying numbers of few-shot examples, and demonstration selection influence translation quality and length control. We discover that the phrasing of instructions, when aligned with the properties of the provided demonstrations, plays a crucial role in controlling the output length. Our experiments show that LLMs tend to produce shorter translations only when presented with extreme examples, while isometric demonstrations often lead to the models disregarding length constraints. While few-shot prompting generally enhances translation quality, further improvements are marginal across 5, 10, and 20-shot settings. Finally, considering multiple outputs allows to notably improve overall tradeoff between the length and quality, yielding state-of-the-art performance for some language pairs.

[Arxiv](https://arxiv.org/abs/2506.04855)