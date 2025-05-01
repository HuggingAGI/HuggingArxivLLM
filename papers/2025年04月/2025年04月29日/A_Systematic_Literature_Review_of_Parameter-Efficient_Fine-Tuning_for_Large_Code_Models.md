# # 系统综述：大型代码模型的参数高效微调方法研究现状  
本研究系统性地回顾了针对大型代码模型的参数高效微调方法的文献。

发布时间：2025年04月29日

`LLM应用

摘要讨论了大型语言模型在软件工程中的应用，特别是参数高效微调技术如何优化这些模型的使用，属于LLM的应用层面。` `软件工程` `人工智能`

> A Systematic Literature Review of Parameter-Efficient Fine-Tuning for Large Code Models

# 摘要

> 人工智能 (AI)——特别是用于代码的大型语言模型 (LLMs)——的崛起，通过实现代码生成、缺陷检测和修复等任务的自动化，彻底改变了软件工程 (SE)。然而，这些模型在训练和微调过程中需要大量计算资源，这对资源受限环境中的实际应用构成了挑战。为了解决这一问题，研究界逐渐转向参数高效微调 (PEFT)，这是一种通过仅更新模型参数的一小部分（而非整个模型）来实现模型适应的技术。在这项系统性文献综述 (SLR) 中，我们探讨了 PEFT 技术在软件工程各类任务中的广泛应用。我们分析了这些方法如何优化各种深度学习 (DL) 架构，重点关注其对性能和效率的影响。我们的研究综合了 27 篇同行评审论文的发现，识别出配置策略和适应权衡的模式。此次综述的成果是一个全面的分类法，根据任务类型对 PEFT 的使用进行分类，区分生成型（如代码摘要）和非生成型（如代码克隆检测）场景。我们的发现旨在为未来研究提供指导，并推动 PEFT 在可持续、AI 驱动的软件开发中的实际应用。我们的研究资料已公开，欢迎访问 https://github.com/alvi75/SLR-PEFT 查看。

> The rise of Artificial Intelligence (AI)-and particularly Large Language Models (LLMs) for code-has reshaped Software Engineering (SE) by enabling the automation of tasks such as code generation, bug detection, and repair. However, these models require significant computational resources for training and fine-tuning, posing challenges for real-world adoption in resource-constrained environments. To address this, the research community has increasingly turned to Parameter-Efficient Fine-Tuning (PEFT)-a class of techniques that enables the adaptation of large models by updating only a small subset of parameters, rather than the entire model. In this Systematic Literature Review (SLR), we examine the growing application of PEFT techniques-across a wide range of software engineering tasks. We analyze how these methods are used to optimize various deep learning (DL) architectures, focusing on their impact on both performance and efficiency. Our study synthesizes findings from 27 peer-reviewed papers, identifying patterns in configuration strategies and adaptation trade-offs. The outcome of this review is a comprehensive taxonomy that categorizes PEFT usage by task type, distinguishing between generative (e.g., Code Summarization) and non-generative (e.g., Code Clone Detection) scenarios. Our findings aim to inform future research and guide the practical deployment of PEFT in sustainable, AI-powered software development. Our artifacts are publicly available at https://github.com/alvi75/SLR-PEFT

[Arxiv](https://arxiv.org/abs/2504.21569)