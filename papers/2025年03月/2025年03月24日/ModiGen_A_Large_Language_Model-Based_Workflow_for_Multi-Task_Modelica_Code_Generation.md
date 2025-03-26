# ModiGen：基于大型语言模型的多任务Modelica代码生成工作流

发布时间：2025年03月24日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在生成Modelica代码中的应用，特别是在复杂物理系统建模中的应用。作者开发了基准数据集，评估了现有LLMs的性能，并提出了一种结合有监督微调、基于图检索的增强生成和反馈优化的工作流来提升生成的准确性和可靠性。这些内容都属于LLM的应用层面，因此归类为LLM应用。`

> ModiGen: A Large Language Model-Based Workflow for Multi-Task Modelica Code Generation

# 摘要

> Modelica 是一种广泛应用于复杂物理系统仿真的语言，但要创建和优化有效的模型，仍需深厚的专业知识。尽管大型语言模型（LLMs）在代码生成方面展现出巨大潜力，但其在建模领域的应用尚未得到充分探索。为填补这一空白，我们开发了专门用于评估 LLMs 在生成 Modelica 组件模型和测试用例方面性能的基准数据集。

我们的评估发现，现有 LLMs 存在明显局限性，生成的代码常无法成功仿真。为克服这些挑战，我们提出了一种结合有监督微调、基于图检索的增强生成以及反馈优化的专用工作流，以提升 Modelica 代码生成的准确性和可靠性。

评估结果表明，我们的方法显著提升了性能：组件生成任务的 pass@1 最大提升达到 0.3349，测试用例生成任务提升为 0.2457。这项研究凸显了 LLMs 在推动智能化建模工具方面的潜力，并为未来系统建模和工程应用的发展提供了宝贵见解。

> Modelica is a widely adopted language for simulating complex physical systems, yet effective model creation and optimization require substantial domain expertise. Although large language models (LLMs) have demonstrated promising capabilities in code generation, their application to modeling remains largely unexplored. To address this gap, we have developed benchmark datasets specifically designed to evaluate the performance of LLMs in generating Modelica component models and test cases. Our evaluation reveals substantial limitations in current LLMs, as the generated code often fails to simulate successfully. To overcome these challenges, we propose a specialized workflow that integrates supervised fine-tuning, graph retrieval-augmented generation, and feedback optimization to improve the accuracy and reliability of Modelica code generation. The evaluation results demonstrate significant performance gains: the maximum improvement in pass@1 reached 0.3349 for the component generation task and 0.2457 for the test case generation task. This research underscores the potential of LLMs to advance intelligent modeling tools and offers valuable insights for future developments in system modeling and engineering applications.

[Arxiv](https://arxiv.org/abs/2503.18460)