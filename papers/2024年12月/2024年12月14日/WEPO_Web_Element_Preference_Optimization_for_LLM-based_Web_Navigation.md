# WEPO: 基于LLM的网页导航中的网页元素偏好优化

发布时间：2024年12月14日

`Agent

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）作为智能体（Agent）来进行自主网页导航，并提出了一种新的方法——网页元素偏好优化（WEPO）。该方法通过优化智能体的行为来更好地对齐用户意图与输出动作，属于智能体（Agent）在具体任务中的应用。因此，分类为Agent。` `网页导航` `人工智能`

> WEPO: Web Element Preference Optimization for LLM-based Web Navigation

# 摘要

> 自主网页导航的飞速发展得益于将预训练的大型语言模型（LLMs）作为智能体的基础。然而，现有研究尚未充分利用HTML元素的冗余性进行对比训练。本文提出了一种基于LLM的网页导航新方法——网页元素偏好优化（WEPO）。WEPO通过采样基于距离的非显著网页元素作为负样本，采用无监督偏好学习，在直接偏好优化（DPO）框架内优化最大似然目标。我们在Mind2Web基准上评估了WEPO，实验表明WEPO能更有效地将用户的高级意图与输出动作对齐。结果显示，我们的方法达到了最先进的水平，比WebAgent提升了13.8%，比视觉语言模型CogAgent基线提升了5.3%。这一发现凸显了偏好优化在增强网页导航及其他网页任务中的潜力，为未来研究指明了方向。

> The rapid advancement of autonomous web navigation has significantly benefited from grounding pretrained Large Language Models (LLMs) as agents. However, current research has yet to fully leverage the redundancy of HTML elements for contrastive training. This paper introduces a novel approach to LLM-based web navigation tasks, called Web Element Preference Optimization (WEPO). WEPO utilizes unsupervised preference learning by sampling distance-based non-salient web elements as negative samples, optimizing maximum likelihood objective within Direct Preference Optimization (DPO). We evaluate WEPO on the Mind2Web benchmark and empirically demonstrate that WEPO aligns user high-level intent with output actions more effectively. The results show that our method achieved the state-of-the-art, with an improvement of 13.8% over WebAgent and 5.3% over the visual language model CogAgent baseline. Our findings underscore the potential of preference optimization to enhance web navigation and other web page based tasks, suggesting a promising direction for future research.

[Arxiv](https://arxiv.org/abs/2412.10742)