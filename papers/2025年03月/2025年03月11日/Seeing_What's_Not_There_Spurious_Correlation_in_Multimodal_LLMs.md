# 看见并不存在的东西：多模态大语言模型中的虚假关联

发布时间：2025年03月11日

`LLM应用` `人工智能` `计算机视觉`

> Seeing What's Not There: Spurious Correlation in Multimodal LLMs

# 摘要

> 单模态视觉模型容易受错误相关性影响，但即使引入语言监督，多模态大型语言模型（MLLMs）是否同样存在这一问题仍不明朗。本文深入研究了MLLMs中的错误偏见问题，并推出了一款创新工具SpurLens，它巧妙结合GPT-4和开放集目标检测器，能够自动识别错误视觉线索，完全无需人工干预。研究发现，错误相关性给MLLMs带来两大主要问题：(1) 在物体识别任务中过度依赖错误线索，移除这些线索会导致准确率显著下降；(2) 物体幻觉现象，错误线索会使幻觉程度加剧10倍以上。我们在多种MLLMs和数据集上验证了这一发现。除了诊断这些问题，我们还探索了多种潜在的解决方案，包括提示集成和基于推理的提示方法，并通过消融研究深入探究了MLLMs中错误偏见的根本原因。本研究揭示了错误相关性问题的普遍性，呼吁学界和业界采用更严格的评估方法和缓解策略，以提升MLLMs的可靠性和实用性。

> Unimodal vision models are known to rely on spurious correlations, but it remains unclear to what extent Multimodal Large Language Models (MLLMs) exhibit similar biases despite language supervision. In this paper, we investigate spurious bias in MLLMs and introduce SpurLens, a pipeline that leverages GPT-4 and open-set object detectors to automatically identify spurious visual cues without human supervision. Our findings reveal that spurious correlations cause two major failure modes in MLLMs: (1) over-reliance on spurious cues for object recognition, where removing these cues reduces accuracy, and (2) object hallucination, where spurious cues amplify the hallucination by over 10x. We validate our findings in various MLLMs and datasets. Beyond diagnosing these failures, we explore potential mitigation strategies, such as prompt ensembling and reasoning-based prompting, and conduct ablation studies to examine the root causes of spurious bias in MLLMs. By exposing the persistence of spurious correlations, our study calls for more rigorous evaluation methods and mitigation strategies to enhance the reliability of MLLMs.

[Arxiv](https://arxiv.org/abs/2503.08884)