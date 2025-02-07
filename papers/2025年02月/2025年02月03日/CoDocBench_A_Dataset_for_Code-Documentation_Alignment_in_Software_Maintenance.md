# CoDocBench: 软件维护中代码与文档对齐的数据集

发布时间：2025年02月03日

`LLM应用

理由：这篇论文讨论了使用大型语言模型（如Llama-3.1 405B和Mixtral 8×22B）来处理代码变更相关的任务，特别是生成代码编辑和变更描述。这属于将大型语言模型应用于特定领域（软件维护）的实际应用场景，因此归类为“LLM应用”。` `软件工程` `代码维护`

> CoDocBench: A Dataset for Code-Documentation Alignment in Software Maintenance

# 摘要

> 软件维护的核心任务之一是理解和开发代码变更。给定一个函数期望新操作的自然语言描述，代理（人类或AI）可能需要生成对该函数的一组编辑以实现新操作；同样，给定一组对函数的编辑，代理可能需要生成该函数新操作的变更描述。因此，训练一个用于变更相关任务的神经模型是有意义的。受此启发，我们提供了一个新的、自然的大型数据集，其中包含从高质量GitHub项目中挖掘的代码和文档的耦合变更，每个样本代表一个单独的提交，其中代码和相关的文档字符串一起被更改。我们介绍了数据集收集方法，并提供了一些具有挑战性（但现实）的任务示例，为学习和评估提供了机会。我们发现当前的模型（特别是Llama-3.1 405B，Mixtral 8×22B）确实发现这些与维护相关的任务具有挑战性。

> One of the central tasks in software maintenance is being able to understand and develop code changes. Thus, given a natural language description of the desired new operation of a function, an agent (human or AI) might be asked to generate the set of edits to that function to implement the desired new operation; likewise, given a set of edits to a function, an agent might be asked to generate a changed description, of that function's new workings. Thus, there is an incentive to train a neural model for change-related tasks. Motivated by this, we offer a new, "natural", large dataset of coupled changes to code and documentation mined from actual high-quality GitHub projects, where each sample represents a single commit where the code and the associated docstring were changed together. We present the methodology for gathering the dataset, and some sample, challenging (but realistic) tasks where our dataset provides opportunities for both learning and evaluation. We find that current models (specifically Llama-3.1 405B, Mixtral 8$\times$22B) do find these maintenance-related tasks challenging.

[Arxiv](https://arxiv.org/abs/2502.00519)