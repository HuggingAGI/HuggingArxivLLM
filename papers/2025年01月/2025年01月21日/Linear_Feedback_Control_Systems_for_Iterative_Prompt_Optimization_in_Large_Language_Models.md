# 大型语言模型中的迭代提示优化：线性反馈控制系统的应用

发布时间：2025年01月21日

`LLM理论

理由：这篇论文主要探讨了如何将反馈控制系统的原理应用于大型语言模型（LLMs）的提示优化过程，并提出了一种新的理论框架。论文的核心在于理论上的创新和方法论的探讨，而不是具体的应用或实现。因此，它更适合归类为“LLM理论”。` `人工智能` `控制系统`

> Linear Feedback Control Systems for Iterative Prompt Optimization in Large Language Models

# 摘要

> 大型语言模型（LLMs）通过生成基于提示的输出，彻底革新了多种应用。然而，要达到理想输出，往往需要反复优化提示。本文提出了一种创新方法，将LLMs中的提示优化过程与反馈控制系统相类比。我们将LLM输出与目标结果之间的偏差视为误差，通过迭代优化提示，直至输出达标。这一过程类似于反馈控制系统，尽管LLM具有非线性和非确定性，但我们运用线性反馈控制原理对其进行管理。我们探讨了在此框架下应用不同类型控制器的可能性，为LLMs与线性反馈控制机制的融合奠定了数学基础。

> Large Language Models (LLMs) have revolutionized various applications by generating outputs based on given prompts. However, achieving the desired output requires iterative prompt refinement. This paper presents a novel approach that draws parallels between the iterative prompt optimization process in LLMs and feedback control systems. We iteratively refine the prompt by treating the deviation between the LLM output and the desired result as an error term until the output criteria are met. This process is akin to a feedback control system, where the LLM, despite being non-linear and non-deterministic, is managed using principles from linear feedback control systems. We explore the application of different types of controllers within this framework, providing a mathematical foundation for integrating linear feedback control mechanisms with LLMs.

[Arxiv](https://arxiv.org/abs/2501.11979)