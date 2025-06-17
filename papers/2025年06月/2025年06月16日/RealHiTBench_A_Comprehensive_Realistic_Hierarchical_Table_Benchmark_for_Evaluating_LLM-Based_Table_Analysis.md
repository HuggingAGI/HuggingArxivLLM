# RealHiTBench: 全面评估基于LLM的表格分析能力的现实层次化表格基准测试工具

发布时间：2025年06月16日

`LLM应用` `表格数据` `基准测试`

> RealHiTBench: A Comprehensive Realistic Hierarchical Table Benchmark for Evaluating LLM-Based Table Analysis

# 摘要

> 大型语言模型（LLMs）的快速发展使得评估其处理复杂表格数据的能力变得日益重要。然而，现有的基准测试要么基于过时的数据设置，要么仅关注简单的扁平表格结构。为了解决这一问题，我们推出了RealHiTBench——一个全面的基准测试，旨在评估LLMs和多模态大型语言模型（MLLMs）在处理复杂表格数据时的性能。RealHiTBench支持包括LaTeX、HTML和PNG在内的多种输入格式，并包含了一系列结构复杂、类型多样的表格。通过使用25个最先进的LLMs进行的实验，我们证明了RealHiTBench确实是一个具有挑战性的基准测试。此外，我们还开发了TreeThinker——一个基于树的管道，能够将层次化标题组织成树结构，从而增强表格推理能力。这验证了提升LLMs对表格层次结构感知能力的重要性。我们希望这项研究能够激发更多关于表格数据推理的研究，并推动更 robust 模型的发展。更多代码和数据请访问https://github.com/cspzyy/RealHiTBench。

> With the rapid advancement of Large Language Models (LLMs), there is an increasing need for challenging benchmarks to evaluate their capabilities in handling complex tabular data. However, existing benchmarks are either based on outdated data setups or focus solely on simple, flat table structures. In this paper, we introduce RealHiTBench, a comprehensive benchmark designed to evaluate the performance of both LLMs and Multimodal LLMs (MLLMs) across a variety of input formats for complex tabular data, including LaTeX, HTML, and PNG. RealHiTBench also includes a diverse collection of tables with intricate structures, spanning a wide range of task types. Our experimental results, using 25 state-of-the-art LLMs, demonstrate that RealHiTBench is indeed a challenging benchmark. Moreover, we also develop TreeThinker, a tree-based pipeline that organizes hierarchical headers into a tree structure for enhanced tabular reasoning, validating the importance of improving LLMs' perception of table hierarchies. We hope that our work will inspire further research on tabular data reasoning and the development of more robust models. The code and data are available at https://github.com/cspzyy/RealHiTBench.

[Arxiv](https://arxiv.org/abs/2506.13405)