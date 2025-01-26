# 多模态大型语言模型的隐私保护个性化联邦提示学习

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（LLMs）在客户支持和运营中的应用，并提出了联邦提示学习（FPL）方法来解决个性化、泛化和隐私之间的平衡问题。论文的核心是应用LLMs来解决实际问题，并提出了新的方法来优化这些应用。因此，它属于LLM应用类别。` `客户支持` `隐私保护`

> Privacy-Preserving Personalized Federated Prompt Learning for Multimodal Large Language Models

# 摘要

> # 多模态大型语言模型（LLMs）通过整合文本、图像和音频等多种模态，在革新客户支持和运营方面发挥着关键作用。联邦提示学习（FPL）是一种新兴方法，它将预训练的多模态LLMs（如视觉语言模型）与联邦学习结合，旨在构建个性化且隐私保护的AI系统。然而，如何在个性化、泛化和隐私之间找到平衡仍是一个重大挑战。过度个性化可能导致过拟合，削弱泛化能力，而严格的隐私措施（如差分隐私）则可能同时阻碍个性化和泛化。本文提出了一种差分隐私联邦提示学习（DP-FPL）方法，通过低秩适应方案捕捉泛化，同时保留残差项以维持个性化的表达能力。为确保隐私，我们创新性地将局部差分隐私应用于局部提示的两个低秩组件，并将全局差分隐私应用于全局提示。该方法有效减轻了隐私噪声对模型性能的影响，并在个性化和泛化之间实现了更好的平衡。大量实验验证了该方法的优越性。

> Multimodal Large Language Models (LLMs) are pivotal in revolutionizing customer support and operations by integrating multiple modalities such as text, images, and audio. Federated Prompt Learning (FPL) is a recently proposed approach that combines pre-trained multimodal LLMs such as vision-language models with federated learning to create personalized, privacy-preserving AI systems. However, balancing the competing goals of personalization, generalization, and privacy remains a significant challenge. Over-personalization can lead to overfitting, reducing generalizability, while stringent privacy measures, such as differential privacy, can hinder both personalization and generalization. In this paper, we propose a Differentially Private Federated Prompt Learning (DP-FPL) approach to tackle this challenge by leveraging a low-rank adaptation scheme to capture generalization while maintaining a residual term that preserves expressiveness for personalization. To ensure privacy, we introduce a novel method where we apply local differential privacy to the two low-rank components of the local prompt, and global differential privacy to the global prompt. Our approach mitigates the impact of privacy noise on the model performance while balancing the tradeoff between personalization and generalization. Extensive experiments demonstrate the effectiveness of our approach over other benchmarks.

[Arxiv](https://arxiv.org/abs/2501.13904)