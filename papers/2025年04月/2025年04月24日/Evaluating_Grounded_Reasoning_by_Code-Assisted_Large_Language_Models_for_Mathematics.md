# 评估代码辅助的大型语言模型在数学推理中的能力

发布时间：2025年04月24日

`LLM应用

摘要主要探讨了代码生成辅助在数学推理任务中的应用，评估了生成程序的质量和关联性，属于LLM的应用研究。` `数学推理` `代码生成`

> Evaluating Grounded Reasoning by Code-Assisted Large Language Models for Mathematics

# 摘要

> 代码生成辅助能让大型语言模型（LLMs）在数学推理任务中表现更出色，但目前的评估方法大多只关注程序能否正确执行，忽视了对生成程序本身的严格考察。本研究通过深入分析代码辅助LLMs在数学推理任务中生成的程序，填补了这一研究空白。我们重点评估了LLMs生成的程序在多大程度上基于数学规则，以及这种关联性如何影响最终表现。为此，我们对五种不同LLMs在两个数学数据集上的生成结果进行了人工和自动化的双重评估。研究发现，程序的关联性分布受LLMs能力及数学问题难度的影响。值得注意的是，数学关联性对闭源模型更为有效，而开源模型则未能正确运用数学规则解决问题。在MATH500数据集中，与ASDiv基础问题相比，基于数学规则的程序比例减少了一半，而未关联的程序生成数量则翻倍。这表明我们需要更深入的评估方法，以全面理解代码辅助LLMs在数学领域的潜力与限制。

> Assisting LLMs with code generation improved their performance on mathematical reasoning tasks. However, the evaluation of code-assisted LLMs is generally restricted to execution correctness, lacking a rigorous evaluation of their generated programs. In this work, we bridge this gap by conducting an in-depth analysis of code-assisted LLMs' generated programs in response to math reasoning tasks. Our evaluation focuses on the extent to which LLMs ground their programs to math rules, and how that affects their end performance. For this purpose, we assess the generations of five different LLMs, on two different math datasets, both manually and automatically. Our results reveal that the distribution of grounding depends on LLMs' capabilities and the difficulty of math problems. Furthermore, mathematical grounding is more effective for closed-source models, while open-source models fail to employ math rules in their solutions correctly. On MATH500, the percentage of grounded programs decreased to half, while the ungrounded generations doubled in comparison to ASDiv grade-school problems. Our work highlights the need for in-depth evaluation beyond execution accuracy metrics, toward a better understanding of code-assisted LLMs' capabilities and limits in the math domain.

[Arxiv](https://arxiv.org/abs/2504.17665)