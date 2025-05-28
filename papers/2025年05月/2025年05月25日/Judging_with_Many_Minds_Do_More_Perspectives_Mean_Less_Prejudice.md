# 集思广益，明辨是非：多元视角能否减少偏见？

发布时间：2025年05月25日

`LLM应用` `人工智能` `智能系统`

> Judging with Many Minds: Do More Perspectives Mean Less Prejudice?

# 摘要

> LLM作为评估者（LLM-as-Judge）作为一种可扩展的人类评估替代方案已经出现，使大型语言模型（LLMs）能够在训练中提供奖励信号。尽管最近的工作探索了多智能体扩展，如多智能体辩论和元评估，以提高评估质量，但这些设置中内在偏见的表现仍是一个未被充分探索的问题。本研究系统分析了四种多样化的偏见类型：位置偏见、冗长偏见、思维链偏见和随大流偏见。我们评估了这些偏见在两个广泛采用的多智能体LLM-as-Judge框架中的表现：多智能体辩论和LLM作为元评估者。结果显示，辩论框架在初始辩论后显著放大了偏见，并且这种增加的偏见在后续轮次中持续存在，而元评估方法则表现出更强的抵抗力。我们进一步研究了将PINE（一种领先的单智能体去偏见方法）作为无偏见代理整合到这些系统中的效果。结果表明，这种无偏见代理在辩论设置中有效减少了偏见，但在元评估场景中提供的益处较少。我们的工作为多智能体LLM-as-Judge系统中的偏见行为提供了全面研究，并强调了在协作评估环境中实施针对性偏见缓解策略的必要性。

> LLM-as-Judge has emerged as a scalable alternative to human evaluation, enabling large language models (LLMs) to provide reward signals in trainings. While recent work has explored multi-agent extensions such as multi-agent debate and meta-judging to enhance evaluation quality, the question of how intrinsic biases manifest in these settings remains underexplored. In this study, we conduct a systematic analysis of four diverse bias types: position bias, verbosity bias, chain-of-thought bias, and bandwagon bias. We evaluate these biases across two widely adopted multi-agent LLM-as-Judge frameworks: Multi-Agent-Debate and LLM-as-Meta-Judge. Our results show that debate framework amplifies biases sharply after the initial debate, and this increased bias is sustained in subsequent rounds, while meta-judge approaches exhibit greater resistance. We further investigate the incorporation of PINE, a leading single-agent debiasing method, as a bias-free agent within these systems. The results reveal that this bias-free agent effectively reduces biases in debate settings but provides less benefit in meta-judge scenarios. Our work provides a comprehensive study of bias behavior in multi-agent LLM-as-Judge systems and highlights the need for targeted bias mitigation strategies in collaborative evaluation settings.

[Arxiv](https://arxiv.org/abs/2505.19477)