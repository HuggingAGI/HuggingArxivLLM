# 利用推理模型生成解决组合设计问题中开放实例的搜索启发式方法

发布时间：2025年05月29日

`LLM应用` `组合设计` `计算机科学`

> Using Reasoning Models to Generate Search Heuristics that Solve Open Instances of Combinatorial Design Problems

# 摘要

> 具备推理能力的大型语言模型（LLMs）在生成和优化答案之前会进行迭代，这在数学和代码生成等应用场景中展现出显著优势。我们采用具备推理能力的LLMs进行代码生成，将其应用于组合设计领域中的特定任务。该领域研究了多种类型的组合设计，其中许多设计仍存在未解决的开放实例。Constructive Protocol CPro1通过LLMs生成搜索启发式策略，这些策略有望为小型开放实例构建解决方案。CPro1以特定类型设计的文本定义和有效性验证器为起点，引导LLMs选择并实施策略，同时提供自动超参数调整和执行反馈。在2006年《组合设计手册》中选取的16个组合设计问题中，CPro1结合推理型LLMs成功解决了其中7个问题的长期开放实例，包括3个全新解决的实例（Bhaskar Rao设计、对称称重矩阵、平衡三元设计），这些问题在使用不具备推理能力的LLMs时未能解决。此外，CPro1还解决了近期（2025年）文献中多个问题的开放实例，生成了新的覆盖序列、Johnson团覆盖、删除码以及一个均匀嵌套的Steiner四元系统。

> Large Language Models (LLMs) with reasoning are trained to iteratively generate and refine their answers before finalizing them, which can help with applications to mathematics and code generation. We apply code generation with reasoning LLMs to a specific task in the mathematical field of combinatorial design. This field studies diverse types of combinatorial designs, many of which have lists of open instances for which existence has not yet been determined. The Constructive Protocol CPro1 uses LLMs to generate search heuristics that have the potential to construct solutions to small open instances. Starting with a textual definition and a validity verifier for a particular type of design, CPro1 guides LLMs to select and implement strategies, while providing automated hyperparameter tuning and execution feedback. CPro1 with reasoning LLMs successfully solves long-standing open instances for 7 of 16 combinatorial design problems selected from the 2006 Handbook of Combinatorial Designs, including new solved instances for 3 of these (Bhaskar Rao Designs, Symmetric Weighing Matrices, Balanced Ternary Designs) that were unsolved by CPro1 with non-reasoning LLMs. It also solves open instances for several problems from recent (2025) literature, generating new Covering Sequences, Johnson Clique Covers, Deletion Codes, and a Uniform Nested Steiner Quadruple System.

[Arxiv](https://arxiv.org/abs/2505.23881)