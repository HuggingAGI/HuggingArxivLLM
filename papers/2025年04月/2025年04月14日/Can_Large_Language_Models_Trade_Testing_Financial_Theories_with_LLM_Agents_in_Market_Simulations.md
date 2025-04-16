# 大型语言模型能否像交易员一样操作？基于LLM代理的市场模拟实验探索金融理论

发布时间：2025年04月14日

`Agent

理由：这篇论文探讨了大型语言模型（LLMs）作为智能体在模拟股票市场中的应用，重点在于它们作为异质化竞争交易代理的行为和市场动态。虽然LLMs是核心工具，但研究的核心在于它们作为智能体的交互和市场模拟，因此归类为Agent。`

> Can Large Language Models Trade? Testing Financial Theories with LLM Agents in Market Simulations

# 摘要

> 本文构建了一个现实的模拟股票市场，其中大型语言模型（LLMs）作为异质化的竞争交易代理参与其中。开源框架集成了持续订单簿，支持市价单、限价单、部分成交、股息以及均衡清算等市场机制，同时代理具备多样化策略、信息集和初始资产配置。代理通过结构化输出和函数调用提交标准化决策，同时以自然语言表达其推理过程。研究发现：首先，LLMs能够始终坚持既定策略，可扮演价值投资者、动量交易者或做市商，具体角色由指令决定。其次，市场动态展现出真实金融市场特征，包括价格发现、泡沫、反应不足和战略性流动性供给。最后，该框架支持分析LLMs对不同市场条件的反应，类似于机器学习可解释性中的部分依赖图。此框架可模拟无解析解的金融理论，设计难以通过人类参与者实现的实验方案，并阐明提示如何生成影响市场稳定的相关行为。

> This paper presents a realistic simulated stock market where large language models (LLMs) act as heterogeneous competing trading agents. The open-source framework incorporates a persistent order book with market and limit orders, partial fills, dividends, and equilibrium clearing alongside agents with varied strategies, information sets, and endowments. Agents submit standardized decisions using structured outputs and function calls while expressing their reasoning in natural language. Three findings emerge: First, LLMs demonstrate consistent strategy adherence and can function as value investors, momentum traders, or market makers per their instructions. Second, market dynamics exhibit features of real financial markets, including price discovery, bubbles, underreaction, and strategic liquidity provision. Third, the framework enables analysis of LLMs' responses to varying market conditions, similar to partial dependence plots in machine-learning interpretability. The framework allows simulating financial theories without closed-form solutions, creating experimental designs that would be costly with human participants, and establishing how prompts can generate correlated behaviors affecting market stability.

[Arxiv](https://arxiv.org/abs/2504.10789)