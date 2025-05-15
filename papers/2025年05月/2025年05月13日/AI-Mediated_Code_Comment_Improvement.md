# AI辅助代码注释优化

发布时间：2025年05月13日

`LLM应用` `软件工程`

> AI-Mediated Code Comment Improvement

# 摘要

> 本文提出了一种通过定制化AI工具重写代码注释的方法，旨在从多个质量维度提升注释质量。我们通过实证研究和扎根理论的定性分析，确定了需要优化的关键质量维度。随后，我们设计了一个基于大型语言模型（LLM）的流程，沿这些维度优化现有代码注释。我们采用GPT-4o实现了该流程，并将结果提炼成一个可在内部运行的轻量化模型，确保用户的数据控制权。我们分别对GPT-4o和提炼模型进行了全面评估，结果表明我们的方法显著提升了代码注释的质量。所有数据和源代码均已在线开放，以支持研究的可重复性。

> This paper describes an approach to improve code comments along different quality axes by rewriting those comments with customized Artificial Intelligence (AI)-based tools. We conduct an empirical study followed by grounded theory qualitative analysis to determine the quality axes to improve. Then we propose a procedure using a Large Language Model (LLM) to rewrite existing code comments along the quality axes. We implement our procedure using GPT-4o, then distil the results into a smaller model capable of being run in-house, so users can maintain data custody. We evaluate both our approach using GPT-4o and the distilled model versions. We show in an evaluation how our procedure improves code comments along the quality axes. We release all data and source code in an online repository for reproducibility.

[Arxiv](https://arxiv.org/abs/2505.09021)