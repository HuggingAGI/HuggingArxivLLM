# # 大型语言模型时代的数据共享：DSIC机制的设计与实现

发布时间：2025年06月01日

`LLM理论

理由：这篇论文讨论了大型语言模型（LLMs）的数据采购机制，提出了一个机制设计框架，确保数据共享的诚实性和激励相容。它涉及数据质量和学习效用的理论分析，属于LLM的理论研究。` `数据市场` `法律科技`

> Designing DSIC Mechanisms for Data Sharing in the Era of Large Language Models

# 摘要

> 大型语言模型（LLMs）的训练需要大量来自面临法律、隐私和战略限制的机构的高质量数据。然而，现有的数据采购方法往往依赖于无法验证的信任，或者忽视了供应商之间异质化的成本。我们提出了一种机制设计框架，用于诚实、低信任的数据共享，确保占优策略激励相容（DSIC）、个人理性和弱预算平衡，同时根据数据质量和学习效用来奖励数据。我们正式化了一个模型，其中供应商私下了解其数据成本和质量，而价值仅来源于数据对模型性能的贡献。基于此，我们提出了质量加权边际激励拍卖（Q-MIA），它使用虚拟成本指标对供应商进行排序，并采用Myerson风格的支付方式，以确保DSIC和预算可行性。为了支持流动性有限或长期激励的环境，我们引入了边际效用代币（MUT），它根据边际贡献分配未来的权利。我们将这些统一到混合MIA中，这是一种平衡前期支付和延期奖励的混合机制。所有机制都支持可验证的、保护隐私的实现。在理论和实证上，它们都优于基于体积和信任的基准方法，在预算约束下吸引更多高质量数据，同时对误报和串通具有鲁棒性。这为未来LLMs的可持续和公平数据市场奠定了原则性基础。

> Training large language models (LLMs) requires vast amounts of high-quality data from institutions that face legal, privacy, and strategic constraints. Existing data procurement methods often rely on unverifiable trust or ignore heterogeneous provider costs. We introduce a mechanism-design framework for truthful, trust-minimized data sharing that ensures dominant-strategy incentive compatibility (DSIC), individual rationality, and weak budget balance, while rewarding data based on both quality and learning utility. We formalize a model where providers privately know their data cost and quality, and value arises solely from the data's contribution to model performance. Based on this, we propose the Quality-Weighted Marginal-Incentive Auction (Q-MIA), which ranks providers using a virtual cost metric and uses Myerson-style payments to ensure DSIC and budget feasibility. To support settings with limited liquidity or long-term incentives, we introduce the Marginal Utility Token (MUT), which allocates future rights based on marginal contributions. We unify these in Mixed-MIA, a hybrid mechanism balancing upfront payments and deferred rewards. All mechanisms support verifiable, privacy-preserving implementation. Theoretically and empirically, they outperform volume-based and trust-based baselines, eliciting higher-quality data under budget constraints while remaining robust to misreporting and collusion. This establishes a principled foundation for sustainable and fair data markets for future LLMs.

[Arxiv](https://arxiv.org/abs/2506.05379)