# LLM4FS：借助大语言模型实现特征选择，并探讨改进之道

发布时间：2025年03月31日

`LLM应用`

> LLM4FS: Leveraging Large Language Models for Feature Selection and How to Improve It

# 摘要

> 大型语言模型（LLMs）的最新进展为决策领域开辟了新天地，尤其是在自动化特征选择方面。本文首先全面评估了基于LLMs的特征选择方法，包括前沿的DeepSeek-R1、GPT-o3-mini和GPT-4.5模型。随后，我们提出了一种名为LLM4FS的创新混合策略，巧妙结合了LLMs与传统数据驱动方法。具体而言，该策略将输入数据样本输入LLMs，随后直接调用随机森林和逐步向前选择等传统数据驱动技术。值得注意的是，我们的分析表明，这种混合策略能够充分发挥LLMs的上下文理解能力和传统数据驱动方法的高统计可靠性，从而实现卓越的特征选择性能，甚至超越了LLMs和传统数据驱动方法的表现。最后，我们探讨了其在决策中的应用局限性。

> Recent advances in large language models (LLMs) have provided new opportunities for decision-making, particularly in the task of automated feature selection. In this paper, we first comprehensively evaluate LLM-based feature selection methods, covering the state-of-the-art DeepSeek-R1, GPT-o3-mini, and GPT-4.5. Then, we propose a novel hybrid strategy called LLM4FS that integrates LLMs with traditional data-driven methods. Specifically, input data samples into LLMs, and directly call traditional data-driven techniques such as random forest and forward sequential selection. Notably, our analysis reveals that the hybrid strategy leverages the contextual understanding of LLMs and the high statistical reliability of traditional data-driven methods to achieve excellent feature selection performance, even surpassing LLMs and traditional data-driven methods. Finally, we point out the limitations of its application in decision-making.

[Arxiv](https://arxiv.org/abs/2503.24157)