# MatTools：用于材料科学工具的大型语言模型基准测试

发布时间：2025年05月16日

`LLM应用` `材料科学` `人工智能`

> MatTools: Benchmarking Large Language Models for Materials Science Tools

# 摘要

> 大型语言模型（LLMs）正广泛应用于材料科学领域，涵盖文献理解、性质预测、材料发现及合金设计等方向。与此同时，基于物理的计算方法不断涌现，为材料性质的计算提供了新途径。在此，我们提出了一种基准应用，旨在通过生成和安全执行基于物理计算材料科学软件包的代码，评估LLMs解答材料科学问题的能力。MatTools 由两个互补组件构成：材料模拟工具问答（QA）基准与真实世界工具使用基准。我们开发了一种自动化方法，用于高效收集真实世界中材料科学工具使用案例。该 QA 基准基于 pymatgen（Python 材料基因组）代码库和文档，包含 69,225 个 QA 对，用于评估 LLM 对材料科学工具的理解能力。真实世界基准包含 49 个任务（138 个子任务），要求生成用于材料性质计算的功能性 Python 代码。我们对多种 LLM 的评估揭示了三个关键发现：（1）通用型模型表现更优；（2）AI 了解 AI；（3）简单即更好。MatTools 为评估和提升 LLM 在材料科学工具应用中的能力提供了标准化框架，助力更高效的 AI 系统在材料科学与一般科学研究中的开发。


> Large language models (LLMs) are increasingly applied to materials science questions, including literature comprehension, property prediction, materials discovery and alloy design. At the same time, a wide range of physics-based computational approaches have been developed in which materials properties can be calculated. Here, we propose a benchmark application to evaluate the proficiency of LLMs to answer materials science questions through the generation and safe execution of codes based on such physics-based computational materials science packages. MatTools is built on two complementary components: a materials simulation tool question-answer (QA) benchmark and a real-world tool-usage benchmark. We designed an automated methodology to efficiently collect real-world materials science tool-use examples. The QA benchmark, derived from the pymatgen (Python Materials Genomics) codebase and documentation, comprises 69,225 QA pairs that assess the ability of an LLM to understand materials science tools. The real-world benchmark contains 49 tasks (138 subtasks) requiring the generation of functional Python code for materials property calculations. Our evaluation of diverse LLMs yields three key insights: (1)Generalists outshine specialists;(2)AI knows AI; and (3)Simpler is better. MatTools provides a standardized framework for assessing and improving LLM capabilities for materials science tool applications, facilitating the development of more effective AI systems for materials science and general scientific research.

[Arxiv](https://arxiv.org/abs/2505.10852)