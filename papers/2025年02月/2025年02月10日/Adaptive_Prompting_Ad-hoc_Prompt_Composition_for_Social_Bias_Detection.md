# 自适应提示：面向社会偏见检测的临时提示创作

发布时间：2025年02月10日

`LLM应用` `社会偏见检测`

> Adaptive Prompting: Ad-hoc Prompt Composition for Social Bias Detection

# 摘要

> 指令微调技术的最新进展推动了多种大语言模型提示方法的开发，如显式推理提示。然而，这些方法的效果受任务类型、模型特性和上下文内容等多重因素影响。因此，寻找有效的提示方案往往需要反复尝试。现有自动提示方法多专注于优化单一技术，而忽视了技术组合及其对输入依赖的重要性。针对这一问题，我们提出了一种自适应提示方法，能够针对具体输入动态预测最优的提示组合。我们将其应用于社会偏见检测这一高度依赖上下文且需要语义理解的任务。实验中，我们使用三个大型语言模型在三个数据集上进行了评估，对比了技术组合与单一技术及其他基线方法的表现。结果表明，找到有效的提示组合至关重要。我们的方法在多个实验设置中均展现出稳健的高性能检测能力。此外，初步实验也验证了该方法在其它任务上的良好泛化能力。

> Recent advances on instruction fine-tuning have led to the development of various prompting techniques for large language models, such as explicit reasoning steps. However, the success of techniques depends on various parameters, such as the task, language model, and context provided. Finding an effective prompt is, therefore, often a trial-and-error process. Most existing approaches to automatic prompting aim to optimize individual techniques instead of compositions of techniques and their dependence on the input. To fill this gap, we propose an adaptive prompting approach that predicts the optimal prompt composition ad-hoc for a given input. We apply our approach to social bias detection, a highly context-dependent task that requires semantic understanding. We evaluate it with three large language models on three datasets, comparing compositions to individual techniques and other baselines. The results underline the importance of finding an effective prompt composition. Our approach robustly ensures high detection performance, and is best in several settings. Moreover, first experiments on other tasks support its generalizability.

[Arxiv](https://arxiv.org/abs/2502.06487)