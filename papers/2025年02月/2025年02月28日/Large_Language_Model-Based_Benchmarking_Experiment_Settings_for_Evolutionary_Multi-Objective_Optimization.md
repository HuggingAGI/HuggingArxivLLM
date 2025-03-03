# # 基于大型语言模型的进化多目标优化基准测试实验设置

发布时间：2025年02月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在设计进化多目标优化（EMO）算法中的应用，具体分析了LLMs在比较EMO算法性能时的隐式假设，并通过实验验证了LLMs在设计基准测试实验中的表现。这属于LLM的应用领域，因此归类为LLM应用。` `优化算法` `人工智能`

> Large Language Model-Based Benchmarking Experiment Settings for Evolutionary Multi-Objective Optimization

# 摘要

> 手动设计进化优化算法时，我们会隐式或显式地针对特定优化问题进行假设。在自动化算法设计中，目标优化问题通常是显式给定的。近期研究探讨了利用大型语言模型（LLMs）设计进化多目标优化（EMO）算法的可能性，但目标多目标问题并不总被显式指定。众所周知，在进化多目标优化领域，算法性能不仅受测试问题影响，还与性能指标、参考点、终止条件和种群规模等因素密切相关。因此，LLMs设计的EMO算法可能也会受到这些因素的影响。本文旨在探讨LLMs在比较EMO算法性能时的隐式假设。为此，我们要求LLMs设计一个EMO算法的基准测试实验。实验结果表明，LLMs通常建议采用经典的基准设置：在标准参数规格下，通过HV和IGD指标，评估NSGA-II、MOEA/D和NSGA-III在ZDT、DTLZ和WFG问题上的性能表现。

> When we manually design an evolutionary optimization algorithm, we implicitly or explicitly assume a set of target optimization problems. In the case of automated algorithm design, target optimization problems are usually explicitly shown. Recently, the use of large language models (LLMs) for the design of evolutionary multi-objective optimization (EMO) algorithms have been examined in some studies. In those studies, target multi-objective problems are not always explicitly shown. It is well known in the EMO community that the performance evaluation results of EMO algorithms depend on not only test problems but also many other factors such as performance indicators, reference point, termination condition, and population size. Thus, it is likely that the designed EMO algorithms by LLMs depends on those factors. In this paper, we try to examine the implicit assumption about the performance comparison of EMO algorithms in LLMs. For this purpose, we ask LLMs to design a benchmarking experiment of EMO algorithms. Our experiments show that LLMs often suggest classical benchmark settings: Performance examination of NSGA-II, MOEA/D and NSGA-III on ZDT, DTLZ and WFG by HV and IGD under the standard parameter specifications.

[Arxiv](https://arxiv.org/abs/2502.21108)