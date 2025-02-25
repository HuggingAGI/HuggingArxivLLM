# MemeIntel：可解释的宣传性与仇恨性表情包检测

发布时间：2025年02月23日

`LLM应用

理由：这篇论文主要探讨了视觉语言模型（VLM）在检测社交媒体上的多模态内容（如虚假信息、仇恨言论和宣传）中的应用。虽然它涉及到多模态内容和数据集的构建，但其核心是利用LLM（作为VLM的一部分）来解决实际问题，因此归类为LLM应用。` `社交媒体` `多模态`

> MemeIntel: Explainable Detection of Propagandistic and Hateful Memes

# 摘要

> 社交媒体上多模态内容的泛滥给监管虚假信息、仇恨言论和宣传等复杂且依赖语境的问题带来了巨大挑战。尽管在自动检测方面已经付出了努力，但标签检测和为预测标签生成基于解释的理由却鲜有关注。为了解决这一挑战，我们推出了MemeIntel，这是一个增强解释的阿拉伯语宣传模因和英语仇恨模因数据集，成为首个针对这些任务的大规模资源。为了解决这些任务，我们提出了一种多阶段优化方法，并训练了视觉语言模型（VLM）。实验结果显示，该方法在	extbf{标签检测}和解释生成方面显著优于基线模型，在ArMeme上绝对提升了约3%，在Hateful Memes上绝对提升了约7%，超越了当前最先进的方法。为了促进可重复研究和未来发展，我们计划公开发布MemeIntel数据集和实验资源。

> The proliferation of multimodal content on social media presents significant challenges in understanding and moderating complex, context-dependent issues such as misinformation, hate speech, and propaganda. While efforts have been made to develop resources and propose new methods for automatic detection, limited attention has been given to label detection and the generation of explanation-based rationales for predicted labels. To address this challenge, we introduce MemeIntel, an explanation-enhanced dataset for propaganda memes in Arabic and hateful memes in English, making it the first large-scale resource for these tasks. To solve these tasks, we propose a multi-stage optimization approach and train Vision-Language Models (VLMs). Our results demonstrate that this approach significantly improves performance over the base model for both \textbf{label detection} and explanation generation, outperforming the current state-of-the-art with an absolute improvement of ~3% on ArMeme and ~7% on Hateful Memes. For reproducibility and future research, we aim to make the MemeIntel dataset and experimental resources publicly available.

[Arxiv](https://arxiv.org/abs/2502.16612)