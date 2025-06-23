# 基于 LLM 的字符串需求满足性验证：借助一致数据与检查器构建

发布时间：2025年06月19日

`LLM应用` `软件工程` `测试与验证`

> LLM-based Satisfiability Checking of String Requirements by Consistent Data and Checker Generation

# 摘要

> 字符串需求在软件系统中至关重要，因其通常以自然语言（NL）形式表达，而软件系统高度依赖字符串操作。虽然单独分析单个需求相对容易，但验证一组自然语言需求的属性（如可满足性）极具挑战性。形式化方法（如SMT求解器）虽能高效验证这些属性，但存在理论限制。此外，将自然语言需求转换为形式化约束往往需要大量手动工作。最近，大型语言模型（LLMs）在形式化推理任务中展现出潜力，但其在验证字符串需求方面的效果尚待研究。本文提出一种混合方法，利用LLMs（1）推导可满足性结果并生成一致字符串（若可能），（2）生成声明式（SMT）和命令式（Python）检查器，以验证结果的正确性。实验评估了四种LLMs的表现。结果显示，LLMs能有效将自然语言转换为检查器，Python检查器甚至达到完美测试准确性。这些检查器显著提升了LLMs生成一致字符串和准确识别不可满足需求的能力，使生成成功率和F1分数在某些情况下较基线（无检查器）提升一倍以上。

> Requirements over strings, commonly represented using natural language (NL), are particularly relevant for software systems due to their heavy reliance on string data manipulation. While individual requirements can usually be analyzed manually, verifying properties (e.g., satisfiability) over sets of NL requirements is particularly challenging. Formal approaches (e.g., SMT solvers) may efficiently verify such properties, but are known to have theoretical limitations. Additionally, the translation of NL requirements into formal constraints typically requires significant manual effort. Recently, large language models (LLMs) have emerged as an alternative approach for formal reasoning tasks, but their effectiveness in verifying requirements over strings is less studied. In this paper, we introduce a hybrid approach that verifies the satisfiability of NL requirements over strings by using LLMs (1) to derive a satisfiability outcome (and a consistent string, if possible), and (2) to generate declarative (i.e., SMT) and imperative (i.e., Python) checkers, used to validate the correctness of (1). In our experiments, we assess the performance of four LLMs. Results show that LLMs effectively translate natural language into checkers, even achieving perfect testing accuracy for Python-based checkers. These checkers substantially help LLMs in generating a consistent string and accurately identifying unsatisfiable requirements, leading to more than doubled generation success rate and F1-score in certain cases compared to baselines without generated checkers.

[Arxiv](https://arxiv.org/abs/2506.16639)