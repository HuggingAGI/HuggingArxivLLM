# # 摘要
基于语言分析、众包和大型语言模型（LLMs）的在线用户反馈质量特征分类

发布时间：2025年06月13日

`LLM应用

理由：这篇论文探讨了在低数据环境下使用大型语言模型（LLMs）进行质量特征分类的应用。论文中提到LLMs在分类任务中的表现，并将其与其他方法进行比较，这属于LLMs的实际应用研究。` `软件工程` `用户体验`

> Classification of Quality Characteristics in Online User Feedback using Linguistic Analysis, Crowdsourcing and LLMs

# 摘要

> 软件质量属性（如可用性或可靠性）是决定移动应用用户满意度的关键因素，同时也是用户在线反馈的重要组成部分，为指导软件开发提供了宝贵的质量相关反馈。尽管在线用户反馈丰富多样，但由于其异质性以及缺乏合适的训练语料库，监督机器学习的应用受到限制。因此，我们研究了三种可能在低数据环境下有效的方法：基于质量相关关键词的语言模式（LPs）、众包微任务指令以及大型语言模型（LLMs）提示。我们评估了每种方法的可行性，并对其准确性进行了比较。在复杂多类别的质量特征分类中，基于LP的方法根据不同质量特征实现了0.38-0.92的不等精度，但召回率较低；众包方法在两个连续阶段实现了最佳平均准确率（0.63、0.72），这一结果可以被表现最佳的LLM条件（0.66）和基于LLMs多数投票的预测（0.68）所匹配。我们的研究发现表明，在这种低数据环境下，使用众包或LLMs而非专家的方法能够实现准确分类，而基于LP的方法仅具有有限的潜力。众包和LLMs在这一领域中的潜力甚至可能扩展到构建训练语料库。

> Software qualities such as usability or reliability are among the strongest determinants of mobile app user satisfaction and constitute a significant portion of online user feedback on software products, making it a valuable source of quality-related feedback to guide the development process. The abundance of online user feedback warrants the automated identification of quality characteristics, but the online user feedback's heterogeneity and the lack of appropriate training corpora limit the applicability of supervised machine learning. We therefore investigate the viability of three approaches that could be effective in low-data settings: language patterns (LPs) based on quality-related keywords, instructions for crowdsourced micro-tasks, and large language model (LLM) prompts. We determined the feasibility of each approach and then compared their accuracy. For the complex multiclass classification of quality characteristics, the LP-based approach achieved a varied precision (0.38-0.92) depending on the quality characteristic, and low recall; crowdsourcing achieved the best average accuracy in two consecutive phases (0.63, 0.72), which could be matched by the best-performing LLM condition (0.66) and a prediction based on the LLMs' majority vote (0.68). Our findings show that in this low-data setting, the two approaches that use crowdsourcing or LLMs instead of involving experts achieve accurate classifications, while the LP-based approach has only limited potential. The promise of crowdsourcing and LLMs in this context might even extend to building training corpora.

[Arxiv](https://arxiv.org/abs/2506.11722)