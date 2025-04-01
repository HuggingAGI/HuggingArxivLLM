# 基于LLM的漏洞定向复合分析检测智能合约功能性缺陷

发布时间：2025年03月31日

`LLM应用

理由：这篇论文主要探讨了智能合约中的功能性漏洞检测，并提出了一种基于大型语言模型（LLM）的系统PROMFUZZ。虽然论文的重点是智能合约安全，但其中明确提到了使用LLM来驱动分析框架，并且LLM在系统中的应用是其创新点之一。因此，这篇论文可以归类为LLM应用。` `区块链`

> Detecting Functional Bugs in Smart Contracts through LLM-Powered and Bug-Oriented Composite Analysis

# 摘要

> 智能合约作为区块链的重要支柱，对促进商业交易至关重要。然而，这些合约易受可利用漏洞影响，可能造成重大损失。研究发现，超80%的可利用漏洞（主要为功能性漏洞）能规避现有工具检测。核心挑战在于：理解业务模型的高层逻辑与检查智能合约底层实现之间存在巨大鸿沟。同时，识别深层次功能性漏洞需要基于特征自动生成检测预言机。为解决这些问题，我们设计了PROMFUZZ——一个自动化、可扩展的智能合约功能性漏洞检测系统。PROMFUZZ包含三大创新：首先，提出了一种大型语言模型（LLM）驱动的分析框架，采用双代理提示工程策略，精准定位潜在易漏洞函数；其次，实现了两阶段耦合方法，专注于生成基于潜在漏洞函数逻辑信息的不变式检查器；最后，设计了以漏洞为导向的模糊测试引擎，将业务模型的高层逻辑映射到底层实现，并对目标函数执行针对性模糊测试。实验结果表明，PROMFUZZ在功能性漏洞检测中达到了86.96%的召回率和93.02%的F1值，比现有方法提升了至少50%。此外，我们在真实DeFi项目中发现了30个零日漏洞，其中24个已获得CVE编号。

> Smart contracts are fundamental pillars of the blockchain, playing a crucial role in facilitating various business transactions. However, these smart contracts are vulnerable to exploitable bugs that can lead to substantial monetary losses. A recent study reveals that over 80% of these exploitable bugs, which are primarily functional bugs, can evade the detection of current tools. The primary issue is the significant gap between understanding the high-level logic of the business model and checking the low-level implementations in smart contracts. Furthermore, identifying deeply rooted functional bugs in smart contracts requires the automated generation of effective detection oracles based on various bug features. To address these challenges, we design and implement PROMFUZZ, an automated and scalable system to detect functional bugs, in smart contracts. In PROMFUZZ, we first propose a novel Large Language Model (LLM)-driven analysis framework, which leverages a dual-agent prompt engineering strategy to pinpoint potentially vulnerable functions for further scrutiny. We then implement a dual-stage coupling approach, which focuses on generating invariant checkers that leverage logic information extracted from potentially vulnerable functions. Finally, we design a bug-oriented fuzzing engine, which maps the logical information from the high-level business model to the low-level smart contract implementations, and performs the bug-oriented fuzzing on targeted functions. We compare PROMFUZZ with multiple state-of-the-art methods. The results show that PROMFUZZ achieves 86.96% recall and 93.02% F1-score in detecting functional bugs, marking at least a 50% improvement in both metrics over state-of-the-art methods. Moreover, we perform an in-depth analysis on real-world DeFi projects and detect 30 zero-day bugs. Up to now, 24 zero-day bugs have been assigned CVE IDs.

[Arxiv](https://arxiv.org/abs/2503.23718)