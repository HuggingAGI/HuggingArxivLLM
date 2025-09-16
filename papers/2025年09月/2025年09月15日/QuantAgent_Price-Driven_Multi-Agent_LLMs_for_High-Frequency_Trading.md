# QuantAgent：面向高频交易的价格驱动多智能体LLMs

发布时间：2025年09月15日

`Agent` `金融科技`

> QuantAgent: Price-Driven Multi-Agent LLMs for High-Frequency Trading

# 摘要

> 近年来，大型语言模型（LLMs）在金融推理与市场洞察方面已展现出令人瞩目的能力。TradingAgent、FINMEM等多智能体LLM框架进一步将这类模型拓展至长期投资任务，借助基本面与情绪驱动的输入制定战略决策。但这类系统难以满足高频交易（HFT）对高速、高精度的严苛要求——高频交易需基于技术指标、图表形态、趋势特征等结构化短期信号，做出快速且具备风险意识的决策，这与传统金融LLM擅长的长期语义推理截然不同。

为此，我们推出QuantAgent——首个专为高频算法交易设计的多智能体LLM框架。该系统将交易流程拆解为指标、形态、趋势与风险四大专业智能体，每个智能体均配备领域专属工具与结构化推理能力，用于捕捉短时间窗口内市场动态的不同维度。在涵盖比特币、纳斯达克期货等十种金融工具的零样本评估中，QuantAgent在4小时交易周期内的预测精度与累计收益上均表现卓越，超越了强大的神经模型与基于规则的基准。研究结果表明，将结构化金融先验与语言原生推理相结合，为高频金融市场构建可追溯的实时决策系统开启了新可能。

> Recent advances in Large Language Models (LLMs) have demonstrated impressive capabilities in financial reasoning and market understanding. Multi-agent LLM frameworks such as TradingAgent and FINMEM augment these models to long-horizon investment tasks, leveraging fundamental and sentiment-based inputs for strategic decision-making. However, such systems are ill-suited for the high-speed, precision-critical demands of High-Frequency Trading (HFT). HFT requires rapid, risk-aware decisions based on structured, short-horizon signals, including technical indicators, chart patterns, and trend-based features, distinct from the long-term semantic reasoning typical of traditional financial LLM applications. To this end, we introduce QuantAgent, the first multi-agent LLM framework explicitly designed for high-frequency algorithmic trading. The system decomposes trading into four specialized agents, Indicator, Pattern, Trend, and Risk, each equipped with domain-specific tools and structured reasoning capabilities to capture distinct aspects of market dynamics over short temporal windows. In zero-shot evaluations across ten financial instruments, including Bitcoin and Nasdaq futures, QuantAgent demonstrates superior performance in both predictive accuracy and cumulative return over 4-hour trading intervals, outperforming random prediction baselines. Our findings suggest that combining structured financial priors with language-native reasoning unlocks new potential for traceable, real-time decision systems in high-frequency financial markets.

[Arxiv](https://arxiv.org/abs/2509.09995)