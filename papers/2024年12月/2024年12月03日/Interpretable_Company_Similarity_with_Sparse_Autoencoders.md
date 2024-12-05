# 利用稀疏自编码器实现的可解释的公司相似性

发布时间：2024年12月03日

`LLM应用`

> Interpretable Company Similarity with Sparse Autoencoders

# 摘要

> 确定公司的相似性在金融领域至关重要，它为套期保值、风险管理、投资组合多元化等提供支撑。从业者常依据部门和行业分类来衡量相似性，像 SIC 代码和 GICS 代码，前者由美国证券交易委员会（SEC）使用，后者在投资界广泛应用。将公司描述进行聚类嵌入被提议作为确定公司相似性的潜在技术，然而令牌嵌入缺乏可解释性，给在高风险情境中的应用带来重大阻碍。稀疏自编码器在增强大型语言模型的可解释性方面展现出潜力，它能将模型激活分解为可解释的特征。在本文中，我们探究了 SAE 特征在衡量公司相似性方面的应用，并将其与（1）SIC 代码和（2）主要组代码进行基准对比。我们的结论是：通过月度回报的相关性（作为相似性的指标）和协整的 PnL 评估，SAE 特征在量化公司的基本特征方面能够重现甚至超越部门分类。

> Determining company similarity is a vital task in finance, underpinning hedging, risk management, portfolio diversification, and more. Practitioners often rely on sector and industry classifications to gauge similarity, such as SIC-codes and GICS-codes, the former being used by the U.S. Securities and Exchange Commission (SEC), and the latter widely used by the investment community. Clustering embeddings of company descriptions has been proposed as a potential technique for determining company similarity, but the lack of interpretability in token embeddings poses a significant barrier to adoption in high-stakes contexts. Sparse Autoencoders have shown promise in enhancing the interpretability of Large Language Models by decomposing LLM activations into interpretable features. In this paper, we explore the use of SAE features in measuring company similarity and benchmark them against (1) SIC codes and (2) Major Group codes. We conclude that SAE features can reproduce and even surpass sector classifications in quantifying fundamental characteristics of companies, evaluated by the correlation of monthly returns, a proxy for similarity, and PnL from cointegration.

[Arxiv](https://arxiv.org/abs/2412.02605)