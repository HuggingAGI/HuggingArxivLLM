# <翻译失败>

发布时间：2025年04月07日

`LLM理论

理由：这篇论文探讨了Chain-of-Thought (CoT) 提示方法在大型语言模型中的表现及其背后的机制，属于对模型推理能力的理论分析和研究。` `人工智能`

> The Curse of CoT: On the Limitations of Chain-of-Thought in In-Context Learning

# 摘要

> Chain-of-Thought (CoT) 提示方法因其通过生成明确的解释性推理来提升大型语言模型 (LLMs) 的推理能力而备受推崇。然而，我们的研究发现了一个与这一普遍认知相悖的惊人现象。通过在 16 个先进 LLM 和 9 个不同基于模式的上下文学习 (ICL) 数据集上进行的广泛实验，我们发现 CoT 及其推理变体在各种模型规模和基准复杂度下，始终逊于直接回答的表现。为了深入探究这一意外现象，我们设计了一系列实验来验证多个假设性解释。我们的分析揭示了 CoT 在基于模式的 ICL 中性能背后的根本显隐二元性：尽管显式推理因 LLM 难以从演示中推断潜在模式而受阻，但隐式推理——被 CoT 推理不断增加的上下文距离所扰乱——往往能够补偿，即使推理存在缺陷，仍能给出正确答案。这种二元性解释了 CoT 的相对欠佳表现，因为显式推理中的噪声削弱了过程，即使隐式机制部分挽救了结果。值得注意的是，即使是擅长抽象和符号推理的长 CoT 推理模型，尽管计算成本更高，也未能完全克服这些限制。我们的发现挑战了 CoT 普遍有效的现有假设，提供了对其局限性的新见解，并为未来研究指明了方向，即开发更精细和有效的推理方法论来提升 LLM 的推理能力。


> Chain-of-Thought (CoT) prompting has been widely recognized for its ability to enhance reasoning capabilities in large language models (LLMs) through the generation of explicit explanatory rationales. However, our study reveals a surprising contradiction to this prevailing perspective. Through extensive experiments involving 16 state-of-the-art LLMs and nine diverse pattern-based in-context learning (ICL) datasets, we demonstrate that CoT and its reasoning variants consistently underperform direct answering across varying model scales and benchmark complexities. To systematically investigate this unexpected phenomenon, we designed extensive experiments to validate several hypothetical explanations. Our analysis uncovers a fundamental explicit-implicit duality driving CoT's performance in pattern-based ICL: while explicit reasoning falters due to LLMs' struggles to infer underlying patterns from demonstrations, implicit reasoning-disrupted by the increased contextual distance of CoT rationales-often compensates, delivering correct answers despite flawed rationales. This duality explains CoT's relative underperformance, as noise from weak explicit inference undermines the process, even as implicit mechanisms partially salvage outcomes. Notably, even long-CoT reasoning models, which excel in abstract and symbolic reasoning, fail to fully overcome these limitations despite higher computational costs. Our findings challenge existing assumptions regarding the universal efficacy of CoT, yielding novel insights into its limitations and guiding future research toward more nuanced and effective reasoning methodologies for LLMs.

[Arxiv](https://arxiv.org/abs/2504.05081)