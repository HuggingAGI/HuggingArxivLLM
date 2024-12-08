# Needle：一种由生成式 AI 驱动的、用于解答多模态数据中复杂自然语言查询的蒙特卡罗方法

发布时间：2024年11月30日

`LLM应用` `图像检索` `多模态数据`

> Needle: A Generative-AI Powered Monte Carlo Method for Answering Complex Natural Language Queries on Multi-modal Data

# 摘要

> 多模态数据，比如图像数据集，往往缺失能恰当捕捉其中丰富信息的详细描述。这就让回答这些领域中的复杂自然语言查询成为重大难题。特别是，传统的最近邻搜索中，元组和查询被建模为数据立方体中的点，而这里的查询和元组性质不同，导致传统的查询回答方案无法直接用于此场景。现有文献通过在自然语言和图像上联合训练的向量表示来应对图像数据的这一挑战。但由于种种原因，此技术在处理复杂查询时表现欠佳。
    本文通过引入一种由生成式人工智能（GenAI）驱动的蒙特卡罗方法来解决这一难题，该方法借助基础模型生成能捕捉自然语言查询复杂性的合成样本，并将其转换到多模态数据的同一空间。依此方法，我们开发了一个图像数据检索系统，并提出了实用的解决方案，以利用 GenAI 和向量表示的未来发展来提升系统性能。我们在各种基准数据集上的综合实验表明，我们的系统明显优于前沿技术。

> Multi-modal data, such as image data sets, often miss the detailed descriptions that properly capture the rich information encoded in them. This makes answering complex natural language queries a major challenge in these domains. In particular, unlike the traditional nearest-neighbor search, where the tuples and the query are modeled as points in a data cube, the query and the tuples are of different natures, making the traditional query answering solutions not directly applicable for such settings. Existing literature addresses this challenge for image data through vector representations jointly trained on natural language and images. This technique, however, underperforms for complex queries due to various reasons.
  This paper takes a step towards addressing this challenge by introducing a Generative-AI (GenAI) powered Monte Carlo method that utilizes foundation models to generate synthetic samples that capture the complexity of the natural language query and transform it to the same space of the multi-modal data. Following this method, we develop a system for image data retrieval and propose practical solutions that enable leveraging future advancements in GenAI and vector representations for improving our system's performance. Our comprehensive experiments on various benchmark datasets verify that our system significantly outperforms state-of-the-art techniques.

[Arxiv](https://arxiv.org/abs/2412.00639)