# LLM与HPC：深度探索在高性能计算任务中的评测表现

发布时间：2025年03月15日

`LLM应用

理由：这篇论文探讨了大型语言模型DeepSeek在高性能计算（HPC）领域的应用，特别是其在生成HPC基准代码方面的表现。研究评估了DeepSeek在不同编程语言中的代码生成能力，并将其与GPT-4进行了对比。这些内容属于将LLM应用于特定领域的研究，因此归类为LLM应用。` `软件工程` `高性能计算`

> LLM & HPC:Benchmarking DeepSeek's Performance in High-Performance Computing Tasks

# 摘要

> 大型语言模型（LLMs），如GPT-4和DeepSeek，在软件工程领域已有广泛应用。但它们在高性能计算（HPC）领域的潜力仍有待进一步挖掘。本文研究了近期大型语言模型DeepSeek在生成HPC基准代码方面的表现，包括共轭梯度求解器、并行热方程、并行矩阵乘法、DGEMM和STREAM三元组操作。我们评估了DeepSeek在Cpp、Fortran、Julia和Python等传统HPC语言中的代码生成能力，测试了代码在不同配置和矩阵规模下的正确性、性能和扩展性。此外，我们还对DeepSeek与GPT-4进行了详细对比。结果显示，尽管DeepSeek能够生成可用于HPC任务的功能性代码，但在代码的可扩展性和执行效率方面，它仍落后于GPT-4。

> Large Language Models (LLMs), such as GPT-4 and DeepSeek, have been applied to a wide range of domains in software engineering. However, their potential in the context of High-Performance Computing (HPC) much remains to be explored. This paper evaluates how well DeepSeek, a recent LLM, performs in generating a set of HPC benchmark codes: a conjugate gradient solver, the parallel heat equation, parallel matrix multiplication, DGEMM, and the STREAM triad operation. We analyze DeepSeek's code generation capabilities for traditional HPC languages like Cpp, Fortran, Julia and Python. The evaluation includes testing for code correctness, performance, and scaling across different configurations and matrix sizes. We also provide a detailed comparison between DeepSeek and another widely used tool: GPT-4. Our results demonstrate that while DeepSeek generates functional code for HPC tasks, it lags behind GPT-4, in terms of scalability and execution efficiency of the generated code.

[Arxiv](https://arxiv.org/abs/2504.03665)