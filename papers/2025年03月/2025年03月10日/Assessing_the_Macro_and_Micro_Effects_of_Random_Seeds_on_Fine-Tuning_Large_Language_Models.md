# 评估随机种子对大模型微调的宏观与微观影响

发布时间：2025年03月10日

`LLM理论` `机器学习`

> Assessing the Macro and Micro Effects of Random Seeds on Fine-Tuning Large Language Models

# 摘要

> 尽管随机种子可能对模型性能产生影响，但在微调大型语言模型 (LLMs) 时，这一因素却常被忽视。本研究系统评估了随机种子对 LLMs 的影响，采用 GLUE 和 SuperGLUE 基准进行分析。我们通过准确率和 F1 等传统指标考察宏观影响，计算均值和方差以量化性能波动。为捕捉微观影响，我们引入“一致性”指标，衡量个体预测的稳定性。实验结果表明，随机种子在宏观和微观层面均引发显著波动，凸显了在微调和评估中谨慎选择随机种子的重要性。

> The impact of random seeds in fine-tuning large language models (LLMs) has been largely overlooked despite its potential influence on model performance.In this study, we systematically evaluate the effects of random seeds on LLMs using the GLUE and SuperGLUE benchmarks. We analyze the macro-level impact through traditional metrics like accuracy and F1, calculating their mean and variance to quantify performance fluctuations. To capture the micro-level effects, we introduce a novel metric, consistency, measuring the stability of individual predictions across runs. Our experiments reveal significant variance at both macro and micro levels, underscoring the need for careful consideration of random seeds in fine-tuning and evaluation.

[Arxiv](https://arxiv.org/abs/2503.07329)