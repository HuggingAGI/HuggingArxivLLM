# 记忆化还是插值？基于输入扰动分析识别LLM记忆化行为

发布时间：2025年05月05日

`LLM应用` `数据隐私` `模型评估`

> Memorization or Interpolation ? Detecting LLM Memorization through Input Perturbation Analysis

# 摘要

> 尽管大型语言模型（LLMs）在海量数据集上表现出色，但它们也可能“背诵”训练数据，而非真正理解。这种“死记硬背”现象引发了关于数据隐私、知识产权和模型评估可靠性的担忧。本文提出了一种全新的方法PEARL，用于检测LLMs的记忆行为。PEARL通过评估模型对输入微扰的敏感性，无需访问模型内部即可发现记忆现象。我们研究了输入微扰如何影响输出的一致性，从而区分真实理解和死记硬背。在Pythia开源模型上的大量实验表明，PEARL提供了一个 robust的框架，能够准确识别模型何时只是简单复述所学内容。在GPT 4o模型上的应用中，PEARL不仅发现了对《圣经》经典文本或HumanEval常见代码的记忆，还证明了它可以提供支持性证据，表明某些数据（如《纽约时报》新闻文章）很可能是给定模型训练数据的一部分。

> While Large Language Models (LLMs) achieve remarkable performance through training on massive datasets, they can exhibit concerning behaviors such as verbatim reproduction of training data rather than true generalization. This memorization phenomenon raises significant concerns about data privacy, intellectual property rights, and the reliability of model evaluations. This paper introduces PEARL, a novel approach for detecting memorization in LLMs. PEARL assesses how sensitive an LLM's performance is to input perturbations, enabling memorization detection without requiring access to the model's internals. We investigate how input perturbations affect the consistency of outputs, enabling us to distinguish between true generalization and memorization. Our findings, following extensive experiments on the Pythia open model, provide a robust framework for identifying when the model simply regurgitates learned information. Applied on the GPT 4o models, the PEARL framework not only identified cases of memorization of classic texts from the Bible or common code from HumanEval but also demonstrated that it can provide supporting evidence that some data, such as from the New York Times news articles, were likely part of the training data of a given model.

[Arxiv](https://arxiv.org/abs/2505.03019)