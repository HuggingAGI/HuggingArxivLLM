# 解析语言与文化，助力多语言大模型评测

发布时间：2025年05月30日

`LLM应用` `文化计算`

> Disentangling Language and Culture for Evaluating Multilingual Large Language Models

# 摘要

> 本文提出了一种双评估框架，用于全面评估大型语言模型（LLMs）的多语言能力。通过从语言媒介和文化背景两个维度分解评估过程，该框架能够细致分析LLMs在跨语言处理中，分别在本族语境和跨文化语境下处理问题的能力。我们对多种模型进行了广泛的评估，发现了一种显著的“文化-语言协同”现象：当问题的文化背景与语言相匹配时，模型表现更佳。通过可解释性探查进一步研究这一现象，发现特定神经元在语言的文化背景中被激活的比例更高。这一激活比例或可作为评估模型训练期间多语言表现的潜在指标。我们的研究结果挑战了当前认为主要基于英语数据训练的LLMs在各语言上表现一致的普遍观念，并强调了从文化和语言角度进行模型评估的必要性。我们的代码可在https://yingjiahao14.github.io/Dual-Evaluation/获取。

> This paper introduces a Dual Evaluation Framework to comprehensively assess the multilingual capabilities of LLMs. By decomposing the evaluation along the dimensions of linguistic medium and cultural context, this framework enables a nuanced analysis of LLMs' ability to process questions within both native and cross-cultural contexts cross-lingually. Extensive evaluations are conducted on a wide range of models, revealing a notable "CulturalLinguistic Synergy" phenomenon, where models exhibit better performance when questions are culturally aligned with the language. This phenomenon is further explored through interpretability probing, which shows that a higher proportion of specific neurons are activated in a language's cultural context. This activation proportion could serve as a potential indicator for evaluating multilingual performance during model training. Our findings challenge the prevailing notion that LLMs, primarily trained on English data, perform uniformly across languages and highlight the necessity of culturally and linguistically model evaluations. Our code can be found at https://yingjiahao14. github.io/Dual-Evaluation/.

[Arxiv](https://arxiv.org/abs/2505.24635)