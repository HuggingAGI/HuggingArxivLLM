# 对大型时间序列模型进行金融微调

发布时间：2024年12月13日

`LLM应用` `时间序列预测`

> Financial Fine-tuning a Large Time Series Model

# 摘要

> 大型模型在自然语言处理、图像生成，尤其是近期的时间序列预测领域，展现出了前所未有的强大能力。这不禁让我们思考：若把市场价格视作时间序列，大型模型能否用于预测市场？本文中，我们通过评估最新的时间序列基础模型 TimesFM 在价格预测上的表现来回答此问题。我们发现，鉴于价格数据的不规则特性，直接运用 TimesFM 效果不佳，于是提议针对价格预测任务，在金融数据上对 TimeFM 进行微调。具体做法是，在涵盖 1 亿个时间点、包含从小时到日等不同粒度的金融工具的价格数据上，对最新的时间序列基础模型 TimesFM 进行持续预训练。微调后的模型在价格预测的准确性上高于基准模型。我们在各类金融市场中对模型进行了模拟交易，结果显示，在回报、夏普比率、最大回撤和交易成本等方面，它都优于各种基准。

> Large models have shown unprecedented capabilities in natural language processing, image generation, and most recently, time series forecasting. This leads us to ask the question: treating market prices as a time series, can large models be used to predict the market? In this paper, we answer this by evaluating the performance of the latest time series foundation model TimesFM on price prediction. We find that due to the irregular nature of price data, directly applying TimesFM gives unsatisfactory results and propose to fine-tune TimeFM on financial data for the task of price prediction. This is done by continual pre-training of the latest time series foundation model TimesFM on price data containing 100 million time points, spanning a range of financial instruments spanning hourly and daily granularities. The fine-tuned model demonstrates higher price prediction accuracy than the baseline model. We conduct mock trading for our model in various financial markets and show that it outperforms various benchmarks in terms of returns, sharpe ratio, max drawdown and trading cost.

[Arxiv](https://arxiv.org/abs/2412.09880)