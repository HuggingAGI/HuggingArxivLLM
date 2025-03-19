# MANTRA: 利用上下文感知的RAG与多智能体LLM协作增强自动化方法级重构能力

发布时间：2025年03月18日

`LLM应用` `软件工程` `代码重构`

> MANTRA: Enhancing Automated Method-Level Refactoring with Contextual RAG and Multi-Agent LLM Collaboration

# 摘要

> 软件系统的维护与扩展离不开有效的代码重构，但这一过程仍是一项费时费力的工作，需要开发人员细致分析现有代码库，同时避免引入新的缺陷。虽然近期研究利用大型语言模型（LLMs）实现了重构任务的自动化，但现有解决方案的应用范围有限，且缺乏确保代码可编译性和测试通过的机制。为此，我们提出了MANTRA——一个基于LLM代理的综合框架，专注于实现方法级别的重构自动化。MANTRA通过整合感知上下文的检索增强生成、协调的多智能体协作以及语言强化学习，成功模拟了人类在重构过程中的决策模式，同时确保代码的正确性和可读性。我们的实证研究基于从10个具有代表性的Java项目中提取的703个“纯重构”实例（即仅涉及结构改进的代码变更），覆盖了最常见的六种重构操作。实验结果显示，MANTRA相较于基准LLM模型（RawGPT）表现出显著优势：成功生成可编译并通过所有测试的代码实例比例达到82.8%（582/703），而RawGPT仅为8.7%（61/703）。此外，与IntelliJ的LLM驱动重构工具（EM-Assist）相比，MANTRA在生成提取方法变换方面实现了50%的性能提升。一项涉及37名专业开发人员的可用性研究进一步表明，MANTRA生成的重构代码在可读性和可重用性方面与人工编写的代码相当，甚至在某些情况下更为出色。这些结果不仅凸显了MANTRA的实际优势，也充分展现了基于LLM的系统在推动软件重构任务自动化方面的巨大潜力。


> Maintaining and scaling software systems relies heavily on effective code refactoring, yet this process remains labor-intensive, requiring developers to carefully analyze existing codebases and prevent the introduction of new defects. Although recent advancements have leveraged Large Language Models (LLMs) to automate refactoring tasks, current solutions are constrained in scope and lack mechanisms to guarantee code compilability and successful test execution. In this work, we introduce MANTRA, a comprehensive LLM agent-based framework that automates method-level refactoring. MANTRA integrates Context-Aware Retrieval-Augmented Generation, coordinated Multi-Agent Collaboration, and Verbal Reinforcement Learning to emulate human decision-making during refactoring while preserving code correctness and readability. Our empirical study, conducted on 703 instances of "pure refactorings" (i.e., code changes exclusively involving structural improvements), drawn from 10 representative Java projects, covers the six most prevalent refactoring operations. Experimental results demonstrate that MANTRA substantially surpasses a baseline LLM model (RawGPT ), achieving an 82.8% success rate (582/703) in producing code that compiles and passes all tests, compared to just 8.7% (61/703) with RawGPT. Moreover, in comparison to IntelliJ's LLM-powered refactoring tool (EM-Assist), MANTRA exhibits a 50% improvement in generating Extract Method transformations. A usability study involving 37 professional developers further shows that refactorings performed by MANTRA are perceived to be as readable and reusable as human-written code, and in certain cases, even more favorable. These results highlight the practical advantages of MANTRA and emphasize the growing potential of LLM-based systems in advancing the automation of software refactoring tasks.

[Arxiv](https://arxiv.org/abs/2503.14340)