# 受损但未崩溃：重新审视视觉指令微调中受损数据的影响

发布时间：2025年02月18日

`LLM应用` `多模态模型`

> Corrupted but Not Broken: Rethinking the Impact of Corrupted Data in Visual Instruction Tuning

# 摘要

> 视觉指令微调（VIT）能够提升多模态大语言模型（MLLMs）的能力，但其效果受到破损数据集的限制，这些数据集包含幻觉内容、错误回答以及低质量OCR内容。尽管先前研究主要通过高质量数据收集或基于规则的过滤来优化数据集，但这些方法成本高昂或仅适用于特定类型的破损数据。为了深入理解破损数据对MLLMs性能的影响，我们系统性地研究了这一问题，发现破损数据虽会降低MLLMs的性能，但其影响大多停留在表面：MLLMs的性能可以通过禁用一小部分参数或使用少量干净数据进行后训练来很大程度上恢复。此外，经过破损数据训练的MLLMs在区分干净样本和破损样本方面表现出更强的能力，从而能够在无需外部帮助的情况下完成数据集的清理工作。基于这些洞察，我们提出了一种结合自验证和后训练的抗破损训练范式，该方法显著优于现有的破损数据缓解策略。

> Visual Instruction Tuning (VIT) enhances Multimodal Large Language Models (MLLMs) but it is hindered by corrupted datasets containing hallucinated content, incorrect responses, and poor OCR quality. While prior works focus on dataset refinement through high-quality data collection or rule-based filtering, they are costly or limited to specific types of corruption. To deeply understand how corrupted data affects MLLMs, in this paper, we systematically investigate this issue and find that while corrupted data degrades the performance of MLLMs, its effects are largely superficial in that the performance of MLLMs can be largely restored by either disabling a small subset of parameters or post-training with a small amount of clean data. Additionally, corrupted MLLMs exhibit improved ability to distinguish clean samples from corrupted ones, enabling the dataset cleaning without external help. Based on those insights, we propose a corruption-robust training paradigm combining self-validation and post-training, which significantly outperforms existing corruption mitigation strategies.

[Arxiv](https://arxiv.org/abs/2502.12635)