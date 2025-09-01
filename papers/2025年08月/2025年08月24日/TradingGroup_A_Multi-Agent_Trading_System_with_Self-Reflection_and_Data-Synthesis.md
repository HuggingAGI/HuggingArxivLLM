# TradingGroup：具备自我反思与数据合成功能的多智能体交易系统

发布时间：2025年08月24日

`Agent` `金融科技`

> TradingGroup: A Multi-Agent Trading System with Self-Reflection and Data-Synthesis

# 摘要

> 大型语言模型（LLMs）的最新进展推动金融领域涌现出强大的智能体应用，尤其在情感分析、财务报告理解和股票预测方面。然而，现有系统往往缺乏智能体间协调、结构化自我反思能力，以及获取高质量特定领域训练后数据的途径——例如包含市场状况与智能体决策的交易活动数据。这些数据对智能体理解市场动态、提升决策质量和促进高效协作至关重要。为此，我们提出TradingGroup——一个多智能体交易系统，通过自我反思架构与端到端数据合成管道解决上述局限。TradingGroup包含多个专业智能体：新闻情感分析、财务报告解读、股票趋势预测、交易风格适配，以及一个整合所有信号与风格偏好并生成买卖持决策的交易决策智能体。具体而言，我们为股票预测、风格适配和决策智能体设计了自我反思机制，提炼过往成败经验以辅助未来相似场景的推理；同时构建动态风险管理模型，提供可配置的动态止损止盈机制。此外，TradingGroup内置自动化数据合成与标注管道，可生成高质量训练后数据，通过训练后进一步提升智能体性能。在五个真实股票数据集上的回测实验表明，TradingGroup的表现显著优于基于规则、机器学习、强化学习及现有LLM驱动的交易策略。

> Recent advancements in large language models (LLMs) have enabled powerful agent-based applications in finance, particularly for sentiment analysis, financial report comprehension, and stock forecasting. However, existing systems often lack inter-agent coordination, structured self-reflection, and access to high-quality, domain-specific post-training data such as data from trading activities including both market conditions and agent decisions. These data are crucial for agents to understand the market dynamics, improve the quality of decision-making and promote effective coordination. We introduce TradingGroup, a multi-agent trading system designed to address these limitations through a self-reflective architecture and an end-to-end data-synthesis pipeline. TradingGroup consists of specialized agents for news sentiment analysis, financial report interpretation, stock trend forecasting, trading style adaptation, and a trading decision making agent that merges all signals and style preferences to produce buy, sell or hold decisions. Specifically, we design self-reflection mechanisms for the stock forecasting, style, and decision-making agents to distill past successes and failures for similar reasoning in analogous future scenarios and a dynamic risk-management model to offer configurable dynamic stop-loss and take-profit mechanisms. In addition, TradingGroup embeds an automated data-synthesis and annotation pipeline that generates high-quality post-training data for further improving the agent performance through post-training. Our backtesting experiments across five real-world stock datasets demonstrate TradingGroup's superior performance over rule-based, machine learning, reinforcement learning, and existing LLM-based trading strategies.

[Arxiv](https://arxiv.org/abs/2508.17565)