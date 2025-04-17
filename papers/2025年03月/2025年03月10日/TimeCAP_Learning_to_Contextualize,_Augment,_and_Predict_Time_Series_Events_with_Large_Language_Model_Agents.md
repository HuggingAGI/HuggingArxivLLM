# TimeCAP：借助大型语言模型代理实现时间序列事件的上下文化、增强与预测

发布时间：2025年03月10日

`LLM应用` `气候建模` `金融分析`

> TimeCAP: Learning to Contextualize, Augment, and Predict Time Series Events with Large Language Model Agents

# 摘要

> 时间序列数据在气候建模、医疗监护及金融分析等领域发挥着关键作用。理解真实世界时间序列数据的上下文信息，对于准确可靠的事件预测至关重要。本文推出TimeCAP框架，创造性地将大型语言模型（LLMs）应用于时间序列数据的上下文处理，超越了传统预测器的角色。TimeCAP包含两个独立的LLM代理：一个生成文本摘要以捕获时间序列的上下文，另一个利用增强后的摘要进行更明智的预测。此外，TimeCAP采用多模态编码器，与LLM代理协同工作，通过相互增强输入中的上下文示例，提升预测性能。实验结果表明，TimeCAP在时间序列事件预测中超越现有最先进方法，包括那些将LLMs作为预测器的方法，F1分数平均提升28.75%。

> Time series data is essential in various applications, including climate modeling, healthcare monitoring, and financial analytics. Understanding the contextual information associated with real-world time series data is often essential for accurate and reliable event predictions. In this paper, we introduce TimeCAP, a time-series processing framework that creatively employs Large Language Models (LLMs) as contextualizers of time series data, extending their typical usage as predictors. TimeCAP incorporates two independent LLM agents: one generates a textual summary capturing the context of the time series, while the other uses this enriched summary to make more informed predictions. In addition, TimeCAP employs a multi-modal encoder that synergizes with the LLM agents, enhancing predictive performance through mutual augmentation of inputs with in-context examples. Experimental results on real-world datasets demonstrate that TimeCAP outperforms state-of-the-art methods for time series event prediction, including those utilizing LLMs as predictors, achieving an average improvement of 28.75% in F1 score.

[Arxiv](https://arxiv.org/abs/2502.11418)