# DeFiScope：利用LLM推理，检测多种DeFi价格操纵行为

发布时间：2025年02月17日

`LLM应用` `加密货币` `去中心化金融`

> DeFiScope: Detecting Various DeFi Price Manipulations with LLM Reasoning

# 摘要

> # 摘要
去中心化金融（DeFi）是当前加密货币和智能合约领域最重要的应用之一，链上管理着数千亿美元的总锁仓价值（TVL）。然而，它仍然容易受到常见的DeFi价格操控攻击。尽管有DeFiRanger和DeFort等先进系统，但它们在处理定制DeFi协议中的非标准价格模型时效果有限。过去三年报告的95起DeFi价格操控攻击中，有44.2%涉及此类模型。

在本文中，我们提出了DeFiScope——首个基于大型语言模型（LLM）的方案，用于检测标准和定制价格模型中的DeFi价格操控攻击。我们的核心观点是，大型语言模型能够从代码中提取价格计算逻辑，并基于此推断代币价格的变化趋势。为了进一步提升LLM的能力，我们利用Foundry合成链上数据，并用于微调专门针对DeFi价格的LLM。结合从低级交易数据中恢复的高级DeFi操作，DeFiScope通过系统挖掘的模式检测各种DeFi价格操控行为。实验结果表明，DeFiScope实现了96%的高精度和80%的召回率，显著优于现有最优方案。此外，我们通过帮助行业合作伙伴确认147起真实世界的价格操控攻击（包括发现81起此前未知的历史事件）证明了DeFiScope的成本效益和实际应用价值。


> DeFi (Decentralized Finance) is one of the most important applications of today's cryptocurrencies and smart contracts. It manages hundreds of billions in Total Value Locked (TVL) on-chain, yet it remains susceptible to common DeFi price manipulation attacks. Despite state-of-the-art (SOTA) systems like DeFiRanger and DeFort, we found that they are less effective to non-standard price models in custom DeFi protocols, which account for 44.2% of the 95 DeFi price manipulation attacks reported over the past three years.
  In this paper, we introduce the first LLM-based approach, DeFiScope, for detecting DeFi price manipulation attacks in both standard and custom price models. Our insight is that large language models (LLMs) have certain intelligence to abstract price calculation from code and infer the trend of token price changes based on the extracted price models. To further strengthen LLMs in this aspect, we leverage Foundry to synthesize on-chain data and use it to fine-tune a DeFi price-specific LLM. Together with the high-level DeFi operations recovered from low-level transaction data, DeFiScope detects various DeFi price manipulations according to systematically mined patterns. Experimental results show that DeFiScope achieves a high precision of 96% and a recall rate of 80%, significantly outperforming SOTA approaches. Moreover, we evaluate DeFiScope's cost-effectiveness and demonstrate its practicality by helping our industry partner confirm 147 real-world price manipulation attacks, including discovering 81 previously unknown historical incidents.

[Arxiv](https://arxiv.org/abs/2502.11521)