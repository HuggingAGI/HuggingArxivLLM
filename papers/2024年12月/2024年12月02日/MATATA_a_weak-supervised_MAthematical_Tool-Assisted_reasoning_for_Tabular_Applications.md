# MATATA：针对表格应用的弱监督数学工具辅助推理

发布时间：2024年12月02日

`Agent` `数据处理`

> MATATA: a weak-supervised MAthematical Tool-Assisted reasoning for Tabular Applications

# 摘要

> 数学推理能力在工具增强型语言代理的助力下日益提升，然而现有方法往往依赖于闭源或大型模型、外部数据，亦或大量的提示工程。本研究推出了 MATATA，这是一种创新且经济高效的方法，用于通过推理、规划和工具运用来训练处理表格数据问题的 LLM 代理。凭借逐步的自我改进模式和迭代式弱监督，它为 3.8B/8B 小型语言模型（SLM）赋能，尤其适用于本地托管以及数据隐私至关重要的敏感业务场景。通过在不同数据集上运用灵活且可复用的工具，它在共享任务中展现出强大的性能和出色的可扩展性。实验表明，在基于开源模型的推理框架中，MATATA 在 FinQA 和 TAT-QA 上达到了顶尖水平。此外，MATATA 模型在 TabMWP 上可与基于 GPT-4 的框架相媲美，并且它属于 SLM。

> Mathematical reasoning capabilities are increasing with tool-augmented language agents, but methods often rely either on closed-source or large models, external data, or extensive prompt engineering. This work introduces MATATA, a novel cost-effective method to train LLM agents for tabular data problems through reasoning, planning, and tool use. With a progressive self-improvement paradigm and an iterative weak supervision, it empowers 3.8B/8B Small Language Models (SLMs), particularly suited for local hosting and sensitive business contexts where data privacy is crucial. By employing a flexible and reusable tools across different datasets, it achieves robust performance with effective scalability across shared tasks. Experiments show that MATATA reaches state-of-the-art performances on FinQA and TAT-QA among reasoning frameworks based on open-source models. Moreover, MATATA models compete with GPT-4 based frameworks on TabMWP, while being SLMs.

[Arxiv](https://arxiv.org/abs/2411.18915)