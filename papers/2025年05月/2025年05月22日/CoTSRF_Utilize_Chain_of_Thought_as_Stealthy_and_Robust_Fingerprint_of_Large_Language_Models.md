# # CoTSRF：将思维链作为大型语言模型的隐秘且稳健指纹

发布时间：2025年05月22日

`LLM理论`

> CoTSRF: Utilize Chain of Thought as Stealthy and Robust Fingerprint of Large Language Models

# 摘要

> 尽管开源大语言模型（LLMs）性能优越，但它们容易遭受滥用。为了解决这一问题，近期研究提出了LLM指纹识别方法，用于识别可疑应用背后的特定源LLM。然而，这些方法未能实现隐蔽且稳健的指纹验证。本文提出了一种新型的LLM指纹识别方案，名为CoTSRF，它利用思维链（CoT）作为LLM的指纹。CoTSRF首先通过精心设计的CoT查询，收集源LLM的响应。然后，它运用对比学习训练一个CoT提取器，从响应中提取CoT特征（即指纹）。最后，CoTSRF通过比较源LLM和可疑LLM的CoT特征之间的Kullback-Leibler散度与经验阈值，进行指纹验证。我们进行了各种实验，以展示我们提出的CoTSRF在指纹识别LLMs方面的优势，特别是在隐蔽和稳健的指纹验证方面。

> Despite providing superior performance, open-source large language models (LLMs) are vulnerable to abusive usage. To address this issue, recent works propose LLM fingerprinting methods to identify the specific source LLMs behind suspect applications. However, these methods fail to provide stealthy and robust fingerprint verification. In this paper, we propose a novel LLM fingerprinting scheme, namely CoTSRF, which utilizes the Chain of Thought (CoT) as the fingerprint of an LLM. CoTSRF first collects the responses from the source LLM by querying it with crafted CoT queries. Then, it applies contrastive learning to train a CoT extractor that extracts the CoT feature (i.e., fingerprint) from the responses. Finally, CoTSRF conducts fingerprint verification by comparing the Kullback-Leibler divergence between the CoT features of the source and suspect LLMs against an empirical threshold. Various experiments have been conducted to demonstrate the advantage of our proposed CoTSRF for fingerprinting LLMs, particularly in stealthy and robust fingerprint verification.

[Arxiv](https://arxiv.org/abs/2505.16785)