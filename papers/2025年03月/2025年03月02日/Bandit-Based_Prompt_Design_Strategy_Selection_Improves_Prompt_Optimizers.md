# 基于 Bandit 算法的提示设计策略选择提升提示优化器效果

发布时间：2025年03月02日

`LLM应用` `提示工程`

> Bandit-Based Prompt Design Strategy Selection Improves Prompt Optimizers

# 摘要

> 提示优化旨在寻找能够提升大型语言模型（LLMs）性能的有效提示。虽然现有方法已找到有效提示，但它们与人类专家精心设计的复杂提示仍有差距。提示设计策略作为提升提示性能的最佳实践，是优化提示的关键。最近，自主提示工程工具箱（APET）将多种设计策略融入优化过程。然而，由于LLM优化能力有限，APET的隐式策略选择可能次优。本文提出通过策略选择优化提示（OPTS），引入显式选择机制。我们提出了三种机制，包括基于汤普森采样的方法，并将其整合到知名优化器EvoPrompt中。实验使用BIG-Bench Hard对Llama-3-8B-Instruct和GPT-4o mini的提示进行了优化。结果显示，策略选择提升了EvoPrompt的性能，其中基于汤普森采样的机制表现最佳。实验代码可在GitHub获取。

> Prompt optimization aims to search for effective prompts that enhance the performance of large language models (LLMs). Although existing prompt optimization methods have discovered effective prompts, they often differ from sophisticated prompts carefully designed by human experts. Prompt design strategies, representing best practices for improving prompt performance, can be key to improving prompt optimization. Recently, a method termed the Autonomous Prompt Engineering Toolbox (APET) has incorporated various prompt design strategies into the prompt optimization process. In APET, the LLM is needed to implicitly select and apply the appropriate strategies because prompt design strategies can have negative effects. This implicit selection may be suboptimal due to the limited optimization capabilities of LLMs. This paper introduces Optimizing Prompts with sTrategy Selection (OPTS), which implements explicit selection mechanisms for prompt design. We propose three mechanisms, including a Thompson sampling-based approach, and integrate them into EvoPrompt, a well-known prompt optimizer. Experiments optimizing prompts for two LLMs, Llama-3-8B-Instruct and GPT-4o mini, were conducted using BIG-Bench Hard. Our results show that the selection of prompt design strategies improves the performance of EvoPrompt, and the Thompson sampling-based mechanism achieves the best overall results. Our experimental code is provided at https://github.com/shiralab/OPTS .

[Arxiv](https://arxiv.org/abs/2503.01163)