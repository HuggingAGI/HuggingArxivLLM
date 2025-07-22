# ASPERA：用于评估复杂动作执行规划的仿真环境

发布时间：2025年07月21日

`LLM应用` `智能助手` `任务自动化`

> ASPERA: A Simulated Environment to Evaluate Planning for Complex Action Execution

# 摘要

> 本研究旨在评估大型语言模型（LLMs）在驱动具备复杂操作能力的数字助手方面的潜力。这些助手通过预训练的编程知识，将助手库中的对象和函数组合成操作执行程序，从而实现多步骤目标。为此，我们开发了ASPERA框架，它包含一个助手库模拟器和一个由人类辅助的LLM数据生成引擎。我们的引擎使开发人员能够引导LLM生成高质量的任务，包括复杂的用户查询、模拟状态和相应的验证程序，从而应对数据可用性和评估鲁棒性的挑战。我们还发布了Asper-Bench，这是一个包含250个挑战性任务的评估数据集，这些任务由ASPERA生成。通过这个数据集，我们展示了基于定制助手库的程序生成对LLMs来说是一个重大挑战，相较于无需依赖的代码生成。

> This work evaluates the potential of large language models (LLMs) to power digital assistants capable of complex action execution. These assistants rely on pre-trained programming knowledge to execute multi-step goals by composing objects and functions defined in assistant libraries into action execution programs. To achieve this, we develop ASPERA, a framework comprising an assistant library simulation and a human-assisted LLM data generation engine. Our engine allows developers to guide LLM generation of high-quality tasks consisting of complex user queries, simulation state and corresponding validation programs, tackling data availability and evaluation robustness challenges. Alongside the framework we release Asper-Bench, an evaluation dataset of 250 challenging tasks generated using ASPERA, which we use to show that program generation grounded in custom assistant libraries is a significant challenge to LLMs compared to dependency-free code generation.

[Arxiv](https://arxiv.org/abs/2507.15501)