# Gemma2的全参数持续预训练采用弹性权重固化

发布时间：2025年05月09日

`LLM理论` `持续学习` `大型语言模型`

> Elastic Weight Consolidation for Full-Parameter Continual Pre-Training of Gemma2

# 摘要

> 本技术报告介绍了一项从持续学习视角出发，使用CulturaX中立陶宛语组件的10%数据对Gemma2 20亿参数大型语言模型（LLM）进行自回归预训练的实验。我们在模型的所有参数上应用了弹性权重固化（EWC），并评估了包括Arc、Belebele、Gsm8K、Hellaswag、MMLU、TruthfulQA和Winogrande（英、立陶宛语版本）在内的语言理解基准测试，以及困惑度基准测试。实证研究表明，EWC正则化不仅有效缓解了灾难性遗忘效应，还可能提升大型语言模型在新任务上的学习效果。

> This technical report describes an experiment on autoregressive pre-training of Gemma2 2 billion parameter large language model (LLM) with 10\% on the Lithuanian language component of CulturaX from the point of view of continual learning. We apply elastic weight consolidation (EWC) to the full set of the model's parameters and investigate language understanding benchmarks, consisting of Arc, Belebele, Gsm8K, Hellaswag, MMLU, TruthfulQA, and Winogrande sets (both in English and Lithuanian versions), and perplexity benchmarks. We empirically demonstrate that EWC regularisation allows us not only to mitigate catastrophic forgetting effects but also that it is potentially beneficial for learning of the new task with LLMs.

[Arxiv](https://arxiv.org/abs/2505.05946)