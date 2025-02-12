# SymGPT：结合符号执行与大型语言模型的智能合约审计方法

发布时间：2025年02月11日

`LLM应用` `区块链` `智能合约`

> SymGPT: Auditing Smart Contracts via Combining Symbolic Execution with Large Language Models

# 摘要

> 为了有效治理以太坊上的智能合约，人们开发了多个以太坊改进提案（ERC）标准，每个标准都有一套规则来规范智能合约的行为。违反这些规则可能导致严重的安全漏洞和经济损失，因此验证智能合约是否符合ERC标准至关重要。然而，当前的验证方法——包括手动审核、专家开发的程序分析工具或大型语言模型（LLMs）——在识别ERC规则违规方面都存在明显不足。本文介绍了一款名为SymGPT的创新工具，它巧妙地结合了大型语言模型的自然语言理解能力和符号执行的形式化保证，能够自动验证智能合约是否符合ERC规则。为了开发SymGPT，我们对三个广泛使用的ERC标准中的132条规则进行了深入研究，分析了它们的内容、安全影响及自然语言描述。基于此，我们设计了SymGPT的工作流程：首先，指示大型语言模型将ERC规则转化为定义好的EBNF语法；然后，从形式化的规则中提取约束条件，以识别可能的违规场景；最后，利用符号执行技术进行检测。实验结果显示，SymGPT在4,000份真实合约中发现了5,783条ERC规则违规，其中包括1,375条具有明确攻击路径的金融资产盗窃风险，充分证明了其有效性。此外，SymGPT在性能上超越了六种自动化技术及一项专业的安全审核服务，凸显了其在智能合约分析领域的领先地位。

> To govern smart contracts running on Ethereum, multiple Ethereum Request for Comment (ERC) standards have been developed, each having a set of rules to guide the behaviors of smart contracts. Violating the ERC rules could cause serious security issues and financial loss, signifying the importance of verifying smart contracts follow ERCs. Today's practices of such verification are to manually audit each single contract, use expert-developed program-analysis tools, or use large language models (LLMs), all of which are far from effective in identifying ERC rule violations. This paper introduces SymGPT, a tool that combines the natural language understanding of large language models (LLMs) with the formal guarantees of symbolic execution to automatically verify smart contracts' compliance with ERC rules. To develop SymGPT, we conduct an empirical study of 132 ERC rules from three widely used ERC standards, examining their content, security implications, and natural language descriptions. Based on this study, we design SymGPT by first instructing an LLM to translate ERC rules into a defined EBNF grammar. We then synthesize constraints from the formalized rules to represent scenarios where violations may occur and use symbolic execution to detect them. Our evaluation shows that SymGPT identifies 5,783 ERC rule violations in 4,000 real-world contracts, including 1,375 violations with clear attack paths for stealing financial assets, demonstrating its effectiveness. Furthermore, SymGPT outperforms six automated techniques and a security-expert auditing service, underscoring its superiority over current smart contract analysis methods.

[Arxiv](https://arxiv.org/abs/2502.07644)