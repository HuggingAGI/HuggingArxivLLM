# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月21日

`LLM应用

摘要中讨论了如何将大型语言模型（LLMs）应用于贝叶斯网络的参数化，通过利用LLMs生成的概率知识来构建和改进这些网络。这属于将LLMs应用于特定任务或领域，因此归类为LLM应用。` `数据分析` `贝叶斯网络`

> Extracting Probabilistic Knowledge from Large Language Models for Bayesian Network Parameterization

# 摘要

> 大型语言模型（LLMs）作为事实知识库展现出巨大潜力，但其生成现实世界事件概率知识的能力尚未得到充分研究。本文探讨了利用LLMs中的固有概率知识，为贝叶斯网络（BN）捕获的事件及其关系生成概率估计。通过LLMs实现BN的参数化，能够在特定领域内进行概率建模。实验结果表明，在医疗保健到金融等领域的八十种公开贝叶斯网络中，查询LLMs关于事件的条件概率比随机、均匀分布及基于下一个令牌生成概率的方法更具意义。我们还发现，将从LLMs中提取的分布作为专家先验，可显著减少从极小数据中提取分布的系统性偏差。总体而言，本文提出了一种结合LLMs提取的概率知识与少量现实数据自动构建贝叶斯网络的策略。此外，我们评估了多种从LLMs中提取概率知识的提示策略，并建立了首个全面基准，用于评估LLMs在提取概率知识方面的性能。

> Large Language Models (LLMs) have demonstrated potential as factual knowledge bases; however, their capability to generate probabilistic knowledge about real-world events remains understudied. This paper investigates using probabilistic knowledge inherent in LLMs to derive probability estimates for statements concerning events and their interrelationships captured via a Bayesian Network (BN). Using LLMs in this context allows for the parameterization of BNs, enabling probabilistic modeling within specific domains. Experiments on eighty publicly available Bayesian Networks, from healthcare to finance, demonstrate that querying LLMs about the conditional probabilities of events provides meaningful results when compared to baselines, including random and uniform distributions, as well as approaches based on next-token generation probabilities. We explore how these LLM-derived distributions can serve as expert priors to refine distributions extracted from minimal data, significantly reducing systematic biases. Overall, this work introduces a promising strategy for automatically constructing Bayesian Networks by combining probabilistic knowledge extracted from LLMs with small amounts of real-world data. Additionally, we evaluate several prompting strategies for eliciting probabilistic knowledge from LLMs and establish the first comprehensive baseline for assessing LLM performance in extracting probabilistic knowledge.

[Arxiv](https://arxiv.org/abs/2505.15918)