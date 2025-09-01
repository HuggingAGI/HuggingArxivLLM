# QTMRL：基于多指标引导强化学习的量化交易决策智能体

发布时间：2025年08月28日

`强化学习` `金融科技`

> QTMRL: An Agent for Quantitative Trading Decision-Making Based on Multi-Indicator Guided Reinforcement Learning

# 摘要

> 在高度波动且充满不确定性的全球金融市场中，依赖统计建模或经验规则的传统量化交易模型，常因假设僵化、泛化能力有限，难以适应动态的市场变化和黑天鹅事件。为解决这些问题，本文提出QTMRL（量化交易多指标强化学习）——一种融合多维技术指标与强化学习（RL）的智能交易智能体，旨在实现自适应且稳定的投资组合管理。我们首先利用23年（2000-2022年）标普500指数中5个行业16只代表性股票的日度OHLCV数据，构建了全面的多指标数据集，并通过趋势、波动率和动量指标丰富原始数据，以捕捉整体市场动态。随后，我们基于优势演员-评论家（A2C）算法设计了轻量级强化学习框架，包含数据处理、A2C算法及交易智能体模块，支持策略学习与可执行交易决策。大量实验在不同市场状态下将QTMRL与9个基线模型（如ARIMA、LSTM、移动平均策略）对比，验证了其在盈利能力、风险调整及下行风险控制上的优越性。QTMRL代码已公开于https://github.com/ChenJiahaoJNU/QTMRL.git

> In the highly volatile and uncertain global financial markets, traditional quantitative trading models relying on statistical modeling or empirical rules often fail to adapt to dynamic market changes and black swan events due to rigid assumptions and limited generalization. To address these issues, this paper proposes QTMRL (Quantitative Trading Multi-Indicator Reinforcement Learning), an intelligent trading agent combining multi-dimensional technical indicators with reinforcement learning (RL) for adaptive and stable portfolio management. We first construct a comprehensive multi-indicator dataset using 23 years of S&P 500 daily OHLCV data (2000-2022) for 16 representative stocks across 5 sectors, enriching raw data with trend, volatility, and momentum indicators to capture holistic market dynamics. Then we design a lightweight RL framework based on the Advantage Actor-Critic (A2C) algorithm, including data processing, A2C algorithm, and trading agent modules to support policy learning and actionable trading decisions. Extensive experiments compare QTMRL with 9 baselines (e.g., ARIMA, LSTM, moving average strategies) across diverse market regimes, verifying its superiority in profitability, risk adjustment, and downside risk control. The code of QTMRL is publicly available at https://github.com/ChenJiahaoJNU/QTMRL.git

[Arxiv](https://arxiv.org/abs/2508.20467)