# 大型语言模型真的理解性能优化吗？

发布时间：2025年03月17日

`LLM应用` `HPC` `软件开发`

> Do Large Language Models Understand Performance Optimization?

# 摘要

> 大型语言模型（LLMs）在代码补全、翻译和优化等软件开发任务中已展现出强大能力，但其在复杂高性能计算（HPC）环境中的表现仍有待深入探索。本文提出了一套全面的基准测试套件，涵盖多个关键HPC计算模式，用于评估由当前最先进的LLMs（如OpenAI o1、Claude-3.5和Llama-3.2）优化的代码性能。我们不仅分析了基本计算内核，还开发了一个集成LLMs的代理系统，以评估它们在真实HPC应用中的有效性。评估重点包括执行时间、正确性和对HPC特定概念的理解。我们还将结果与传统HPC优化工具的性能进行了对比。研究发现，LLMs在理解人类指令和执行自动化代码转换方面具有显著优势，但同时也存在生成错误代码以及难以理解复杂HPC代码控制流和数据流的局限性。

> Large Language Models (LLMs) have emerged as powerful tools for software development tasks such as code completion, translation, and optimization. However, their ability to generate efficient and correct code, particularly in complex High-Performance Computing (HPC) contexts, has remained underexplored. To address this gap, this paper presents a comprehensive benchmark suite encompassing multiple critical HPC computational motifs to evaluate the performance of code optimized by state-of-the-art LLMs, including OpenAI o1, Claude-3.5, and Llama-3.2. In addition to analyzing basic computational kernels, we developed an agent system that integrates LLMs to assess their effectiveness in real HPC applications. Our evaluation focused on key criteria such as execution time, correctness, and understanding of HPC-specific concepts. We also compared the results with those achieved using traditional HPC optimization tools. Based on the findings, we recognized the strengths of LLMs in understanding human instructions and performing automated code transformations. However, we also identified significant limitations, including their tendency to generate incorrect code and their challenges in comprehending complex control and data flows in sophisticated HPC code.

[Arxiv](https://arxiv.org/abs/2503.13772)