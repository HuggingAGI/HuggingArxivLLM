# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月21日

`LLM应用` `情感分析`

> Can AI Read Between The Lines? Benchmarking LLMs On Financial Nuance

# 摘要

> 截至2025年，生成式人工智能（GenAI）已成为各行各业提升生产力的核心工具。除了文本生成，GenAI在编程、数据分析和研究工作流程中发挥着关键作用。随着大型语言模型（LLMs）的持续发展，评估其输出的可靠性和准确性变得尤为重要，尤其是在金融等专业且高风险领域。大多数现代LLMs通过将文本转换为数值向量来进行操作，例如余弦相似度搜索，以此生成响应。然而，这种抽象过程可能导致情感基调的误判，特别是在复杂的金融语境中。

虽然LLMs在日常语言的情感识别方面表现出色，但面对收益电话会议记录中那些微妙且策略性模糊的语言时，这些模型常常表现不佳。财务披露往往通过措辞谨慎的表述、展望性语言和行业特定术语来传达情感，即使对人类分析师而言，要始终如一地准确解读这些信息也颇具挑战性，更遑论AI模型了。

本文介绍了由查理·戈德堡教授领导的圣克拉拉微软实践项目的研究成果，该项目对微软的Copilot、OpenAI的ChatGPT、谷歌的Gemini以及传统机器学习模型在财务文本情感分析中的性能进行了基准测试。通过分析微软的收益电话会议记录，研究评估了LLM生成的情感与市场情感及股票走势之间的相关性，并对模型输出的准确性进行了评估。同时，研究还探讨了改进情感分析结果的提示工程技巧。为了评估情感基调与股票表现的一致性，研究开发了情感一致性可视化工具，并分析了微软各业务线的情感趋势，以确定哪些业务部门对市场情绪影响最大。


> As of 2025, Generative Artificial Intelligence (GenAI) has become a central tool for productivity across industries. Beyond text generation, GenAI now plays a critical role in coding, data analysis, and research workflows. As large language models (LLMs) continue to evolve, it is essential to assess the reliability and accuracy of their outputs, especially in specialized, high-stakes domains like finance. Most modern LLMs transform text into numerical vectors, which are used in operations such as cosine similarity searches to generate responses. However, this abstraction process can lead to misinterpretation of emotional tone, particularly in nuanced financial contexts. While LLMs generally excel at identifying sentiment in everyday language, these models often struggle with the nuanced, strategically ambiguous language found in earnings call transcripts. Financial disclosures frequently embed sentiment in hedged statements, forward-looking language, and industry-specific jargon, making it difficult even for human analysts to interpret consistently, let alone AI models. This paper presents findings from the Santa Clara Microsoft Practicum Project, led by Professor Charlie Goldenberg, which benchmarks the performance of Microsoft's Copilot, OpenAI's ChatGPT, Google's Gemini, and traditional machine learning models for sentiment analysis of financial text. Using Microsoft earnings call transcripts, the analysis assesses how well LLM-derived sentiment correlates with market sentiment and stock movements and evaluates the accuracy of model outputs. Prompt engineering techniques are also examined to improve sentiment analysis results. Visualizations of sentiment consistency are developed to evaluate alignment between tone and stock performance, with sentiment trends analyzed across Microsoft's lines of business to determine which segments exert the greatest influence.

[Arxiv](https://arxiv.org/abs/2505.16090)