# 别骗我：大型语言模型中通过注意力重新分配防范煤气灯效应

发布时间：2025年04月13日

`LLM应用` `可信度` `鲁棒性`

> Don't Deceive Me: Mitigating Gaslighting through Attention Reallocation in LMMs

# 摘要

> # 摘要
大型多模态模型（LMMs）在各类任务中展现出了卓越的能力。然而，这些模型在面对用户欺瞒（即用户故意使用误导性或矛盾性输入）时的脆弱性，引发了对其在实际应用中可靠性的严重担忧。本文针对一个新颖且具挑战性的难题展开研究，即如何减轻基于否定的欺瞒对LMMs造成的负面影响。具体而言，当欺骗性用户陈述导致模型准确率显著下降时，我们提出了一种无需重新训练的方法——GasEraser。该方法通过重新分配注意力权重，将误导性文本标记的注意力权重转移至语义显著的视觉区域。通过抑制“注意力陷阱”标记的影响，并强化对视觉依据线索的关注，GasEraser显著提升了LMMs的鲁棒性，且无需重新训练或额外监督。大量实验结果表明，在GaslightingBench基准测试中，GasEraser在多个主流开源LMMs上均表现出有效性。值得注意的是，对于LLaVA-v1.5-7B模型，GasEraser将误导向率降低了48.2%，充分证明了其在打造更加值得信赖的LMMs方面的潜力。

> Large Multimodal Models (LMMs) have demonstrated remarkable capabilities across a wide range of tasks. However, their vulnerability to user gaslighting-the deliberate use of misleading or contradictory inputs-raises critical concerns about their reliability in real-world applications. In this paper, we address the novel and challenging issue of mitigating the negative impact of negation-based gaslighting on LMMs, where deceptive user statements lead to significant drops in model accuracy. Specifically, we introduce GasEraser, a training-free approach that reallocates attention weights from misleading textual tokens to semantically salient visual regions. By suppressing the influence of "attention sink" tokens and enhancing focus on visually grounded cues, GasEraser significantly improves LMM robustness without requiring retraining or additional supervision. Extensive experimental results demonstrate that GasEraser is effective across several leading open-source LMMs on the GaslightingBench. Notably, for LLaVA-v1.5-7B, GasEraser reduces the misguidance rate by 48.2%, demonstrating its potential for more trustworthy LMMs.

[Arxiv](https://arxiv.org/abs/2504.09456)