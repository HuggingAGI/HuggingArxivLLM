# 视觉问答基准中方差的评估

发布时间：2025年08月04日

`LLM应用` `视觉问答` `评估方法`

> Evaluating Variance in Visual Question Answering Benchmarks

# 摘要

> 多模态大型语言模型（MLLMs）作为强大的工具，能够实现跨视觉和文本模态的推理和上下文理解，从而在视觉问答（VQA）任务中表现出色。尽管取得了显著进展，但目前对MLLMs在VQA基准上的评估往往依赖于点估计，忽视了随机模型输出、训练种子敏感性以及超参数配置等因素导致的显著性能波动。本研究系统性地分析了广泛使用的14个视觉问答基准，涵盖视觉推理、文本理解以及常识推理等多样化任务，并深入探讨了训练种子、框架非确定性、模型规模以及扩展指令微调等因素对性能波动的影响。此外，我们还探索了Cloze式评估作为替代评估策略，研究其在降低随机性、提升评估可靠性方面的作用。研究结果揭示了当前评估实践的局限性，并呼吁采用考虑性能波动的方法，以促进更加稳健和可靠的多模态大型语言模型开发。

> Multimodal large language models (MLLMs) have emerged as powerful tools for visual question answering (VQA), enabling reasoning and contextual understanding across visual and textual modalities. Despite their advancements, the evaluation of MLLMs on VQA benchmarks often relies on point estimates, overlooking the significant variance in performance caused by factors such as stochastic model outputs, training seed sensitivity, and hyperparameter configurations. This paper critically examines these issues by analyzing variance across 14 widely used VQA benchmarks, covering diverse tasks such as visual reasoning, text understanding, and commonsense reasoning. We systematically study the impact of training seed, framework non-determinism, model scale, and extended instruction finetuning on performance variability. Additionally, we explore Cloze-style evaluation as an alternate assessment strategy, studying its effectiveness in reducing stochasticity and improving reliability across benchmarks. Our findings highlight the limitations of current evaluation practices and advocate for variance-aware methodologies to foster more robust and reliable development of MLLMs.

[Arxiv](https://arxiv.org/abs/2508.02645)