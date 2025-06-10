# 大型语言模型能否生成可靠的测试用例生成器？一项针对竞赛级编程问题的研究

发布时间：2025年06月07日

`LLM应用` `软件工程` `测试与验证`

> Can LLMs Generate Reliable Test Case Generators? A Study on Competition-Level Programming Problems

# 摘要

> 大型语言模型（LLMs）在代码生成方面表现出色，能够处理复杂的推理任务。然而，关于通过生成测试用例将LLMs用于代码检查或调试的研究仍处于探索阶段。我们从竞赛级编程（CP）程序的角度出发，提出TCGBench——一个用于评估LLM生成测试用例生成器能力的基准测试。该基准测试包含两个任务：一是为给定的CP问题生成有效的测试用例生成器，二是生成能够揭示人类编写代码中错误的定向测试用例生成器。实验结果表明，尽管最先进的LLMs在大多数情况下能够生成有效的测试用例生成器，但大多数LLMs在生成能够有效揭示人类代码缺陷的定向测试用例方面仍存在困难。特别地，即使是先进的推理模型（如o3-mini）在生成定向生成器的任务中也远逊于人类的表现。此外，我们构建了一个高质量、人工精选的用于生成定向生成器的指令数据集。分析表明，借助这一数据集，通过提示或微调，LLMs的性能可以得到显著提升。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in code generation, capable of tackling complex tasks during inference. However, the extent to which LLMs can be utilized for code checking or debugging through test case generation remains largely unexplored. We investigate this problem from the perspective of competition-level programming (CP) programs and propose TCGBench, a Benchmark for (LLM generation of) Test Case Generators. This benchmark comprises two tasks, aimed at studying the capabilities of LLMs in (1) generating valid test case generators for a given CP problem, and further (2) generating targeted test case generators that expose bugs in human-written code. Experimental results indicate that while state-of-the-art LLMs can generate valid test case generators in most cases, most LLMs struggle to generate targeted test cases that reveal flaws in human code effectively. Especially, even advanced reasoning models (e.g., o3-mini) fall significantly short of human performance in the task of generating targeted generators. Furthermore, we construct a high-quality, manually curated dataset of instructions for generating targeted generators. Analysis demonstrates that the performance of LLMs can be enhanced with the aid of this dataset, by both prompting and fine-tuning.

[Arxiv](https://arxiv.org/abs/2506.06821)