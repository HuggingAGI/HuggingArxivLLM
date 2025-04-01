# # 超越对比学习：合成数据助力多层级相关性列表式训练
对比学习一直是机器学习领域的重要方法。如今，合成数据的引入使我们能够实现基于多层级相关性的列表式训练，这一突破标志着机器学习技术的又一次飞跃。

发布时间：2025年03月29日

`LLM应用` `信息检索` `数据科学`

> Beyond Contrastive Learning: Synthetic Data Enables List-wise Training with Multiple Levels of Relevance

# 摘要

> 大型语言模型（LLMs）的最新进展使合成数据在信息检索（IR）管道中得到了广泛应用。然而，当前主流的训练方法仍然是基于二元相关标签和InfoNCE损失的对比学习，即一个正样本与一个或多个负样本进行比较。这种设定将所有未标注为相关的文档一概视为负样本，忽视了它们实际相关性的细微差别，导致（a）丢失对排序有帮助的微妙信息，（b）易受标注噪声影响。为突破这一限制，我们完全摒弃真实训练文档和标注，改用开源LLMs直接生成合成文档，这些文档能够根据不同相关性级别准确回答真实用户查询。结合渐进相关性的合成排名上下文与适当的列表级损失（Wasserstein距离），我们的方法能够更精准地捕捉排序任务的本质。实验结果表明，与传统InfoNCE训练相比，我们的方法在各类IR数据集上表现显著更优。无需使用任何真实文档训练，我们的密集检索器性能远超自监督训练的同类模型。更重要的是，它与使用真实标注文档训练的模型表现相当，同时在分布偏移场景下更具鲁棒性，并在BEIR数据集的零样本评估中表现更佳。

> Recent advancements in large language models (LLMs) have allowed the augmentation of information retrieval (IR) pipelines with synthetic data in various ways. Yet, the main training paradigm remains: contrastive learning with binary relevance labels and the InfoNCE loss, where one positive document is compared against one or more negatives. This objective treats all documents that are not explicitly annotated as relevant on an equally negative footing, regardless of their actual degree of relevance, thus (a) missing subtle nuances that are useful for ranking and (b) being susceptible to annotation noise. To overcome this limitation, in this work we forgo real training documents and annotations altogether and use open-source LLMs to directly generate synthetic documents that answer real user queries according to several different levels of relevance. This fully synthetic ranking context of graduated relevance, together with an appropriate list-wise loss (Wasserstein distance), enables us to train dense retrievers in a way that better captures the ranking task. Experiments on various IR datasets show that our proposed approach outperforms conventional training with InfoNCE by a large margin. Without using any real documents for training, our dense retriever significantly outperforms the same retriever trained through self-supervision. More importantly, it matches the performance of the same retriever trained on real, labeled training documents of the same dataset, while being more robust to distribution shift and clearly outperforming it when evaluated zero-shot on the BEIR dataset collection.

[Arxiv](https://arxiv.org/abs/2503.23239)