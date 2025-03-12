# # 探索大型语言模型的词义消歧能力
我们来探讨一下大型语言模型在词义消歧方面的潜力。通过分析模型在不同语境下对多义词的理解能力，我们可以更好地理解其语言处理机制。

发布时间：2025年03月11日

`LLM应用` `大型语言模型`

> Exploring the Word Sense Disambiguation Capabilities of Large Language Models

# 摘要

> 词汇语义消歧（WSD）是计算语言学中的经典任务，长期以来备受关注。但随着大型语言模型（LLMs）的兴起，人们对这一传统任务的兴趣逐渐减弱。本研究旨在评估各种LLM在WSD任务中的表现。我们对现有基准（XL-WSD）进行了扩展，重新设计了两个适合LLM的子任务：1）给定句子中的一个词，LLM需生成正确定义；2）给定句子中的一个词和一组预定义含义，LLM需选择正确含义。扩展后的基准基于XL-WSD和BabelNet构建。实验结果显示，LLMs在零样本学习中表现优异，但尚未超越当前最优方法。值得注意的是，一个经过微调的中等规模参数模型在所有模型中表现最佳，甚至超越了现有最优方法。


> Word Sense Disambiguation (WSD) is a historical task in computational linguistics that has received much attention over the years. However, with the advent of Large Language Models (LLMs), interest in this task (in its classical definition) has decreased. In this study, we evaluate the performance of various LLMs on the WSD task. We extend a previous benchmark (XL-WSD) to re-design two subtasks suitable for LLM: 1) given a word in a sentence, the LLM must generate the correct definition; 2) given a word in a sentence and a set of predefined meanings, the LLM must select the correct one. The extended benchmark is built using the XL-WSD and BabelNet. The results indicate that LLMs perform well in zero-shot learning but cannot surpass current state-of-the-art methods. However, a fine-tuned model with a medium number of parameters outperforms all other models, including the state-of-the-art.

[Arxiv](https://arxiv.org/abs/2503.08662)