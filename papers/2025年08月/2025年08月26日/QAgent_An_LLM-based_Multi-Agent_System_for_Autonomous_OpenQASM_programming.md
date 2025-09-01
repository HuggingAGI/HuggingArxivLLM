# QAgent：基于LLM的多智能体系统，实现自主OpenQASM编程

发布时间：2025年08月26日

`Agent` `基础理论`

> QAgent: An LLM-based Multi-Agent System for Autonomous OpenQASM programming

# 摘要

> 嘈杂中等规模量子（NISQ）设备已在经典计算机难以解决的问题上崭露早期量子优势，其应用范围从物理模拟延伸至高斯玻色采样。然而，非专家要想充分利用这些优势仍面临挑战，主要瓶颈在于Open Quantum Assembly Language（OpenQASM）编程的复杂性。尽管基于大型语言模型（LLM）的智能体已能自动处理经典编程流程，但量子领域的同类智能体大多局限于量子化学、错误校正等特定任务。为此，本文提出QAgent——一个由LLM驱动的多智能体系统，能够实现OpenQASM编程的全自动化。该系统通过整合任务规划、上下文少样本学习、用于长期上下文的检索增强生成（RAG）、预定义生成工具及思维链（CoT）推理，系统性提升了代码的编译准确性与功能正确性。实验结果表明，QAgent的性能提升显著：在不同规模的多个LLM上，其QASM代码生成准确率较以往基于静态LLM的方法提高了71.6%。我们相信，这一多智能体系统将成为推动量子编程民主化、弥合专业鸿沟、加速量子计算落地应用的关键力量。

> Noisy Intermediate-Scale Quantum (NISQ) devices have begun to exhibit early quantum advantages on classically intractable problems, spanning physics simulations to Gaussian boson sampling. Yet, realizing these benefits remains challenging for non-experts, primarily due to the complexities of programming in Open Quantum Assembly Language (OpenQASM). Although Large Language Model (LLM)-based agents have shown promise in automating classical programming workflows, their quantum counterparts have largely been restricted to specialized tasks such as quantum chemistry or error correction. In this paper, we present QAgent, an LLM-powered multi-agent system that fully automates OpenQASM programming. By integrating task planning, in-context few-shot learning, retrieval-augmented generation (RAG) for long-term context, predefined generation tools, and chain-of-thought (CoT) reasoning, the agents systematically improve both compilation and functional correctness. Our evaluations demonstrate substantial improvements: across multiple LLMs of varying sizes, QAgent enhances the accuracy of QASM code generation by 71.6\% compared to previous static LLM-based approaches. We envision this multi-agent system as a key enabler for democratizing quantum programming, bridging expertise gaps, and accelerating the practical adoption of quantum computing.

[Arxiv](https://arxiv.org/abs/2508.20134)