# FinGPT: 利用传播感知与上下文增强的LLMs提升情绪驱动的股票走势预测

发布时间：2024年12月14日

`LLM应用

理由：该论文主要讨论了如何利用大型语言模型（LLMs）进行金融情感分析，并通过整合新闻传播广度、上下文数据和明确指令来提升股价预测的准确性。这属于LLM在实际应用中的具体使用场景，因此归类为“LLM应用”。` `情感分析`

> FinGPT: Enhancing Sentiment-Based Stock Movement Prediction with Dissemination-Aware and Context-Enriched LLMs

# 摘要

> # 摘要
金融情感分析是理解新闻如何影响股价的关键。近年来，大型语言模型（LLMs）凭借其强大的文本分析能力，被广泛应用于这一领域。然而，这些模型往往只关注新闻内容本身，忽视了其传播过程，导致难以准确预测短期股价波动。此外，现有方法在提示中往往缺乏足够的上下文数据和明确指令，限制了LLMs对新闻的解读能力。本文提出了一种数据驱动的方法，通过整合新闻传播广度、上下文数据和明确指令，提升了基于LLM的情感驱动的股价预测能力。我们通过聚类近期与公司相关的新闻，评估其传播范围和影响力，并在提示中加入更具体的数据和精确指令。这些数据用于构建指令调优数据集，以微调LLM，从而预测短期股价走势。实验结果表明，与现有方法相比，我们的方法将预测准确率提高了8%。

> Financial sentiment analysis is crucial for understanding the influence of news on stock prices. Recently, large language models (LLMs) have been widely adopted for this purpose due to their advanced text analysis capabilities. However, these models often only consider the news content itself, ignoring its dissemination, which hampers accurate prediction of short-term stock movements. Additionally, current methods often lack sufficient contextual data and explicit instructions in their prompts, limiting LLMs' ability to interpret news. In this paper, we propose a data-driven approach that enhances LLM-powered sentiment-based stock movement predictions by incorporating news dissemination breadth, contextual data, and explicit instructions. We cluster recent company-related news to assess its reach and influence, enriching prompts with more specific data and precise instructions. This data is used to construct an instruction tuning dataset to fine-tune an LLM for predicting short-term stock price movements. Our experimental results show that our approach improves prediction accuracy by 8\% compared to existing methods.

[Arxiv](https://arxiv.org/abs/2412.10823)