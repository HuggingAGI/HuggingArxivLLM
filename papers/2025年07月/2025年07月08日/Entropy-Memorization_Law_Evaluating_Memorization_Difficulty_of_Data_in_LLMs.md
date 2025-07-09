# 熵-记忆定律：探索大型语言模型的数据记忆难度评估

发布时间：2025年07月08日

`LLM理论` `大型语言模型` `数据安全`

> Entropy-Memorization Law: Evaluating Memorization Difficulty of Data in LLMs

# 摘要

> 大型语言模型（LLMs）具有记忆训练数据的能力，有时甚至会在适当提示下逐字复现内容。本研究聚焦记忆领域一个基础但尚未被充分探索的问题：如何表征 LLMs 中训练数据的记忆难度？通过在开源模型家族 OLMo 上进行实证研究，我们提出了熵-记忆定律。该定律揭示数据熵与记忆分数之间存在线性相关性。此外，在一项关于记忆高度随机字符串（即“乱码”）的案例研究中，我们发现这些看似随机的序列，相较于更广泛的训练语料库，表现出意外低的实证熵。基于熵-记忆定律的发现策略，我们提出了一种简单而有效的方法来区分训练数据和测试数据，从而实现了数据集推断（DI）。

> Large Language Models (LLMs) are known to memorize portions of their training data, sometimes reproducing content verbatim when prompted appropriately. In this work, we investigate a fundamental yet under-explored question in the domain of memorization: How to characterize memorization difficulty of training data in LLMs? Through empirical experiments on OLMo, a family of open models, we present the Entropy-Memorization Law. It suggests that data entropy is linearly correlated with memorization score. Moreover, in a case study of memorizing highly randomized strings, or "gibberish", we observe that such sequences, despite their apparent randomness, exhibit unexpectedly low empirical entropy compared to the broader training corpus. Adopting the same strategy to discover Entropy-Memorization Law, we derive a simple yet effective approach to distinguish training and testing data, enabling Dataset Inference (DI).

[Arxiv](https://arxiv.org/abs/2507.06056)