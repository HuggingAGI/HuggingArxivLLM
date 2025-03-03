# # 时间一致性大型语言模型

发布时间：2025年02月28日

`LLM理论` `社会科学`

> Chronologically Consistent Large Language Models

# 摘要

> 大型语言模型在社会科学领域得到广泛应用，但其训练数据可能引入前瞻偏差和训练泄露。要打造优秀的时序一致语言模型，关键在于高效利用训练数据，即使面对时间受限的数据，仍需保持高精度。我们通过训练时序一致的大型语言模型，将训练数据的时间戳与其可用日期绑定，成功克服了这一挑战。这些模型不仅准确，其性能甚至可与最先进的开源权重模型相媲美。值得注意的是，前瞻偏差因模型和应用场景而异。即使时序一致的语言模型在语言理解上稍逊一筹，但在其之上应用回归或预测模型可以有效补偿这一不足。以资产定价为例，我们比较了基于新闻的组合策略，分别采用时序一致与存在偏差的语言模型，结果发现适度的前瞻偏差。

> Large language models are increasingly used in social sciences, but their training data can introduce lookahead bias and training leakage. A good chronologically consistent language model requires efficient use of training data to maintain accuracy despite time-restricted data. Here, we overcome this challenge by training chronologically consistent large language models timestamped with the availability date of their training data, yet accurate enough that their performance is comparable to state-of-the-art open-weight models. Lookahead bias is model and application-specific because even if a chronologically consistent language model has poorer language comprehension, a regression or prediction model applied on top of the language model can compensate. In an asset pricing application, we compare the performance of news-based portfolio strategies that rely on chronologically consistent versus biased language models and estimate a modest lookahead bias.

[Arxiv](https://arxiv.org/abs/2502.21206)