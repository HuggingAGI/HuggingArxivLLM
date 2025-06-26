# # 基于LLM的多智能体系统实现Haskell代码智能重构

发布时间：2025年06月24日

`LLM应用` `软件开发` `软件维护`

> LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code

# 摘要

> # 代码重构在软件开发中的应用
代码重构是软件开发与维护中的一项持续性活动。软件系统的规模扩展与维护，均依赖于代码重构这一过程。然而，这一过程仍然劳动密集，因为它要求程序员详细分析代码库以避免引入新的缺陷。

在本研究中，我们提出了一种基于大型语言模型（LLM）的多智能体系统，用于自动化Haskell代码的重构过程。本研究的目标是评估基于LLM的智能体在执行结构化且语义准确的Haskell代码重构方面的效果。

我们提出的多智能体系统基于具有不同角色的专用智能体，包括代码分析、重构执行、验证和调试。为了测试多智能体系统的有效性和实际适用性，我们使用不同的开源Haskell代码库进行了评估。

实验结果表明，所提出的基于LLM的多智能体系统平均将代码复杂度降低了11.03%，整体代码质量提高了22.46%，平均性能效率提升了13.27%。此外，内存分配得到了最多14.57%的优化。这些结果凸显了基于LLM的多智能体在管理面向函数式编程范式的重构任务方面的能力。

我们的研究发现表明，将基于LLM的多智能体系统集成到函数式编程语言的重构中，可以提高系统的可维护性，并支持自动化的开发工作流程。

> Refactoring is a constant activity in software development and maintenance. Scale and maintain software systems are based on code refactoring. However, this process is still labor intensive, as it requires programmers to analyze the codebases in detail to avoid introducing new defects. In this research, we put forward a large language model (LLM)-based multi-agent system to automate the refactoring process on Haskell code. The objective of this research is to evaluate the effect of LLM-based agents in performing structured and semantically accurate refactoring on Haskell code. Our proposed multi-agent system based on specialized agents with distinct roles, including code analysis, refactoring execution, verification, and debugging. To test the effectiveness and practical applicability of the multi-agent system, we conducted evaluations using different open-source Haskell codebases. The results of the experiments carried out showed that the proposed LLM-based multi-agent system could average 11.03% decreased complexity in code, an improvement of 22.46% in overall code quality, and increase performance efficiency by an average of 13.27%. Furthermore, memory allocation was optimized by up to 14.57%. These results highlight the ability of LLM-based multi-agent in managing refactoring tasks targeted toward functional programming paradigms. Our findings hint that LLM-based multi-agent systems integration into the refactoring of functional programming languages can enhance maintainability and support automated development workflows.

[Arxiv](https://arxiv.org/abs/2506.19481)