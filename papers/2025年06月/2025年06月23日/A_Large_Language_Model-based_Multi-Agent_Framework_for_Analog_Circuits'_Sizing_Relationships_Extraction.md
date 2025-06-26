# 提出了一种基于大型语言模型的多智能体框架，专注于提取模拟电路中的尺寸关系

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了大语言模型在模拟电路尺寸设计中的应用，具体是通过LLM提取尺寸关系来优化设计过程。这属于LLM的应用层面，而非理论或架构的研究，因此归类为LLM应用。` `电子设计自动化` `模拟电路设计`

> A Large Language Model-based Multi-Agent Framework for Analog Circuits' Sizing Relationships Extraction

# 摘要

> 在模拟电路预布局设计中，器件尺寸设计是决定电路性能的关键环节。现有的方法多将尺寸设计转化为数学优化问题，从数学角度提升优化效率，但忽视了先验知识的自动引入，导致搜索空间剪枝效果不佳，仍存在较大压缩空间。为解决此问题，我们提出了一种基于大语言模型（LLM）的多智能体框架，用于从学术论文中提取模拟电路的尺寸关系。通过该框架提取的尺寸关系，可有效剪枝设计过程中的搜索空间。实验结果表明，在3种电路测试中，优化效率提升了$2.32 \sim 26.6 	imes$。这表明LLM在模拟电路尺寸设计的搜索空间剪枝中表现出色，为LLMs与传统模拟电路设计自动化方法的结合提供了新思路。

> In the design process of the analog circuit pre-layout phase, device sizing is an important step in determining whether an analog circuit can meet the required performance metrics. Many existing techniques extract the circuit sizing task as a mathematical optimization problem to solve and continuously improve the optimization efficiency from a mathematical perspective. But they ignore the automatic introduction of prior knowledge, fail to achieve effective pruning of the search space, which thereby leads to a considerable compression margin remaining in the search space. To alleviate this problem, we propose a large language model (LLM)-based multi-agent framework for analog circuits' sizing relationships extraction from academic papers. The search space in the sizing process can be effectively pruned based on the sizing relationship extracted by this framework. Eventually, we conducted tests on 3 types of circuits, and the optimization efficiency was improved by $2.32 \sim 26.6 \times$. This work demonstrates that the LLM can effectively prune the search space for analog circuit sizing, providing a new solution for the combination of LLMs and conventional analog circuit design automation methods.

[Arxiv](https://arxiv.org/abs/2506.18424)