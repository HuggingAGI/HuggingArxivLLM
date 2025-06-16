# 提示工程与框架：指南驱动的实现，提升LLMs代码可靠性

发布时间：2025年03月19日

`LLM应用` `软件开发`

> Prompt engineering and framework: implementation to increase code reliability based guideline for LLMs

# 摘要

> 本文提出了一种创新的提示方法，旨在显著提升大型语言模型（LLMs）生成准确Python代码的能力。我们设计了一个专门的提示模板，能够有效提高代码片段的质量和正确性，确保其通过测试并输出可靠结果。通过在HumanEval数据集上对两个先进LLMs进行的实验表明，我们的方法在Pass@k指标上显著优于现有的零-shot和Chain-of-Thought（CoT）方法。值得一提的是，与CoT方法相比，我们的方案在保证性能提升的同时，大幅降低了令牌使用量，展现出更高的资源利用效率。这不仅降低了计算需求，也优化了LLM的环境影响。这些研究成果表明，通过定制化的提示策略，我们可以显著优化代码生成性能，为AI驱动的编程任务开辟了更广阔的应用前景。

> In this paper, we propose a novel prompting approach aimed at enhancing the ability of Large Language Models (LLMs) to generate accurate Python code. Specifically, we introduce a prompt template designed to improve the quality and correctness of generated code snippets, enabling them to pass tests and produce reliable results. Through experiments conducted on two state-of-the-art LLMs using the HumanEval dataset, we demonstrate that our approach outperforms widely studied zero-shot and Chain-of-Thought (CoT) methods in terms of the Pass@k metric. Furthermore, our method achieves these improvements with significantly reduced token usage compared to the CoT approach, making it both effective and resource-efficient, thereby lowering the computational demands and improving the eco-footprint of LLM capabilities. These findings highlight the potential of tailored prompting strategies to optimize code generation performance, paving the way for broader applications in AI-driven programming tasks.

[Arxiv](https://arxiv.org/abs/2506.10989)