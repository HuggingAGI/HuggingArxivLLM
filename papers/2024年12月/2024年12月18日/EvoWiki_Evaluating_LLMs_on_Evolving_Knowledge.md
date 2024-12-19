# EvoWiki：评估关于不断演变知识的大型语言模型

发布时间：2024年12月18日

`LLM应用` `语言模型` `知识评估`

> EvoWiki: Evaluating LLMs on Evolving Knowledge

# 摘要

> 知识利用对于大型语言模型（LLMs）而言是关键一环，搞清楚它们如何适应不断变化的知识，对于有效运用这些模型十分重要。然而，现有的基准大多是静态的，难以捕捉到 LLMs 和知识的演变特性，从而导致出现不准确和易受污染等问题。在本文中，我们推出了 EvoWiki 这一不断进化的数据集，其通过将信息划分为稳定、演变和未知这几种状态，来反映知识的演变情况。EvoWiki 能够完全自动更新，可对不断变化的知识和新发布的 LLMs 进行精准评估。通过与检索增强生成（RAG）和持续学习（CL）的实验，我们对 LLMs 适应不断演变知识的效果进行了评估。结果显示，当前的模型在应对演变的知识时往往表现不佳，常常给出过时或错误的回答。此外，该数据集凸显了 RAG 和 CL 之间的协同作用，展现了它们在更好适应不断演变知识方面的潜力。EvoWiki 为推动大型语言模型知识演变能力的未来研究，提供了有力的基准。

> Knowledge utilization is a critical aspect of LLMs, and understanding how they adapt to evolving knowledge is essential for their effective deployment. However, existing benchmarks are predominantly static, failing to capture the evolving nature of LLMs and knowledge, leading to inaccuracies and vulnerabilities such as contamination. In this paper, we introduce EvoWiki, an evolving dataset designed to reflect knowledge evolution by categorizing information into stable, evolved, and uncharted states. EvoWiki is fully auto-updatable, enabling precise evaluation of continuously changing knowledge and newly released LLMs. Through experiments with Retrieval-Augmented Generation (RAG) and Contunual Learning (CL), we evaluate how effectively LLMs adapt to evolving knowledge. Our results indicate that current models often struggle with evolved knowledge, frequently providing outdated or incorrect responses. Moreover, the dataset highlights a synergistic effect between RAG and CL, demonstrating their potential to better adapt to evolving knowledge. EvoWiki provides a robust benchmark for advancing future research on the knowledge evolution capabilities of large language models.

[Arxiv](https://arxiv.org/abs/2412.13582)