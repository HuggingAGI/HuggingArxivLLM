# 基于概率建模的LLM级联优化

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的可靠性问题，特别是复合LLM系统的性能分布和优化方法。论文提出了一种概率模型来分析和优化LLM级联系统的性能，这属于对LLM的理论研究和性能优化方法的探讨，因此应归类为LLM理论。` `系统优化`

> Rational Tuning of LLM Cascades via Probabilistic Modeling

# 摘要

> # 摘要
大型语言模型（LLMs）的可靠性问题近来备受关注。由于LLMs容易产生幻觉且对提示设计高度敏感，预测单个LLM的性能已颇具挑战。然而，对于复合LLM系统（如级联系统），问题更为复杂，因为除了每个模型的独立性能外，还需理解不同模型的错误率如何相互作用。本文提出了一种用于序列LLMs联合性能分布的概率模型，为通过连续优化合理调整LLM级联的置信度阈值提供了框架。与网格搜索相比，我们的参数化马尔可夫-耦合模型显著改善了级联长度和成本-误差曲线分辨率的运行时扩展，将其从难以处理的问题转化为低阶多项式问题。此外，随着级联长度的增加，基于连续优化的算法计算出的最优阈值逐渐优于网格搜索的结果，对于至少由三个模型组成的级联系统，成本-误差曲线下的面积平均提高了1.9%。总体而言，我们的马尔可夫-耦合模型为调整LLM级联性能提供了合理基础，并展示了概率方法在分析LLM系统中的潜力。

> Understanding the reliability of large language models (LLMs) has recently garnered significant attention. Given LLMs' propensity to hallucinate, as well as their high sensitivity to prompt design, it is already challenging to predict the performance of an individual LLM. However, the problem becomes more complex for compound LLM systems such as cascades, where in addition to each model's standalone performance, we must understand how the error rates of different models interact. In this paper, we present a probabilistic model for the joint performance distribution of a sequence of LLMs, which enables a framework for rationally tuning the confidence thresholds of a LLM cascade using continuous optimization. Compared to selecting confidence thresholds using grid search, our parametric Markov-copula model significantly improves runtime scaling with respect to the length of the cascade and the desired resolution of the cost-error curve, turning them from intractable into low-order polynomial. In addition, the optimal thresholds computed using our continuous optimization-based algorithm increasingly outperform those found via grid search as cascade length grows, improving the area under the cost-error curve by 1.9% on average for cascades consisting of at least three models. Overall, our Markov-copula model provides a rational basis for tuning LLM cascade performance and points to the potential of probabilistic methods in analyzing LLM systems.

[Arxiv](https://arxiv.org/abs/2501.09345)