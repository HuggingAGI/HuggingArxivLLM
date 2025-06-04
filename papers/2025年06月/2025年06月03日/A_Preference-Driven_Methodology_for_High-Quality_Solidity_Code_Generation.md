# 一种基于偏好驱动的高质量Solidity代码生成方法论

发布时间：2025年06月03日

`LLM应用` `区块链` `智能合约`

> A Preference-Driven Methodology for High-Quality Solidity Code Generation

# 摘要

> 尽管大型语言模型（LLMs）在生成Solidity代码方面取得了显著进展，但在生成gas效率高且安全的代码方面仍面临重大挑战，这些是实际部署智能合约的关键要求。现有方法将功能正确性、gas优化和安全性视为独立目标，导致生成的合约可能在操作上是健全的，但执行成本高昂或存在严重漏洞。我们提出了PrefGen，一个新型框架，它将标准DPO扩展到人类偏好之外，整合了可量化的区块链特定指标，从而实现专门针对智能合约生成的全面多目标优化。我们的框架引入了一种全面的评估方法，包含四个互补指标：Pass@k（功能正确性）、Compile@k（语法正确性）、Gas@k（gas效率）和Secure@k（安全性评估），提供了严格多维度的合约评估。通过广泛的实验，我们证明PrefGen在所有关键维度上显著优于现有方法，实现了66.7%的Pass@5、58.9%的Gas@5和62.5%的Secure@5，同时生成了功能正确、成本高效且安全的生产级智能合约。

> While Large Language Models (LLMs) have demonstrated remarkable progress in generating functionally correct Solidity code, they continue to face critical challenges in producing gas-efficient and secure code, which are critical requirements for real-world smart contract deployment. Although recent advances leverage Supervised Fine-Tuning (SFT) and Direct Preference Optimization (DPO) for code preference alignment, existing approaches treat functional correctness, gas optimization, and security as independent objectives, resulting in contracts that may achieve operational soundness but suffer from prohibitive execution costs or dangerous vulnerabilities. To address these limitations, we propose PrefGen, a novel framework that extends standard DPO beyond human preferences to incorporate quantifiable blockchain-specific metrics, enabling holistic multi-objective optimization specifically tailored for smart contract generation. Our framework introduces a comprehensive evaluation methodology with four complementary metrics: Pass@k (functional correctness), Compile@k (syntactic correctness), Gas@k (gas efficiency), and Secure@k (security assessment), providing rigorous multi-dimensional contract evaluation. Through extensive experimentation, we demonstrate that PrefGen significantly outperforms existing approaches across all critical dimensions, achieving 66.7% Pass@5, 58.9% Gas@5, and 62.5% Secure@5, while generating production-ready smart contracts that are functionally correct, cost-efficient, and secure.

[Arxiv](https://arxiv.org/abs/2506.03006)