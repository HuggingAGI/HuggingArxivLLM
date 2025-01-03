# 任务校准：大型语言模型在推理任务中的校准

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在推理任务中的性能问题，并提出了一种基于互信息的零-shot推理校准方法（任务校准，TC）。论文的核心在于改进LLMs的推理能力，减少对输入文本与输出标签间虚假相关性的依赖。这属于对LLMs的理论改进和优化，因此分类为LLM理论。` `推理系统`

> Task Calibration: Calibrating Large Language Models on Inference Tasks

# 摘要

> 大型语言模型（LLMs）在推理任务上展现了卓越的零-shot性能，但输入文本与输出标签间的虚假相关性可能限制其推理能力。LLMs往往仅依赖前提或假设进行预测，而非综合考虑两者。为此，我们提出任务校准（TC），一种基于互信息的零-shot推理校准方法，通过任务重构提升LLM性能。TC促使LLMs同时考虑前提和假设进行推理，减少对单一因素的依赖。实验显示，TC在13个零-shot推理任务中表现显著提升，并在少样本设置及多种自然语言理解任务中验证了其有效性。此外，TC对提示模板具有鲁棒性，且易于与其他校准方法结合。

> Large language models (LLMs) have exhibited impressive zero-shot performance on inference tasks. However, LLMs may suffer from spurious correlations between input texts and output labels, which limits LLMs' ability to reason based purely on general language understanding. In other words, LLMs may make predictions primarily based on premise or hypothesis, rather than both components. To address this problem that may lead to unexpected performance degradation, we propose task calibration (TC), a zero-shot and inference-only calibration method inspired by mutual information which recovers LLM performance through task reformulation. TC encourages LLMs to reason based on both premise and hypothesis, while mitigating the models' over-reliance on individual premise or hypothesis for inference. Experimental results show that TC achieves a substantial improvement on 13 inference tasks in the zero-shot setup. We further validate the effectiveness of TC in few-shot setups and various natural language understanding tasks. Further analysis indicates that TC is also robust to prompt templates and has the potential to be integrated with other calibration methods.

[Arxiv](https://arxiv.org/abs/2410.18764)