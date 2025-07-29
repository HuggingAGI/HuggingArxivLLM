# 潜在用户差异建模，实现LLM个性化

发布时间：2025年07月28日

`LLM应用

理由：这篇论文主要探讨了如何在大型语言模型（LLMs）中实现个性化输出，提出了一种新的框架DEP，用于建模用户差异并生成个性化的评论。这属于LLMs的应用层面，因为它专注于如何将LLMs应用于特定任务，而不是LLMs的理论发展或其他领域。` `个性化推荐`

> Latent Inter-User Difference Modeling for LLM Personalization

# 摘要

> 大型语言模型（LLMs）正逐步融入日常生活，人们对个性化输出的需求也随之激增。传统方法多依赖用户历史记录，却忽视了用户间的个性化差异。尽管近期研究开始关注这些差异，但基于语言提示的方法往往难以有效提取关键区别。为此，我们提出了一种名为DEP（基于差异感知嵌入的个性化框架）的新方法，它通过潜在空间建模用户差异，而非传统语言提示。DEP通过对比用户与兴趣相近的同侪嵌入，提取相对行为信号，构建软提示。随后，稀疏自动编码器对用户特征与差异感知嵌入进行筛选和压缩，仅保留任务相关特征后再注入冻结的LLM中。实验结果显示，DEP在个性化评论生成任务中全面超越现有方法。我们的代码已开源，地址为https://github.com/SnowCharmQ/DEP。

> Large language models (LLMs) are increasingly integrated into users' daily lives, leading to a growing demand for personalized outputs. Previous work focuses on leveraging a user's own history, overlooking inter-user differences that are crucial for effective personalization. While recent work has attempted to model such differences, the reliance on language-based prompts often hampers the effective extraction of meaningful distinctions. To address these issues, we propose Difference-aware Embedding-based Personalization (DEP), a framework that models inter-user differences in the latent space instead of relying on language prompts. DEP constructs soft prompts by contrasting a user's embedding with those of peers who engaged with similar content, highlighting relative behavioral signals. A sparse autoencoder then filters and compresses both user-specific and difference-aware embeddings, preserving only task-relevant features before injecting them into a frozen LLM. Experiments on personalized review generation show that DEP consistently outperforms baseline methods across multiple metrics. Our code is available at https://github.com/SnowCharmQ/DEP.

[Arxiv](https://arxiv.org/abs/2507.20849)