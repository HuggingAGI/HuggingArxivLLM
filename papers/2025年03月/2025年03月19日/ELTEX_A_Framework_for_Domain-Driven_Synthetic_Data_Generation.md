# ELTEX：一个专为领域驱动设计的合成数据生成框架

发布时间：2025年03月19日

`LLM应用

理由：这篇论文探讨了如何在专业领域（如网络安全）中生成高质量的合成数据，以提升大型语言模型（LLMs）在这些特定任务中的性能。ELTEX框架专注于领域驱动的数据生成，通过整合显式领域指示符和动态提示，优化模型在区块链网络攻击检测等任务中的应用。这属于LLM的应用层面研究，旨在提升模型在特定领域的表现，而非理论探讨或模型本身的改进。因此，归类为LLM应用。` `网络安全` `区块链`

> ELTEX: A Framework for Domain-Driven Synthetic Data Generation

# 摘要

> 我们推出了 ELTEX（高效 LLM 令牌提取），一个领域驱动的框架，专为在专业领域生成高质量合成训练数据而设计。尽管大型语言模型（LLMs）展现了强大的通用能力，但在网络安全等专业领域，其性能仍受限于领域特定训练数据的稀缺性。ELTEX 通过系统整合显式的领域指示符提取与动态提示，在生成过程中保持关键领域知识，从而突破这一限制。我们在区块链相关的网络攻击检测场景中展示了 ELTEX 的有效性，使用不同组合的真实数据和 ELTEX 生成的数据对 Gemma-2B 进行微调。实验结果表明，ELTEX 增强的模型在标准分类指标和不确定性校准方面均达到了与 GPT-4 相当的性能，同时所需计算资源显著减少。我们发布了用于区块链网络攻击检测的精选社交媒体文本合成数据集。这项研究表明，领域驱动的合成数据生成能够有效缩小资源高效模型与更大架构在专业领域之间的性能鸿沟。

> We present ELTEX (Efficient LLM Token Extraction), a domain-driven framework for generating high-quality synthetic training data in specialized domains. While Large Language Models (LLMs) have shown impressive general capabilities, their performance in specialized domains like cybersecurity remains limited by the scarcity of domain-specific training data. ELTEX addresses this challenge by systematically integrating explicit domain indicator extraction with dynamic prompting to preserve critical domain knowledge throughout the generation process. We demonstrate ELTEX's effectiveness in the context of blockchain-related cyberattack detection, where we fine-tune Gemma-2B using various combinations of real and ELTEX-generated data. Our results show that the ELTEX-enhanced model achieves performance competitive with GPT-4 across both standard classification metrics and uncertainty calibration, while requiring significantly fewer computational resources. We release a curated synthetic dataset of social media texts for cyberattack detection in blockchain. Our work demonstrates that domain-driven synthetic data generation can effectively bridge the performance gap between resource-efficient models and larger architectures in specialized domains.

[Arxiv](https://arxiv.org/abs/2503.15055)