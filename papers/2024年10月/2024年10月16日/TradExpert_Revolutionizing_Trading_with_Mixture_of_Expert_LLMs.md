# TradExpert：专家混合LLMs引领交易革命

发布时间：2024年10月16日

`LLM应用

理由：这篇论文主要讨论了如何利用多个专业的大型语言模型（LLMs）来分析和整合多源数据，以在金融领域进行量化交易。论文提出的TradeExpert框架是一个具体的应用实例，展示了LLMs在金融预测和决策中的实际应用。因此，这篇论文应被归类为“LLM应用”。` `量化交易`

> TradExpert: Revolutionizing Trading with Mixture of Expert LLMs

# 摘要

> AI在金融领域的应用为量化交易开辟了新途径，尤其是通过LLMs的运用。然而，如何有效整合多源数据并融合结构化和非结构化数据仍是一大挑战。本文提出TradeExpert，一个基于专家混合（MoE）的创新框架，利用四个专业LLMs分别分析新闻、市场数据、阿尔法因子和基本面数据。这些专家LLMs的见解由通用专家LLM整合，最终做出预测或决策。通过特定提示，TradeExpert可在预测模式和排名模式间切换，分别用于股票走势预测和量化交易。此外，我们还发布了一个大规模金融数据集，全面评估TradeExpert的性能。实验结果显示，TradeExpert在所有交易场景中均表现卓越。

> The integration of Artificial Intelligence (AI) in the financial domain has opened new avenues for quantitative trading, particularly through the use of Large Language Models (LLMs). However, the challenge of effectively synthesizing insights from diverse data sources and integrating both structured and unstructured data persists. This paper presents TradeExpert, a novel framework that employs a mix of experts (MoE) approach, using four specialized LLMs, each analyzing distinct sources of financial data, including news articles, market data, alpha factors, and fundamental data. The insights of these expert LLMs are further synthesized by a General Expert LLM to make a final prediction or decision. With specific prompts, TradeExpert can be switched between the prediction mode and the ranking mode for stock movement prediction and quantitative stock trading, respectively. In addition to existing benchmarks, we also release a large-scale financial dataset to comprehensively evaluate TradeExpert's effectiveness. Our experimental results demonstrate TradeExpert's superior performance across all trading scenarios.

[Arxiv](https://arxiv.org/abs/2411.00782)