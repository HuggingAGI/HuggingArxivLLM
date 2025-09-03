# # 价格已包含全部信息？LLM嵌入与有效市场假说（EMH）的股票聚类对决

发布时间：2025年09月01日

`LLM应用` `金融科技`

> Is All the Information in the Price? LLM Embeddings versus the EMH in Stock Clustering

# 摘要

> 本文探讨人工智能能否比传统方法更有效地增强股票聚类。结合半强有效市场假说（EMH），我们展开研究——该假说认为，价格已充分反映所有公开信息，因此基于价格信息的聚类难以被进一步优化。我们比较了三种聚类方法：（i）基于历史回报相关性的价格聚类，（ii）由全球行业分类标准（GICS）定义的人工聚类，以及（iii）基于股票相关新闻标题的大型语言模型（LLM）嵌入构建的AI驱动聚类。在每个时间点，每种方法都会对股票进行分类，将每只股票归入一个聚类。为评估聚类效果，我们基于套利定价理论（APT）框架将其转化为合成因子模型，从而在滚动的样本外测试中一致地评估预测性能。通过分析2022年至2024年的标普500成分股，我们发现基于价格的聚类表现始终优于规则驱动和AI驱动的方法：与GICS相比，均方根误差（RMSE）降低15.9%；与LLM嵌入相比，降低14.7%。本文的贡献主要有三点：（i）提出一种可推广的方法，能将任何股票分组（无论是手动、机器还是市场驱动）转化为实时因子模型以进行评估；（ii）首次在相同条件下直接比较了基于价格、人工规则和AI的聚类；（iii）实证证据进一步证实，短期回报信息在很大程度上已包含在价格中。这些结果不仅支持了EMH，还为从业者提供了监测行业结构演变的实用工具，同时为学者测试市场吸收信息速度的相关假说提供了框架。

> This paper investigates whether artificial intelligence can enhance stock clustering compared to traditional methods. We consider this in the context of the semi-strong Efficient Markets Hypothesis (EMH), which posits that prices fully reflect all public information and, accordingly, that clusters based on price information cannot be improved upon. We benchmark three clustering approaches: (i) price-based clusters derived from historical return correlations, (ii) human-informed clusters defined by the Global Industry Classification Standard (GICS), and (iii) AI-driven clusters constructed from large language model (LLM) embeddings of stock-related news headlines. At each date, each method provides a classification in which each stock is assigned to a cluster. To evaluate a clustering, we transform it into a synthetic factor model following the Arbitrage Pricing Theory (APT) framework. This enables consistent evaluation of predictive performance in a roll forward, out-of-sample test. Using S&P 500 constituents from from 2022 through 2024, we find that price-based clustering consistently outperforms both rule-based and AI-based methods, reducing root mean squared error (RMSE) by 15.9% relative to GICS and 14.7% relative to LLM embeddings. Our contributions are threefold: (i) a generalizable methodology that converts any equity grouping: manual, machine, or market-driven, into a real-time factor model for evaluation; (ii) the first direct comparison of price-based, human rule-based, and AI-based clustering under identical conditions; and (iii) empirical evidence reinforcing that short-horizon return information is largely contained in prices. These results support the EMH while offering practitioners a practical diagnostic for monitoring evolving sector structures and provide academics a framework for testing alternative hypotheses about how quickly markets absorb information.

[Arxiv](https://arxiv.org/abs/2509.01590)