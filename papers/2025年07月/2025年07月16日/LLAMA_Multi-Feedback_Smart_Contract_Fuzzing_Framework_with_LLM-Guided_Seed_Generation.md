# LLAMA：基于多反馈与LLM引导的智能合约模糊测试框架

发布时间：2025年07月16日

`LLM应用` `区块链` `智能合约`

> LLAMA: Multi-Feedback Smart Contract Fuzzing Framework with LLM-Guided Seed Generation

# 摘要

> 智能合约在区块链生态系统中至关重要，而模糊测试仍是保障其安全的关键手段。尽管变异调度对模糊测试效果影响深远，但现有模糊器主要聚焦于种子调度与生成，而变异调度这一关键因素却鲜少被深入研究。本研究提出了一种基于大型语言模型（LLMs）的多反馈智能合约模糊测试框架（LLAMA），该框架巧妙融合了 LLMs、进化变异策略和混合测试技术。LLAMA 的三大核心组件分别为：(i) 一种分层提示策略，引导 LLMs 生成语义有效的初始种子，并结合轻量级预模糊阶段以筛选出高潜力输入；(ii) 一种多反馈优化机制，通过运行时覆盖和依赖反馈的双重驱动，同步提升种子生成、选择及变异调度的效率；(iii) 一种进化模糊引擎，动态调整变异算子概率以优化测试效果，同时引入符号执行技术以突破测试瓶颈，挖掘更深层次的安全漏洞。实验数据显示，LLAMA 在覆盖范围和漏洞检测方面均超越现有顶尖模糊器。具体而言，LLAMA 达到了 91% 的指令覆盖率和 90% 的分支覆盖率，并在不同类别中成功识别出 148 个已知漏洞中的 132 个。这些成果充分展现了 LLAMA 在现实世界智能合约安全测试中的卓越效能、广泛应用性和实际操作性。

> Smart contracts play a pivotal role in blockchain ecosystems, and fuzzing remains an important approach to securing smart contracts. Even though mutation scheduling is a key factor influencing fuzzing effectiveness, existing fuzzers have primarily explored seed scheduling and generation, while mutation scheduling has been rarely addressed by prior work. In this work, we propose a Large Language Models (LLMs)-based Multi-feedback Smart Contract Fuzzing framework (LLAMA) that integrates LLMs, evolutionary mutation strategies, and hybrid testing techniques. Key components of the proposed LLAMA include: (i) a hierarchical prompting strategy that guides LLMs to generate semantically valid initial seeds, coupled with a lightweight pre-fuzzing phase to select high-potential inputs; (ii) a multi-feedback optimization mechanism that simultaneously improves seed generation, seed selection, and mutation scheduling by leveraging runtime coverage and dependency feedback; and (iii) an evolutionary fuzzing engine that dynamically adjusts mutation operator probabilities based on effectiveness, while incorporating symbolic execution to escape stagnation and uncover deeper vulnerabilities. Our experiments demonstrate that LLAMA outperforms state-of-the-art fuzzers in both coverage and vulnerability detection. Specifically, it achieves 91% instruction coverage and 90% branch coverage, while detecting 132 out of 148 known vulnerabilities across diverse categories. These results highlight LLAMA's effectiveness, adaptability, and practicality in real-world smart contract security testing scenarios.

[Arxiv](https://arxiv.org/abs/2507.12084)