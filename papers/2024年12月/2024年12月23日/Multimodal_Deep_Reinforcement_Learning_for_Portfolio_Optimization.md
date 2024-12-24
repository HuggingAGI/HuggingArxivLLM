# 多模态深度强化学习在投资组合优化中的应用

发布时间：2024年12月23日

`Agent`

> Multimodal Deep Reinforcement Learning for Portfolio Optimization

# 摘要

> 我们提出了一个强化学习框架，它借助包括历史股票价格、情绪分析以及新闻文章中的主题嵌入等多模态数据，来优化 SP100 股票的交易策略。基于金融强化学习的最新成果，我们致力于通过整合来自 SEC 备案和新闻标题的金融情绪数据来强化状态空间的表示，并优化奖励函数以更好地契合投资组合绩效指标。我们的方法涵盖了具有由价格数据、情绪得分和新闻嵌入构成的状态张量的深度强化学习，通过诸如 CNNs 和 RNNs 等先进的特征提取模型进行处理。通过与传统的投资组合优化技术和先进策略进行对比测试，我们证实了我们的方法在实现出色的投资组合绩效方面的效力。实证结果表明，我们的代理有超越标准基准的潜力，尤其是在基于利润的奖励函数下利用组合数据源时。

> We propose a reinforcement learning (RL) framework that leverages multimodal data including historical stock prices, sentiment analysis, and topic embeddings from news articles, to optimize trading strategies for SP100 stocks. Building upon recent advancements in financial reinforcement learning, we aim to enhance the state space representation by integrating financial sentiment data from SEC filings and news headlines and refining the reward function to better align with portfolio performance metrics. Our methodology includes deep reinforcement learning with state tensors comprising price data, sentiment scores, and news embeddings, processed through advanced feature extraction models like CNNs and RNNs. By benchmarking against traditional portfolio optimization techniques and advanced strategies, we demonstrate the efficacy of our approach in delivering superior portfolio performance. Empirical results showcase the potential of our agent to outperform standard benchmarks, especially when utilizing combined data sources under profit-based reward functions.

[Arxiv](https://arxiv.org/abs/2412.17293)