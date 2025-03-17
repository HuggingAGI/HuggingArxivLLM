# LLMPerf：GPU 性能建模邂逅大型语言模型

发布时间：2025年03月14日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在性能建模中的应用，具体是将其用作性能估算器，并通过实验验证了其在OpenCL程序性能建模中的潜力和挑战。因此，它属于LLM应用类别。` `高性能计算` `程序优化`

> LLMPerf: GPU Performance Modeling meets Large Language Models

# 摘要

> 性能建模是程序成本分析中的关键领域，目前依赖于手工构建的模型，这些模型受到程序和硬件限制的约束，尤其是在复杂的GPGPU环境中。与此同时，大型语言模型（LLMs）在解决各种编程挑战中展现出了有效性。我们的工作建立了LLMs与性能建模之间的联系，将LLM用作性能估算器。通过使用精心设计的大型OpenCL数据集进行实验探索，我们突显了LLMs在处理OpenCL设备源程序的性能建模任务中的潜在能力以及主要困难。作为这项工作的首个研究，我们基于LLM的性能模型在大规模生成的验证集上实现了【数学公式】的平均绝对百分比误差。在一组公开的OpenCL程序上，我们的模型达到了【数学公式】的平均绝对百分比误差。

> Performance modeling, a pivotal domain in program cost analysis, currently relies on manually crafted models constrained by various program and hardware limitations, especially in the intricate landscape of GPGPU. Meanwhile, Large Language Models (LLMs) have demonstrated their effectiveness in addressing diverse programming challenges. Our work establishes a connection between LLMs and performance modeling, employing the LLM as a performance estimator. Through experimental exploration with carefully designed large-scale OpenCL datasets, we highlight the potential capability as well as the main difficulties of using LLMs in handling performance modeling tasks for OpenCL device source programs. As the first study for this line of work, our LLM-based performance model achieves a mean absolute percentage error of $24.25\%$ for a large-scale generated validation set. On a set of publicly available OpenCL programs, our model achieves a mean absolute percentage error of $46.1\%$.

[Arxiv](https://arxiv.org/abs/2503.11244)