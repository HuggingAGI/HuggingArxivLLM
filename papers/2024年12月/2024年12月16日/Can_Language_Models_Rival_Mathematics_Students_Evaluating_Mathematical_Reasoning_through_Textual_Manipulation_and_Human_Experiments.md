# 语言模型能否媲美数学学生？通过文本操作与人类实验评估其数学推理能力

发布时间：2024年12月16日

`LLM应用

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在解决组合数学问题上的表现，并对比了不同模型的表现。这属于LLM在实际问题中的应用，因此分类为LLM应用。`

> Can Language Models Rival Mathematics Students? Evaluating Mathematical Reasoning through Textual Manipulation and Human Experiments

# 摘要

> 本文探讨了最新大型语言模型（LLMs）在解决组合数学问题上的表现。我们对比了LLaMA-2、LLaMA-3.1、GPT-4和Mixtral模型，并与有数学竞赛经验的学生进行了比较。为此，我们创建了Combi-Puzzles数据集，包含125个基于25个组合问题的变体，每个问题以五种不同形式呈现，通过对抗性添加、数值变化和语言混淆生成。这些变体保留了数学核心，旨在测试LLM的泛化能力，并确保问题以未见过的形式提交。结果显示，GPT-4模型在生成正确答案上表现最佳，尤其在数学变体上显著优于人类。此外，问题陈述的修改对LLM表现有显著影响，而人类表现则不受影响。

> In this paper we look at the ability of recent large language models (LLMs) at solving mathematical problems in combinatorics. We compare models LLaMA-2, LLaMA-3.1, GPT-4, and Mixtral against each other and against human pupils and undergraduates with prior experience in mathematical olympiads. To facilitate these comparisons we introduce the Combi-Puzzles dataset, which contains 125 problem variants based on 25 combinatorial reasoning problems. Each problem is presented in one of five distinct forms, created by systematically manipulating the problem statements through adversarial additions, numeric parameter changes, and linguistic obfuscation. Our variations preserve the mathematical core and are designed to measure the generalisability of LLM problem-solving abilities, while also increasing confidence that problems are submitted to LLMs in forms that have not been seen as training instances. We found that a model based on GPT-4 outperformed all other models in producing correct responses, and performed significantly better in the mathematical variation of the problems than humans. We also found that modifications to problem statements significantly impact the LLM's performance, while human performance remains unaffected.

[Arxiv](https://arxiv.org/abs/2412.11908)