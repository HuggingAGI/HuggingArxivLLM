# 基于因果生成对抗网络与深度强化学习的债券流动性敏感收益率预测研究，并采用大语言模型进行评估

发布时间：2025年02月24日

`LLM应用`

> Predicting Liquidity-Aware Bond Yields using Causal GANs and Deep Reinforcement Learning with LLM Evaluation

# 摘要

> 金融债券收益率预测面临数据稀缺性、宏观经济的非线性依赖关系以及不断变化的市场条件等多重挑战。本文提出了一种结合因果生成对抗网络（CausalGANs）和软Actor-批评家（SAC）强化学习的创新框架，用于生成四种主要债券类别（AAA、BAA、US10Y、垃圾债券）的高保真合成债券收益率数据。通过整合12个关键宏观经济变量，我们确保了统计保真性，保留了重要的市场特性。为了将这种依赖市场的合成数据转化为可操作的见解，我们采用了一种微调的大型语言模型（LLM）Qwen2.5-7B，该模型能够生成交易信号（买入/持有/卖出）、风险评估和波动率预测。通过自动化、人工和LLM评估，我们验证了该框架在预测性能上的优越性。统计结果显示，预测准确性、MAE评估（0.103%）、盈亏评估（60%的利润率）、LLM评估（3.37/5）以及专家评估（4.67/5）均优于现有方法。强化学习增强的合成数据生成实现了最小的平均绝对误差（0.103），证明了其在复制现实世界债券市场动态方面的有效性。我们不仅增强了数据驱动的交易策略，还提供了一个可扩展的、高保真的合成金融数据管道，用于风险与波动性管理和投资决策。这项工作在合成数据生成、LLM驱动的金融预测以及语言模型评估之间架起了一座桥梁，为AI驱动的金融决策做出了贡献。

> Financial bond yield forecasting is challenging due to data scarcity, nonlinear macroeconomic dependencies, and evolving market conditions. In this paper, we propose a novel framework that leverages Causal Generative Adversarial Networks (CausalGANs) and Soft Actor-Critic (SAC) reinforcement learning (RL) to generate high-fidelity synthetic bond yield data for four major bond categories (AAA, BAA, US10Y, Junk). By incorporating 12 key macroeconomic variables, we ensure statistical fidelity by preserving essential market properties. To transform this market dependent synthetic data into actionable insights, we employ a finetuned Large Language Model (LLM) Qwen2.5-7B that generates trading signals (BUY/HOLD/SELL), risk assessments, and volatility projections. We use automated, human and LLM evaluations, all of which demonstrate that our framework improves forecasting performance over existing methods, with statistical validation via predictive accuracy, MAE evaluation(0.103%), profit/loss evaluation (60% profit rate), LLM evaluation (3.37/5) and expert assessments scoring 4.67 out of 5. The reinforcement learning-enhanced synthetic data generation achieves the least Mean Absolute Error of 0.103, demonstrating its effectiveness in replicating real-world bond market dynamics. We not only enhance data-driven trading strategies but also provides a scalable, high-fidelity synthetic financial data pipeline for risk & volatility management and investment decision-making. This work establishes a bridge between synthetic data generation, LLM driven financial forecasting, and language model evaluation, contributing to AI-driven financial decision-making.

[Arxiv](https://arxiv.org/abs/2502.17011)