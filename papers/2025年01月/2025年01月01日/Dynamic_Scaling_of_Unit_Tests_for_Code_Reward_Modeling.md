# 代码奖励模型的单元测试动态扩展

发布时间：2025年01月01日

`LLM应用

理由：这篇论文主要讨论了如何通过增加单元测试数量来提高大型语言模型（LLMs）在代码生成任务中的性能。具体来说，论文提出了一个轻量级的单元测试生成器（CodeRM-8B）和一种动态扩展机制，以优化LLMs在复杂推理任务中的表现。这些内容属于LLM在实际应用中的优化和改进，因此归类为LLM应用。` `软件工程` `代码生成`

> Dynamic Scaling of Unit Tests for Code Reward Modeling

# 摘要

> 当前的大型语言模型（LLMs）在处理复杂推理任务（如代码生成）时，往往难以在第一次尝试中生成准确的响应。先前的研究通过生成多个候选解决方案并使用LLM生成的单元测试来验证这些解决方案，以应对这一挑战。然而，由于LLMs总是自信地犯错，这些单元测试并不可靠，从而降低了奖励信号的质量。受到增加解决方案数量可以提高LLM性能的启发，我们探索了增加单元测试数量对提高奖励信号质量的影响。我们的初步实验表明，单元测试数量与奖励信号质量呈正相关，且在更具挑战性的问题中收益更大。基于这些发现，我们提出了CodeRM-8B，一个轻量级但高效的单元测试生成器，能够高效且高质量地扩展单元测试。此外，我们还实现了一种动态扩展机制，根据问题难度调整单元测试的数量，进一步提高了效率。实验结果显示，我们的方法在三个基准测试中显著提升了各种模型的性能（例如，Llama3-8B在HumanEval Plus上的增益为18.43%，GPT-4o-mini的增益为3.42%）。

> Current large language models (LLMs) often struggle to produce accurate responses on the first attempt for complex reasoning tasks like code generation. Prior research tackles this challenge by generating multiple candidate solutions and validating them with LLM-generated unit tests. The execution results of unit tests serve as reward signals to identify correct solutions. As LLMs always confidently make mistakes, these unit tests are not reliable, thereby diminishing the quality of reward signals. Motivated by the observation that scaling the number of solutions improves LLM performance, we explore the impact of scaling unit tests to enhance reward signal quality. Our pioneer experiment reveals a positive correlation between the number of unit tests and reward signal quality, with greater benefits observed in more challenging problems. Based on these insights, we propose CodeRM-8B, a lightweight yet effective unit test generator that enables efficient and high-quality unit test scaling. Additionally, we implement a dynamic scaling mechanism that adapts the number of unit tests based on problem difficulty, further improving efficiency. Experimental results show that our approach significantly improves performance across various models on three benchmarks (e.g., with gains of 18.43% for Llama3-8B and 3.42% for GPT-4o-mini on HumanEval Plus).

[Arxiv](https://arxiv.org/abs/2501.01054)