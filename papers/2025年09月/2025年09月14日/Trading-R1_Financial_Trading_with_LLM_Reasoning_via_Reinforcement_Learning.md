# Trading-R1：基于LLM推理与强化学习的金融交易

发布时间：2025年09月14日

`LLM应用` `金融科技`

> Trading-R1: Financial Trading with LLM Reasoning via Reinforcement Learning

# 摘要

> 在金融AI领域，培养与人类金融分析师和交易员相当的专业、结构化推理能力仍是核心挑战——毕竟市场对可解释性和信任度有极高要求。传统时间序列模型难以解释，大型语言模型（LLMs）则在将自然语言分析转化为规范可执行的交易时遇到瓶颈。尽管推理型大型语言模型在逐步规划与验证方面已有所突破，但其在风险敏感型金融决策中的应用尚未得到充分探索。为此，我们提出Trading-R1——一种具备金融感知能力的模型，它融合战略思考与规划，可实现全面的论点构建、事实驱动的分析以及波动率调整的决策制定。Trading-R1通过监督微调与强化学习，并采用三阶段由易到难的训练课程，确保推理过程与交易原则高度契合。训练数据来自Tauric-TR1-DB语料库，该库包含10万条样本，覆盖18个月的时间范围、14只股票及五种异构金融数据源。在六种主要股票和ETF上的评估结果显示，与开源、专有指令跟随模型及推理模型相比，Trading-R1的风险调整后收益更高，回撤更低。该系统能生成结构化、基于证据的投资论点，为规范且可解释的交易决策提供支持。Trading-R1终端将在https://github.com/TauricResearch/Trading-R1开源发布。

> Developing professional, structured reasoning on par with human financial analysts and traders remains a central challenge in AI for finance, where markets demand interpretability and trust. Traditional time-series models lack explainability, while LLMs face challenges in turning natural-language analysis into disciplined, executable trades. Although reasoning LLMs have advanced in step-by-step planning and verification, their application to risk-sensitive financial decisions is underexplored. We present Trading-R1, a financially-aware model that incorporates strategic thinking and planning for comprehensive thesis composition, facts-grounded analysis, and volatility-adjusted decision making. Trading-R1 aligns reasoning with trading principles through supervised fine-tuning and reinforcement learning with a three-stage easy-to-hard curriculum. Training uses Tauric-TR1-DB, a 100k-sample corpus spanning 18 months, 14 equities, and five heterogeneous financial data sources. Evaluated on six major equities and ETFs, Trading-R1 demonstrates improved risk-adjusted returns and lower drawdowns compared to both open-source and proprietary instruction-following models as well as reasoning models. The system generates structured, evidence-based investment theses that support disciplined and interpretable trading decisions. Trading-R1 Terminal will be released at https://github.com/TauricResearch/Trading-R1.

[Arxiv](https://arxiv.org/abs/2509.11420)