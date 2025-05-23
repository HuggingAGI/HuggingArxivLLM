# 从大型语言模型中提取概率知识，用于贝叶斯网络参数化

发布时间：2025年05月21日

`LLM应用` `贝叶斯网络` `概率建模`

> Extracting Probabilistic Knowledge from Large Language Models for Bayesian Network Parameterization

# 摘要

> 大型语言模型（LLMs）在作为事实知识库方面潜力巨大，但在生成现实世界事件的概率知识方面仍有待深入研究。本文探讨了如何利用LLMs内在的概率知识，为通过贝叶斯网络（BN）捕捉的事件及其相互关系生成概率评估。通过将LLMs应用于这一领域，我们能够对贝叶斯网络进行参数化，从而在特定领域内实现概率建模。在涵盖医疗保健到金融等领域的八十种公开贝叶斯网络上进行的实验表明，与随机分布、均匀分布以及基于下一个词生成概率的方法相比，通过询问LLMs关于事件的条件概率可以产生有意义的结果。我们进一步研究了如何将从LLMs中提取的分布作为专家先验，以优化从有限数据中获得的分布，从而显著降低系统性偏差。总体而言，这项研究提出了一种有前景的方法，通过结合从LLMs中提取的概率知识与少量真实数据，实现贝叶斯网络的自动化构建。此外，我们还评估了多种从LLMs中提取概率知识的提示策略，并为评估LLMs在提取概率知识方面的能力建立了首个全面的基准。

> Large Language Models (LLMs) have demonstrated potential as factual knowledge bases; however, their capability to generate probabilistic knowledge about real-world events remains understudied. This paper investigates using probabilistic knowledge inherent in LLMs to derive probability estimates for statements concerning events and their interrelationships captured via a Bayesian Network (BN). Using LLMs in this context allows for the parameterization of BNs, enabling probabilistic modeling within specific domains. Experiments on eighty publicly available Bayesian Networks, from healthcare to finance, demonstrate that querying LLMs about the conditional probabilities of events provides meaningful results when compared to baselines, including random and uniform distributions, as well as approaches based on next-token generation probabilities. We explore how these LLM-derived distributions can serve as expert priors to refine distributions extracted from minimal data, significantly reducing systematic biases. Overall, this work introduces a promising strategy for automatically constructing Bayesian Networks by combining probabilistic knowledge extracted from LLMs with small amounts of real-world data. Additionally, we evaluate several prompting strategies for eliciting probabilistic knowledge from LLMs and establish the first comprehensive baseline for assessing LLM performance in extracting probabilistic knowledge.

[Arxiv](https://arxiv.org/abs/2505.15918)