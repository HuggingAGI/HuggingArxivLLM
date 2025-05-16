# 稀疏自编码器能否助力Java函数缺陷检测？

发布时间：2025年05月15日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在软件漏洞检测中的应用，特别是如何利用LLMs的内部表示来检测漏洞。研究重点在于LLMs的应用，而非其理论或架构，因此归类为LLM应用。` `信息安全` `漏洞检测`

> Are Sparse Autoencoders Useful for Java Function Bug Detection?

# 摘要

> 软件漏洞，如缓冲区溢出和SQL注入，是导致安全漏洞的主要根源。传统漏洞检测方法虽仍不可或缺，但受限于高误报率、可扩展性问题及对人工参与的依赖。这推动了基于AI的自动化漏洞检测和安全代码生成方法的发展。大型语言模型（LLMs）虽为分类任务开辟了新途径，但其复杂性和不透明性对可解释性和部署提出挑战。稀疏自动编码器（SAEs）为这一问题提供了一个有前景的解决方案。

我们研究了SAEs是否可以作为轻量级、可解释的替代方案，用于检测Java函数中的漏洞。通过评估SAEs在GPT-2 Small和Gemma 2B表示上的效果，我们发现其无需微调底层LLMs即可有效识别漏洞行为。实验结果表明，基于SAE的特征使漏洞检测的F1分数达到89%，显著优于微调的Transformer编码器基线。这是首个实证证据，证明SAEs可以直接从预训练LLMs的内部表示中检测软件漏洞，无需任何微调或特定任务的监督。

> Software vulnerabilities such as buffer overflows and SQL injections are a major source of security breaches. Traditional methods for vulnerability detection remain essential but are limited by high false positive rates, scalability issues, and reliance on manual effort. These constraints have driven interest in AI-based approaches to automated vulnerability detection and secure code generation. While Large Language Models (LLMs) have opened new avenues for classification tasks, their complexity and opacity pose challenges for interpretability and deployment. Sparse Autoencoder offer a promising solution to this problem. We explore whether SAEs can serve as a lightweight, interpretable alternative for bug detection in Java functions. We evaluate the effectiveness of SAEs when applied to representations from GPT-2 Small and Gemma 2B, examining their capacity to highlight buggy behaviour without fine-tuning the underlying LLMs. We found that SAE-derived features enable bug detection with an F1 score of up to 89%, consistently outperforming fine-tuned transformer encoder baselines. Our work provides the first empirical evidence that SAEs can be used to detect software bugs directly from the internal representations of pretrained LLMs, without any fine-tuning or task-specific supervision.

[Arxiv](https://arxiv.org/abs/2505.10375)