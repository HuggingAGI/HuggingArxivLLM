# TradingGroup：具备自我反思与数据合成功能的多智能体交易系统

发布时间：2025年08月24日

`Agent` `金融科技`

> TradingGroup: A Multi-Agent Trading System with Self-Reflection and Data-Synthesis

# 摘要

> 大型语言模型（LLMs）的最新进展已在金融领域催生了强大的智能体应用，尤其适用于情感分析、财务报告解读和股票预测。然而，现有系统往往存在智能体间协调不足、缺乏结构化自我反思，以及难以获取高质量特定领域训练后数据（如包含市场状况和智能体决策的交易活动数据）等问题。这些数据对智能体理解市场动态、提升决策质量和实现高效协调至关重要。为此，我们提出了TradingGroup——一个多智能体交易系统，它通过自反思架构和端到端数据合成管道来解决这些问题。TradingGroup包含多个专业智能体，分别负责新闻情感分析、财务报告解读、股票趋势预测和交易风格适配，还有一个交易决策智能体，负责整合所有信号与风格偏好，生成买入、卖出或持有决策。具体来说，我们为股票预测、风格适配和决策智能体设计了自反思机制，通过提炼过往的成败经验，使其能在未来相似场景中进行类比推理；同时设计了动态风险管理模型，提供可配置的动态止损与止盈机制。此外，TradingGroup还嵌入了自动化数据合成与标注管道，能生成高质量训练后数据，通过后续训练进一步提升智能体性能。我们在五个真实股票数据集上的回测实验显示，TradingGroup的表现优于基于规则、机器学习、强化学习以及现有基于LLM的交易策略。

> Recent advancements in large language models (LLMs) have enabled powerful agent-based applications in finance, particularly for sentiment analysis, financial report comprehension, and stock forecasting. However, existing systems often lack inter-agent coordination, structured self-reflection, and access to high-quality, domain-specific post-training data such as data from trading activities including both market conditions and agent decisions. These data are crucial for agents to understand the market dynamics, improve the quality of decision-making and promote effective coordination. We introduce TradingGroup, a multi-agent trading system designed to address these limitations through a self-reflective architecture and an end-to-end data-synthesis pipeline. TradingGroup consists of specialized agents for news sentiment analysis, financial report interpretation, stock trend forecasting, trading style adaptation, and a trading decision making agent that merges all signals and style preferences to produce buy, sell or hold decisions. Specifically, we design self-reflection mechanisms for the stock forecasting, style, and decision-making agents to distill past successes and failures for similar reasoning in analogous future scenarios and a dynamic risk-management model to offer configurable dynamic stop-loss and take-profit mechanisms. In addition, TradingGroup embeds an automated data-synthesis and annotation pipeline that generates high-quality post-training data for further improving the agent performance through post-training. Our backtesting experiments across five real-world stock datasets demonstrate TradingGroup's superior performance over rule-based, machine learning, reinforcement learning, and existing LLM-based trading strategies.

[Arxiv](https://arxiv.org/abs/2508.17565)