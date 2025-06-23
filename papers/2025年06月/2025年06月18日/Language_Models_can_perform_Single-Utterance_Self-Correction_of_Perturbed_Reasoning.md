# 语言模型实现单轮自我修正，精准纠正受扰推理

发布时间：2025年06月18日

`LLM理论`

> Language Models can perform Single-Utterance Self-Correction of Perturbed Reasoning

# 摘要

> 大型语言模型（LLMs）在数学推理方面表现优异，但其性能对问题描述和提示策略的微小变化较为敏感。此外，推理过程容易受到采样引发的错误影响，自回归模型主要通过生成额外的tokens进行自我修正。为了深入探究近期模型的自我修正能力，我们设计了实验，测量模型在链式推理（CoT）过程中对人为引入的合成扰动进行自我修正的能力。我们发现，从细微的隐性修正到明确的错误承认和修正，各种开放权重模型和数据集均表现出稳健的单轮内在自我修正行为。研究发现表明，包括那些未针对长链式推理进行微调的模型在内，LLMs可能拥有比现有文献中所展示的更强的内在自我修正能力。这种能力的存在表明，近期的“推理”模型工作可能更多地放大了模型中已显著存在的特质，而非完全重新定义能力。

> Large Language Models (LLMs) have demonstrated impressive mathematical reasoning capabilities, yet their performance remains brittle to minor variations in problem description and prompting strategy. Furthermore, reasoning is vulnerable to sampling-induced errors which autoregressive models must primarily address using self-correction via additionally-generated tokens. To better understand self-correction capabilities of recent models, we conduct experiments measuring models' ability to self-correct synthetic perturbations introduced into their Chain of Thought (CoT) reasoning. We observe robust single-utterance intrinsic self-correction behavior across a range of open-weight models and datasets, ranging from subtle, implicit corrections to explicit acknowledgments and corrections of errors. Our findings suggest that LLMs, including those not finetuned for long CoT, may possess stronger intrinsic self-correction capabilities than commonly shown in the literature. The presence of this ability suggests that recent "reasoning" model work involves amplification of traits already meaningfully present in models.

[Arxiv](https://arxiv.org/abs/2506.15894)