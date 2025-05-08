# 探索利用执行轨迹提升代码大语言模型程序修复效果的方法

发布时间：2025年05月07日

`LLM应用

理由：这篇论文探讨了大型语言模型在自动程序修复任务中的应用，通过引入程序执行轨迹来增强模型的修复能力。它属于LLM的应用层面，具体涉及如何在编程任务中利用LLM进行改进。` `软件工程`

> Towards Effectively Leveraging Execution Traces for Program Repair with Code LLMs

# 摘要

> 大型语言模型（LLMs）在包括自动程序修复（APR）在内的多种编程任务中展现出极具潜力的表现。然而，现有的基于LLM的自动程序修复方法大多局限于对程序的静态分析，而忽略了程序的运行时行为。受知识增强自然语言处理的启发，本研究通过在标准的APR提示中加入程序执行轨迹，弥补了这一潜在的盲点。我们采用GPT系列模型对三个流行的APR数据集进行了评估。研究结果表明，仅将执行轨迹融入提示相较于不使用轨迹的基线模型，仅在6种测试的模型/数据集配置中的2种取得了性能提升。我们进一步发现，执行轨迹对APR的有效性会随着其复杂度的增加而减弱。我们探讨了在提示中利用轨迹的多种策略，并证明了经过优化的LLM提示能够更一致地超越不使用轨迹的提示。此外，我们还表明，基于轨迹的提示方法优于在小规模数据集上微调小型LLM；并通过探查研究强化了执行轨迹能够补充LLMs推理能力的观点。

> Large Language Models (LLMs) show promising performance on various programming tasks, including Automatic Program Repair (APR). However, most approaches to LLM-based APR are limited to the static analysis of the programs, while disregarding their runtime behavior. Inspired by knowledge-augmented NLP, in this work, we aim to remedy this potential blind spot by augmenting standard APR prompts with program execution traces. We evaluate our approach using the GPT family of models on three popular APR datasets. Our findings suggest that simply incorporating execution traces into the prompt provides a limited performance improvement over trace-free baselines, in only 2 out of 6 tested dataset / model configurations. We further find that the effectiveness of execution traces for APR diminishes as their complexity increases. We explore several strategies for leveraging traces in prompts and demonstrate that LLM-optimized prompts help outperform trace-free prompts more consistently. Additionally, we show trace-based prompting to be superior to finetuning a smaller LLM on a small-scale dataset; and conduct probing studies reinforcing the notion that execution traces can complement the reasoning abilities of the LLMs.

[Arxiv](https://arxiv.org/abs/2505.04441)