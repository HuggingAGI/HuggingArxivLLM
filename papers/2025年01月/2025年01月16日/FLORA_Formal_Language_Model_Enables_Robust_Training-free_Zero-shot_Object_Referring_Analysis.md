# FLORA：形式语言模型助力无需训练的零-shot 目标引用分析

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）的推理能力，结合形式语言模型（FLM）来实现零样本对象指代分析（ORA）。虽然涉及了视觉定位和对象检测，但其核心创新点在于利用LLMs进行推理和解析，从而提升零样本ORA的性能。因此，这篇论文应归类为LLM应用。` `计算机视觉`

> FLORA: Formal Language Model Enables Robust Training-free Zero-shot Object Referring Analysis

# 摘要

> # 摘要
对象指代分析（ORA），通常称为指代表达理解，旨在通过自然描述识别和定位图像中的特定对象。与通用对象检测不同，ORA 不仅需要精准的语言理解，还要求精确的视觉定位，因此复杂度更高。尽管近期预训练的大型视觉定位检测器取得了显著进展，但它们依赖大量标注数据和耗时的训练过程。为此，我们提出了一种无需训练的零样本 ORA 框架——FLORA（Formal Language for Object Referring and Analysis）。FLORA 结合了大型语言模型（LLMs）的推理能力，并引入了一种形式语言模型（FLM），该模型通过结构化、基于规则的描述规范语言，从而实现高效的零样本 ORA。FLM 能够在无需训练的情况下，对对象描述进行逻辑驱动的解释。基于 FLM 规范的 LLM 输出，我们进一步设计了贝叶斯推理框架，并采用现成的解释模型完成推理，有效应对 LLM 幻觉问题，并在无需训练的情况下实现出色的 ORA 性能。实验表明，FLORA 将现有预训练定位检测器的零样本性能提升了约 45%。在多个挑战性数据集上的评估也证实，FLORA 在零样本 ORA 相关的检测和分割任务中始终优于当前最先进的零样本方法。我们相信，通过对 LLM 输出的概率解析和推理，FLORA 显著提升了零样本 ORA 的可靠性和可解释性。代码将在论文发表后开源。

> Object Referring Analysis (ORA), commonly known as referring expression comprehension, requires the identification and localization of specific objects in an image based on natural descriptions. Unlike generic object detection, ORA requires both accurate language understanding and precise visual localization, making it inherently more complex. Although recent pre-trained large visual grounding detectors have achieved significant progress, they heavily rely on extensively labeled data and time-consuming learning. To address these, we introduce a novel, training-free framework for zero-shot ORA, termed FLORA (Formal Language for Object Referring and Analysis). FLORA harnesses the inherent reasoning capabilities of large language models (LLMs) and integrates a formal language model - a logical framework that regulates language within structured, rule-based descriptions - to provide effective zero-shot ORA. More specifically, our formal language model (FLM) enables an effective, logic-driven interpretation of object descriptions without necessitating any training processes. Built upon FLM-regulated LLM outputs, we further devise a Bayesian inference framework and employ appropriate off-the-shelf interpretive models to finalize the reasoning, delivering favorable robustness against LLM hallucinations and compelling ORA performance in a training-free manner. In practice, our FLORA boosts the zero-shot performance of existing pretrained grounding detectors by up to around 45%. Our comprehensive evaluation across different challenging datasets also confirms that FLORA consistently surpasses current state-of-the-art zero-shot methods in both detection and segmentation tasks associated with zero-shot ORA. We believe our probabilistic parsing and reasoning of the LLM outputs elevate the reliability and interpretability of zero-shot ORA. We shall release codes upon publication.

[Arxiv](https://arxiv.org/abs/2501.09887)