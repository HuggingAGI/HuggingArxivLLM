# 迈向通用人工智能还是个性化智能？——个性化联邦智能基础模型研究综述

发布时间：2025年05月11日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）与联邦学习（FL）相结合，以实现个性化、高效且隐私保护的部署。它讨论了LLMs在实际应用中的挑战和解决方案，特别是针对个性化需求的应用场景，因此归类为LLM应用。` `物联网` `边缘计算`

> Towards Artificial General or Personalized Intelligence? A Survey on Foundation Models for Personalized Federated Intelligence

# 摘要

> 大型语言模型（LLMs）的崛起，如ChatGPT、DeepSeek和Grok-3，重塑了人工智能领域的格局。作为基础模型（FMs）的杰出代表，这些模型在生成类人内容方面表现出色，使我们更接近实现人工通用智能（AGI）。然而，它们的大规模特性、对隐私问题的敏感性和巨大的计算需求，给终端用户的个性化定制带来了重大挑战。为了解决这一问题，本文提出了人工个性化智能（API）的愿景，专注于将这些强大的模型适应用户的具体需求和偏好，同时保持隐私和效率。具体而言，本文提出了个性化联邦智能（PFI），将联邦学习（FL）的隐私保护优势与基础模型（FMs）的零样本泛化能力相结合，实现了在边缘设备上的个性化、高效且隐私保护的部署。我们首先回顾了联邦学习和基础模型的最新进展，并讨论了利用FMs增强联邦系统的潜力。然后，我们阐述了实现PFI的关键动机，并探索了该领域有前景的机会，包括高效PFI、可信PFI以及基于检索增强生成（RAG）的PFI。最后，我们概述了在边缘部署FM驱动的FL系统时，实现个性化、计算效率和隐私保证的关键挑战和未来研究方向。总体而言，本调查旨在为人工个性化智能（API）的发展奠定基础，作为AGI的补充，特别关注PFI作为关键实现技术。

> The rise of large language models (LLMs), such as ChatGPT, DeepSeek, and Grok-3, has reshaped the artificial intelligence landscape. As prominent examples of foundational models (FMs) built on LLMs, these models exhibit remarkable capabilities in generating human-like content, bringing us closer to achieving artificial general intelligence (AGI). However, their large-scale nature, sensitivity to privacy concerns, and substantial computational demands present significant challenges to personalized customization for end users. To bridge this gap, this paper presents the vision of artificial personalized intelligence (API), focusing on adapting these powerful models to meet the specific needs and preferences of users while maintaining privacy and efficiency. Specifically, this paper proposes personalized federated intelligence (PFI), which integrates the privacy-preserving advantages of federated learning (FL) with the zero-shot generalization capabilities of FMs, enabling personalized, efficient, and privacy-protective deployment at the edge. We first review recent advances in both FL and FMs, and discuss the potential of leveraging FMs to enhance federated systems. We then present the key motivations behind realizing PFI and explore promising opportunities in this space, including efficient PFI, trustworthy PFI, and PFI empowered by retrieval-augmented generation (RAG). Finally, we outline key challenges and future research directions for deploying FM-powered FL systems at the edge with improved personalization, computational efficiency, and privacy guarantees. Overall, this survey aims to lay the groundwork for the development of API as a complement to AGI, with a particular focus on PFI as a key enabling technique.

[Arxiv](https://arxiv.org/abs/2505.06907)