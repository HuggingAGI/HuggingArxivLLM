# FANformer：提升大型语言模型性能的有效周期性建模方法

发布时间：2025年02月28日

`LLM理论` `机器学习`

> FANformer: Improving Large Language Models Through Effective Periodicity Modeling

# 摘要

> 周期性作为关键特征之一，为人类学习中的结构化知识获取和系统化认知奠定了基础。然而，Transformer中周期性建模的缺陷影响了基于其构建的大型语言模型（LLMs）的学习效率和基本原理的建立。本文证明，引入有效的周期性建模可显著提升LLMs的性能。为此，我们提出了FANformer，通过将傅里叶分析网络（FAN）融入注意力机制，改进特征投影过程，实现高效的周期性建模。实验结果显示，FANformer在扩展模型规模和训练数据时始终优于Transformer，展现了其卓越的学习效率。为验证其有效性，我们在1万亿标记上预训练了FANformer-1B。与参数和训练数据相近的开源LLMs相比，FANformer-1B在下游任务中表现显著提升。这表明，FANformer是一种极具潜力的架构，为推进LLMs发展提供了有效解决方案。

> Periodicity, as one of the most important basic characteristics, lays the foundation for facilitating structured knowledge acquisition and systematic cognitive processes within human learning paradigms. However, the potential flaws of periodicity modeling in Transformer affect the learning efficiency and establishment of underlying principles from data for large language models (LLMs) built upon it. In this paper, we demonstrate that integrating effective periodicity modeling can improve the learning efficiency and performance of LLMs. We introduce FANformer, which integrates Fourier Analysis Network (FAN) into attention mechanism to achieve efficient periodicity modeling, by modifying the feature projection process of attention mechanism. Extensive experimental results on language modeling show that FANformer consistently outperforms Transformer when scaling up model size and training tokens, underscoring its superior learning efficiency. To further validate the effectiveness of FANformer, we pretrain a FANformer-1B on 1 trillion tokens. FANformer-1B exhibits marked improvements on downstream tasks compared to open-source LLMs with similar model parameters or training tokens. The results position FANformer as an effective and promising architecture for advancing LLMs.

[Arxiv](https://arxiv.org/abs/2502.21309)