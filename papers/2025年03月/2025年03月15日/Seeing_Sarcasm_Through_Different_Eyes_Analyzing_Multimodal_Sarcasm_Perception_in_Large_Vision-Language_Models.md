# # 研究摘要：以不同视角看待讽刺：解析大型视觉-语言模型中的多模态讽刺理解

发布时间：2025年03月15日

`LLM应用` `社交媒体`

> Seeing Sarcasm Through Different Eyes: Analyzing Multimodal Sarcasm Perception in Large Vision-Language Models

# 摘要

> 随着大型视觉-语言模型（LVLMs）展现出日益增强的人类化能力，一个关键问题浮现：不同 LVLM 是否对多模态讽刺有着不同的解读，以及单一模型是否能像人类一样从多角度理解讽刺？为探讨这一问题，我们在现有跨模态讽刺数据集上引入了一个分析框架，通过系统设计的提示语进行研究。通过对 12 个最先进的 LVLM 在 2,409 个样本上的评估，我们分析了模型内部和跨模型的解释差异，重点关注置信度水平、与数据集标签的一致性以及对模糊“中性”案例的识别。我们的研究发现显著的差异性——跨 LVLM 以及同一模型在不同提示下。尽管面向分类的提示语能够带来更高的内部一致性，但当模型被赋予解释性推理任务时，它们之间的分歧则变得明显。这些结果通过强调讽刺的主观性，挑战了二元标注范式。我们主张超越 rigid 的标注方案，转向多角度、不确定性感知的建模方式，从而为多模态讽刺理解提供更深入的见解。我们的代码和数据可在 https://github.com/CoderChen01/LVLMSarcasmAnalysis 获取。


> With the advent of large vision-language models (LVLMs) demonstrating increasingly human-like abilities, a pivotal question emerges: do different LVLMs interpret multimodal sarcasm differently, and can a single model grasp sarcasm from multiple perspectives like humans? To explore this, we introduce an analytical framework using systematically designed prompts on existing multimodal sarcasm datasets. Evaluating 12 state-of-the-art LVLMs over 2,409 samples, we examine interpretive variations within and across models, focusing on confidence levels, alignment with dataset labels, and recognition of ambiguous "neutral" cases. Our findings reveal notable discrepancies -- across LVLMs and within the same model under varied prompts. While classification-oriented prompts yield higher internal consistency, models diverge markedly when tasked with interpretive reasoning. These results challenge binary labeling paradigms by highlighting sarcasm's subjectivity. We advocate moving beyond rigid annotation schemes toward multi-perspective, uncertainty-aware modeling, offering deeper insights into multimodal sarcasm comprehension. Our code and data are available at: https://github.com/CoderChen01/LVLMSarcasmAnalysis

[Arxiv](https://arxiv.org/abs/2503.12149)