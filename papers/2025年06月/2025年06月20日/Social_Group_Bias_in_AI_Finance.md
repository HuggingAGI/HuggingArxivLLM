# # AI金融中的社会群体偏见
人工智能在金融领域的应用中，社会群体偏见是一个复杂且值得深入探讨的问题。

发布时间：2025年06月20日

`LLM应用` `机器学习`

> Social Group Bias in AI Finance

# 摘要

> 金融机构越来越多地依赖大型语言模型 (LLMs) 进行高风险决策。然而，未经谨慎监督的模型部署可能加剧有害偏见。本文通过信用决策任务深入研究 LLM 中的种族偏见，揭示了这些偏见在金融应用中的广泛影响。我们提出了一种可重复的反事实测试框架，用于评估模型对除种族外所有属性相同的模拟抵押贷款申请人的反应。结果显示，模型中存在显著的种族差异，甚至超过了历史偏见水平。通过分层分析，我们追踪了敏感属性在模型内部表示中的传播路径。在此基础上，我们提出了一种控制向量干预方法，成功将种族差异减少了 70%（平均减少 33%），同时保持了模型的整体性能。我们的研究为识别和缓解金融 LLM 中的偏见提供了一个透明且实用的工具包。

> Financial institutions increasingly rely on large language models (LLMs) for high-stakes decision-making. However, these models risk perpetuating harmful biases if deployed without careful oversight. This paper investigates racial bias in LLMs specifically through the lens of credit decision-making tasks, operating on the premise that biases identified here are indicative of broader concerns across financial applications. We introduce a reproducible, counterfactual testing framework that evaluates how models respond to simulated mortgage applicants identical in all attributes except race. Our results reveal significant race-based discrepancies, exceeding historically observed bias levels. Leveraging layer-wise analysis, we track the propagation of sensitive attributes through internal model representations. Building on this, we deploy a control-vector intervention that effectively reduces racial disparities by up to 70% (33% on average) without impairing overall model performance. Our approach provides a transparent and practical toolkit for the identification and mitigation of bias in financial LLM deployments.

[Arxiv](https://arxiv.org/abs/2506.17490)