# 面向跨平台移动智能体的可扩展视频数据集生成方法

发布时间：2025年05月18日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）和视觉语言模型（VLMs）在开发GUI视觉代理中的应用，特别是通过引入新的数据集和自动化框架来提升模型在跨平台导航任务中的性能。虽然它涉及数据集和工具的开发，但其核心是展示LLMs在实际任务中的应用和效果提升，因此归类为LLM应用。` `移动操作系统`

> Scalable Video-to-Dataset Generation for Cross-Platform Mobile Agents

# 摘要

> 大型语言模型（LLMs）和视觉语言模型（VLMs）的最新进展引发了对开发GUI视觉代理的广泛关注。我们推出了MONDAY数据集，这是一个包含20,000个教学视频中313,000个标注帧的大型数据集，涵盖了多个平台上多样化的现实世界移动操作系统导航场景。在预训练阶段包含MONDAY数据集的模型展现出强大的跨平台泛化能力，在现有单一操作系统数据集上训练的模型基础上，平均性能提升了18.11%p，且在未见过的移动操作系统平台上表现更优。为了支持随着移动平台演进而持续扩展数据集，我们提出了一种自动化框架，该框架利用公开可用的视频内容创建全面的任务数据集，无需人工标注。我们的框架包括了基于OCR的场景检测（F1得分为95.04%）、近乎完美的UI元素检测（命中率为99.87%）以及创新的多步动作识别，从而能够从各种界面配置中提取可靠的行动序列。我们贡献了MONDAY数据集和我们的自动化采集框架，以促进未来在移动操作系统导航领域的研究。

> Recent advancements in Large Language Models (LLMs) and Vision-Language Models (VLMs) have sparked significant interest in developing GUI visual agents. We introduce MONDAY (Mobile OS Navigation Task Dataset for Agents from YouTube), a large-scale dataset of 313K annotated frames from 20K instructional videos capturing diverse real-world mobile OS navigation across multiple platforms. Models that include MONDAY in their pre-training phases demonstrate robust cross-platform generalization capabilities, consistently outperforming models trained on existing single OS datasets while achieving an average performance gain of 18.11%p on an unseen mobile OS platform. To enable continuous dataset expansion as mobile platforms evolve, we present an automated framework that leverages publicly available video content to create comprehensive task datasets without manual annotation. Our framework comprises robust OCR-based scene detection (95.04% F1score), near-perfect UI element detection (99.87% hit ratio), and novel multi-step action identification to extract reliable action sequences across diverse interface configurations. We contribute both the MONDAY dataset and our automated collection framework to facilitate future research in mobile OS navigation.

[Arxiv](https://arxiv.org/abs/2505.12632)