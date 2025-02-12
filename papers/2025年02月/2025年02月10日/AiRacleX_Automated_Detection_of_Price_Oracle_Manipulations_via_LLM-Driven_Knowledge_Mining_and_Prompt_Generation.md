# AiRacleX：通过基于LLM的知识挖掘和提示生成实现价格预言机操纵的自动化检测

发布时间：2025年02月10日

`LLM应用` `去中心化金融` `区块链`

> AiRacleX: Automated Detection of Price Oracle Manipulations via LLM-Driven Knowledge Mining and Prompt Generation

# 摘要

> 去中心化金融应用依赖准确的价格预言机来保障交易安全，然而这些预言机极易受到操控，使攻击者能够利用智能合约漏洞进行不公平的资产评估并谋取私利。传统上，检测此类操控依赖于经验丰富的专家手动分析，这带来了巨大的挑战。本文中，我们提出了一种全新的LLM驱动框架，通过整合不同LLM模型的互补优势，实现对价格预言机操控的自动化检测。我们的方法始于领域知识提取，其中一种LLM模型从顶级学术论文中提炼出关于价格预言机漏洞的精准见解，从而无需开发者或审计人员具备深厚的专业知识。这些知识构成了第二个LLM模型生成结构化、上下文感知的链式思考提示的基础，这些提示引导第三个LLM模型准确识别智能合约中的操控模式。我们通过实验验证了该框架的有效性，实验基于2021年至2023年间46个真实世界DeFi攻击或项目中已知的60个漏洞。由AiRacleX识别出的最佳LLM组合（Haiku-Haiku-4o-mini）在召回率上较最先进的工具GPTScan提升了2.58倍（0.667 vs 0.259），同时保持了相当的精准度。此外，我们的框架展示了用开源模型替代商业模型的可行性，从而为开发者提升了隐私与安全性。


> Decentralized finance (DeFi) applications depend on accurate price oracles to ensure secure transactions, yet these oracles are highly vulnerable to manipulation, enabling attackers to exploit smart contract vulnerabilities for unfair asset valuation and financial gain. Detecting such manipulations traditionally relies on the manual effort of experienced experts, presenting significant challenges. In this paper, we propose a novel LLM-driven framework that automates the detection of price oracle manipulations by leveraging the complementary strengths of different LLM models (LLMs). Our approach begins with domain-specific knowledge extraction, where an LLM model synthesizes precise insights about price oracle vulnerabilities from top-tier academic papers, eliminating the need for profound expertise from developers or auditors. This knowledge forms the foundation for a second LLM model to generate structured, context-aware chain of thought prompts, which guide a third LLM model in accurately identifying manipulation patterns in smart contracts. We validate the effectiveness of framework through experiments on 60 known vulnerabilities from 46 real-world DeFi attacks or projects spanning 2021 to 2023. The best performing combination of LLMs (Haiku-Haiku-4o-mini) identified by AiRacleX demonstrate a 2.58-times improvement in recall (0.667 vs 0.259) compared to the state-of-the-art tool GPTScan, while maintaining comparable precision. Furthermore, our framework demonstrates the feasibility of replacing commercial models with open-source alternatives, enhancing privacy and security for developers.

[Arxiv](https://arxiv.org/abs/2502.06348)