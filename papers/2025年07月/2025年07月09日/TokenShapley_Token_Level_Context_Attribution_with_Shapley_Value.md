# TokenShapley：基于Shapley值的Token级别上下文归因方法

发布时间：2025年07月09日

`LLM应用

摘要讨论了大型语言模型（LLMs）在上下文学习中的表现，并提出了一种新的归因方法TokenShapley，用于提高模型生成结果的可解释性。这种方法结合了Shapley值和KNN检索技术，属于对LLM应用的改进和优化。因此，归类为LLM应用。` `数据科学`

> TokenShapley: Token Level Context Attribution with Shapley Value

# 摘要

> 大型语言模型（LLMs）在上下文学习中表现出色，但验证其生成结果的正确性仍面临难题。现有方法虽在句子层面实现了归因，但难以满足用户对响应中特定关键词（如数字、年份或名称）进行归因的需求。为解决这一问题，我们提出了TokenShapley——一种创新的令牌级归因方法。该方法融合了基于Shapley值的数据归因与受近期KNN增强型LLMs启发的基于KNN的检索技术。通过利用预计算的数据存储进行上下文检索，并借助Shapley值量化令牌的重要性，TokenShapley实现了细粒度的数据归因。在四个基准测试中的全面评估表明，TokenShapley在令牌级归因方面显著优于现有最先进方法，准确率提升了11-23%。

> Large language models (LLMs) demonstrate strong capabilities in in-context learning, but verifying the correctness of their generated responses remains a challenge. Prior work has explored attribution at the sentence level, but these methods fall short when users seek attribution for specific keywords within the response, such as numbers, years, or names. To address this limitation, we propose TokenShapley, a novel token-level attribution method that combines Shapley value-based data attribution with KNN-based retrieval techniques inspired by recent advances in KNN-augmented LLMs. By leveraging a precomputed datastore for contextual retrieval and computing Shapley values to quantify token importance, TokenShapley provides a fine-grained data attribution approach. Extensive evaluations on four benchmarks show that TokenShapley outperforms state-of-the-art baselines in token-level attribution, achieving an 11-23% improvement in accuracy.

[Arxiv](https://arxiv.org/abs/2507.05261)