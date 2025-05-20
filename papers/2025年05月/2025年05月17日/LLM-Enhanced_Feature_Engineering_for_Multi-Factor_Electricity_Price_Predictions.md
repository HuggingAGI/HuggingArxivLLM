# LLM增强型特征工程助力多因素电价预测

发布时间：2025年05月17日

`LLM应用` `电力市场`

> LLM-Enhanced Feature Engineering for Multi-Factor Electricity Price Predictions

# 摘要

> 精准预测电价波动对风险管理与决策具有重要意义。传统模型在捕捉电力市场复杂非线性动态，尤其是面对天气与市场波动等外部因素时，往往力不从心。这些局限性在高波动的新南威尔士州电力市场中尤为明显。为突破这一瓶颈，我们提出了FAEP框架。该框架巧妙结合大型语言模型（LLMs）与先进特征工程，显著提升了预测精度。通过整合天气数据与电价突变等外部特征，并借助检索增强生成（RAG）技术进行特征提取，FAEP成功弥补了传统方法的不足。其内置的混合XGBoost-LSTM模型进一步优化了这些增强特征，构建了一个更 robust 的预测体系。实验结果表明，在澳大利亚新南威尔士州电力市场中，FAEP的表现超越现有模型，充分展现了LLM增强特征工程与混合机器学习架构的强大效能。

> Accurately forecasting electricity price volatility is crucial for effective risk management and decision-making. Traditional forecasting models often fall short in capturing the complex, non-linear dynamics of electricity markets, particularly when external factors like weather conditions and market volatility are involved. These limitations hinder their ability to provide reliable predictions in markets with high volatility, such as the New South Wales (NSW) electricity market. To address these challenges, we introduce FAEP, a Feature-Augmented Electricity Price Prediction framework. FAEP leverages Large Language Models (LLMs) combined with advanced feature engineering to enhance prediction accuracy. By incorporating external features such as weather data and price volatility jumps, and utilizing Retrieval-Augmented Generation (RAG) for effective feature extraction, FAEP overcomes the shortcomings of traditional approaches. A hybrid XGBoost-LSTM model in FAEP further refines these augmented features, resulting in a more robust prediction framework. Experimental results demonstrate that FAEP achieves state-of-art (SOTA) performance compared to other electricity price prediction models in the Australian New South Wale electricity market, showcasing the efficiency of LLM-enhanced feature engineering and hybrid machine learning architectures.

[Arxiv](https://arxiv.org/abs/2505.11890)