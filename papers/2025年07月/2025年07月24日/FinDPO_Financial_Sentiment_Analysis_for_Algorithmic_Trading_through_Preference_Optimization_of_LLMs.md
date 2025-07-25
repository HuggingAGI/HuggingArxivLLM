# # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年07月24日

`LLM应用

理由：这篇论文探讨了大型语言模型在金融情感分析中的应用，特别是通过直接偏好优化（DPO）来提升模型的性能和推广能力。它展示了如何将LLM应用于金融投资策略，并取得了显著的实际效果，属于LLM的应用研究。` `情感分析`

> FinDPO: Financial Sentiment Analysis for Algorithmic Trading through Preference Optimization of LLMs

# 摘要

> 在线金融文本数据中的观点对交易决策和市场走势的影响日益深远，凸显了情感分析在量化这些观点性质和强度中的重要性。随着生成式AI（GenAI）的快速发展，监督微调（SFT）大型语言模型（LLMs）已成为金融情感分析的事实标准。然而，SFT范式可能导致对训练数据的记忆，并且通常无法很好地推广到未见样本。这对金融领域来说是一个关键限制，因为模型必须适应以前未观察到的事件以及金融领域特有的细微语言。

为此，我们引入了FinDPO，这是首个基于直接偏好优化（DPO）通过后训练人类偏好对齐的金融特定LLM框架。FinDPO在标准情感分类基准上实现了最先进的性能，平均优于现有监督微调模型11%。独特地，FinDPO框架通过一种新颖的“logit-to-score”转换，将微调后的因果LLM集成到现实的投资组合策略中，将离散的情感预测转换为连续的、可排序的情感分数（概率）。

通过这种方式，模拟表明，FinDPO是第一个基于情感的方法，即使在5个基点（bps）的实际交易成本下，也能保持每年67%的显著正回报和强大的风险调整后表现，如夏普比率2.0所示。


> Opinions expressed in online finance-related textual data are having an increasingly profound impact on trading decisions and market movements. This trend highlights the vital role of sentiment analysis as a tool for quantifying the nature and strength of such opinions. With the rapid development of Generative AI (GenAI), supervised fine-tuned (SFT) large language models (LLMs) have become the de facto standard for financial sentiment analysis. However, the SFT paradigm can lead to memorization of the training data and often fails to generalize to unseen samples. This is a critical limitation in financial domains, where models must adapt to previously unobserved events and the nuanced, domain-specific language of finance. To this end, we introduce FinDPO, the first finance-specific LLM framework based on post-training human preference alignment via Direct Preference Optimization (DPO). The proposed FinDPO achieves state-of-the-art performance on standard sentiment classification benchmarks, outperforming existing supervised fine-tuned models by 11% on the average. Uniquely, the FinDPO framework enables the integration of a fine-tuned causal LLM into realistic portfolio strategies through a novel 'logit-to-score' conversion, which transforms discrete sentiment predictions into continuous, rankable sentiment scores (probabilities). In this way, simulations demonstrate that FinDPO is the first sentiment-based approach to maintain substantial positive returns of 67% annually and strong risk-adjusted performance, as indicated by a Sharpe ratio of 2.0, even under realistic transaction costs of 5 basis points (bps).

[Arxiv](https://arxiv.org/abs/2507.18417)