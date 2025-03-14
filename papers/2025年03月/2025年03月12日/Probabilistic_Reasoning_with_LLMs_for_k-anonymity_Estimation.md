# # 标题
基于大型语言模型的概率推理方法进行k-匿名性评估

发布时间：2025年03月12日

`LLM应用` `隐私保护` `数据安全`

> Probabilistic Reasoning with LLMs for k-anonymity Estimation

# 摘要

> 概率推理是人类与人工智能共有的关键能力，使我们能够应对决策中的不确定性和模糊性。本文提出了一种全新的不确定性下的数值推理任务，专注于估计包含隐私敏感信息的用户生成文档的k匿名性。我们提出了一种名为BRANCH的创新方法，该方法利用大型语言模型（LLMs）分解联合概率分布，通过将文本信息建模为随机变量来估计k值——即与给定信息匹配的人口规模。每个因素在整个人群中发生的概率通过独立的LLMs或检索增强生成系统进行估算，然后将这些概率整合为最终的k值。实验结果表明，我们的方法成功估计出正确的k值67%的时间，相比GPT-4的链式思考推理准确率提高了11%。此外，我们还利用LLMs的不确定性开发了k匿名性的预测区间，在近92%的情况下包含了正确值。

> Probabilistic reasoning is a key aspect of both human and artificial intelligence that allows for handling uncertainty and ambiguity in decision-making. In this paper, we introduce a novel numerical reasoning task under uncertainty, focusing on estimating the k-anonymity of user-generated documents containing privacy-sensitive information. We propose BRANCH, which uses LLMs to factorize a joint probability distribution to estimate the k-value-the size of the population matching the given information-by modeling individual pieces of textual information as random variables. The probability of each factor occurring within a population is estimated using standalone LLMs or retrieval-augmented generation systems, and these probabilities are combined into a final k-value. Our experiments show that this method successfully estimates the correct k-value 67% of the time, an 11% increase compared to GPT-4o chain-of-thought reasoning. Additionally, we leverage LLM uncertainty to develop prediction intervals for k-anonymity, which include the correct value in nearly 92% of cases.

[Arxiv](https://arxiv.org/abs/2503.09674)