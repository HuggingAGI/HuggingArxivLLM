# 结合知识图谱的可执行CoT方法，助力数学编码

发布时间：2025年08月06日

`LLM应用

摘要分析：论文探讨了大型语言模型在数学推理和代码生成中的应用，提出了一种结合知识图谱和RAG技术的框架，属于将LLMs应用于特定任务的范畴。` `数学推理` `代码生成`

> KG-Augmented Executable CoT for Mathematical Coding

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域表现优异，但在数学推理和代码生成等复杂任务中仍存在明显短板。针对这些局限性，我们提出了一种创新性框架——知识图谱增强的可执行链式思维（KGA-ECoT）。该框架通过知识图谱优化代码生成，并利用可执行代码提升数学推理能力。KGA-ECoT将问题拆解为结构化任务图，借助高效的GraphRAG从数学知识库中精准检索相关信息，并生成可验证的代码以确保计算结果的准确性。实验结果表明，在多个数学推理基准测试中，KGA-ECoT的绝对准确率较现有方法提升了几个到十几个百分点。深入分析表明，GraphRAG在提升代码质量方面发挥了重要作用，而外部代码的可执行性则为推理结果的精确性提供了有力保障。这些研究发现充分证明了KGA-ECoT在复杂数学推理任务中具有强大的适用性和广泛的推广价值。

> In recent years, large language models (LLMs) have excelled in natural language processing tasks but face significant challenges in complex reasoning tasks such as mathematical reasoning and code generation. To address these limitations, we propose KG-Augmented Executable Chain-of-Thought (KGA-ECoT), a novel framework that enhances code generation through knowledge graphs and improves mathematical reasoning via executable code. KGA-ECoT decomposes problems into a Structured Task Graph, leverages efficient GraphRAG for precise knowledge retrieval from mathematical libraries, and generates verifiable code to ensure computational accuracy. Evaluations on multiple mathematical reasoning benchmarks demonstrate that KGA-ECoT significantly outperforms existing prompting methods, achieving absolute accuracy improvements ranging from several to over ten percentage points. Further analysis confirms the critical roles of GraphRAG in enhancing code quality and external code execution in ensuring precision. These findings collectively establish KGA-ECoT as a robust and highly generalizable framework for complex mathematical reasoning tasks.

[Arxiv](https://arxiv.org/abs/2508.04072)