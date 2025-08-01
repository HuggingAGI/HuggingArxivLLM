# FinMarBa：一个基于市场信息的金融情感分类数据集

发布时间：2025年07月24日

`LLM应用` `投资组合优化`

> FinMarBa: A Market-Informed Dataset for Financial Sentiment Classification

# 摘要

> 本文提出了一种新颖的层级框架，用于投资组合优化。通过将轻量级大型语言模型（LLMs）与深度强化学习（DRL）相结合，该框架巧妙地将来自财经新闻的情绪信号与传统市场指标相结合。我们的三层架构采用基RL代理处理混合数据，元代理聚合它们的决策，超级代理则根据市场数据和情绪分析合并决策。在2018年至2024年的数据上进行评估（经过2000年至2017年的训练），该框架实现了26%的年化回报率和1.2的夏普比率，显著优于等权重和标普500基准。主要贡献包括可扩展的跨模态集成、用于增强稳定性的层级RL结构，以及开源可复现性。

> This paper presents a novel hierarchical framework for portfolio optimization, integrating lightweight Large Language Models (LLMs) with Deep Reinforcement Learning (DRL) to combine sentiment signals from financial news with traditional market indicators. Our three-tier architecture employs base RL agents to process hybrid data, meta-agents to aggregate their decisions, and a super-agent to merge decisions based on market data and sentiment analysis. Evaluated on data from 2018 to 2024, after training on 2000-2017, the framework achieves a 26% annualized return and a Sharpe ratio of 1.2, outperforming equal-weighted and S&P 500 benchmarks. Key contributions include scalable cross-modal integration, a hierarchical RL structure for enhanced stability, and open-source reproducibility.

[Arxiv](https://arxiv.org/abs/2507.22932)