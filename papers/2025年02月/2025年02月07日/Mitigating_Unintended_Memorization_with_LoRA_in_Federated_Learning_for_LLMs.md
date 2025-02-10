# 联邦学习中，利用LoRA缓解大型语言模型的意外记忆问题

发布时间：2025年02月07日

`LLM理论` `联邦学习`

> Mitigating Unintended Memorization with LoRA in Federated Learning for LLMs

# 摘要

> 联邦学习（FL）是一种避免客户端间直接数据暴露的协作训练范式。然而，数据隐私问题依然存在：FL训练出的大型语言模型在给定前缀时，能够记忆并完成训练数据中的短语和句子。因此，恶意或好奇的客户端可能通过针对性提示恢复其他参与者的训练数据。本研究展示了联邦学习中一种流行且简单的微调策略——低秩适配（LoRA），能够将模型的记忆能力降低多达10倍。我们通过医疗问答任务进行微调，并注入来自外部临床数据集的多个分布外敏感序列副本，研究了这一效果。我们发现，对于多种Llama 2和3模型，记忆能力都有所降低，且LoRA在集中式学习中同样有效。此外，LoRA可与其他隐私保护技术（如梯度裁剪、高斯噪声、安全聚合和Goldfish损失）结合使用，在保持性能的同时进一步提升记录级别的隐私保护。

> Federated learning (FL) is a popular paradigm for collaborative training which avoids direct data exposure between clients. However, data privacy issues still remain: FL-trained large language models are capable of memorizing and completing phrases and sentences contained in training data when given with their prefixes. Thus, it is possible for adversarial and honest-but-curious clients to recover training data of other participants simply through targeted prompting. In this work, we demonstrate that a popular and simple fine-tuning strategy, low-rank adaptation (LoRA), reduces memorization during FL up to a factor of 10. We study this effect by performing a medical question-answering fine-tuning task and injecting multiple replicas of out-of-distribution sensitive sequences drawn from an external clinical dataset. We observe a reduction in memorization for a wide variety of Llama 2 and 3 models, and find that LoRA can reduce memorization in centralized learning as well. Furthermore, we show that LoRA can be combined with other privacy-preserving techniques such as gradient clipping and Gaussian noising, secure aggregation, and Goldfish loss to further improve record-level privacy while maintaining performance.

[Arxiv](https://arxiv.org/abs/2502.05087)