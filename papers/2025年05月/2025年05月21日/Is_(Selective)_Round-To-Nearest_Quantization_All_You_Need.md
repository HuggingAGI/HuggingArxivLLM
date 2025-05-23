# 仅靠（选择性）最近邻量化就够了吗？

发布时间：2025年05月21日

`LLM应用

理由：这篇论文主要讨论了量化技术，特别是四舍五入（Round-to-Nearest，RTN）在大型语言模型（LLMs）中的应用和优化。它探讨了如何通过选择性地提升特定模型层和模块的数据精度格式来提高RTN的准确度，并展示了其在生成吞吐量和准确度上的优势。因此，这篇论文属于LLM应用类别，因为它专注于将量化技术应用于优化LLMs的性能。` `人工智能`

> Is (Selective) Round-To-Nearest Quantization All You Need?

# 摘要

> 量化已成为应对日益增长的大型语言模型（LLMs）不可或缺的工具。四舍五入（Round-to-Nearest，RTN）或许是最早出现的量化技术之一，在大型语言模型（LLMs）尚未成为机器学习（ML）研究焦点之前就已存在。然而，近年来更先进的量化方法相继涌现，声称在几乎所有性能指标上都优于RTN。本研究旨在打破这一固有观念，证明RTN不仅应用成本低廉，而且其生成吞吐量可能更优，准确度也可与更先进的替代方案相媲美。特别地，我们基于近期的Marlin内核实现了RTN，并展示了如何通过选择性地提升特定模型层和模块的数据精度格式，逐步提高RTN的准确度。根据我们的研究结果，我们认为RTN为量化大型语言模型（LLMs）提供了一个可行且实用的选择。

> Quantization became a necessary tool for serving ever-increasing Large Language Models (LLMs). RTN (Round-to-Nearest) is perhaps the simplest quantization technique that has been around well before LLMs surged to the forefront of machine learning (ML) research. Yet, it has been largely dismissed by recent and more advanced quantization methods that claim superiority over RTN in nearly every aspect of performance. This work aims to dispel this established point of view, showing that RTN is not only much cheaper to apply, but also its token generation throughput can be better than and accuracy can be similar to more advanced alternatives. In particular, we discuss our implementation of RTN based on the recent Marlin kernels and demonstrate how the accuracy of RTN can be gradually improved by selectively increasing the data precision format of certain model layers and modules. Based on our results, we argue that RTN presents a viable and practical choice for quantizing LLMs.

[Arxiv](https://arxiv.org/abs/2505.15909)