# FairCode: 评估LLM在代码生成中的社会偏见

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要关注的是大型语言模型（LLMs）在代码生成中的应用，特别是如何评估和减少代码生成中的偏见。论文提出了一个新的基准（FairCode）和评估指标（FairScore），用于评估LLMs在代码生成任务中的表现。这属于LLM在实际应用中的具体问题，因此归类为“LLM应用”。` `软件工程` `人工智能`

> FairCode: Evaluating Social Bias of LLMs in Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成方面表现出色，但其输出质量和安全性评估日益受到关注。然而，代码生成中的偏见研究仍显不足。现有研究多通过恶意提示或重新应用任务和数据集来评估偏见，但这些数据集并未针对代码任务优化。鉴于LLMs通常与人类价值观一致，且现有数据集未完全适配代码任务，亟需专门评估代码模型的基准。本研究推出FairCode，一个评估代码生成偏见的新基准，包含函数实现和测试用例生成两个任务，通过多样化场景评估社会偏见。我们还提出新指标FairScore，用于评估模型在此基准上的表现。实验在多个LLMs上进行，结果显示所有模型均存在偏见。代码详见https://github.com/YongkDu/FairCode。

> Large language models (LLMs) have demonstrated significant capability in code generation, drawing increasing attention to the evaluation of the quality and safety of their outputs. However, research on bias in code generation remains limited. Existing studies typically assess bias by applying malicious prompts or reapply tasks and dataset for discriminative models. Given that LLMs are often aligned with human values and that prior datasets are not fully optimized for code-related tasks, there is a pressing need for benchmarks specifically designed for evaluating code models. In this study, we introduce FairCode, a novel benchmark for evaluating bias in code generation. FairCode comprises two tasks: function implementation and test case generation, each evaluating social bias through diverse scenarios. Additionally, we propose a new metric, FairScore, to assess model performance on this benchmark. We conduct experiments on widely used LLMs and provide a comprehensive analysis of the results. The findings reveal that all tested LLMs exhibit bias. The code is available at https://github.com/YongkDu/FairCode.

[Arxiv](https://arxiv.org/abs/2501.05396)