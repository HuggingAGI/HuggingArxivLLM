# # 增强大语言模型对提示格式变化的鲁棒性

发布时间：2025年04月09日

`LLM应用` `计算机视觉`

> Towards LLMs Robustness to Changes in Prompt Format Styles

# 摘要

> 大型语言模型（LLMs）因其强大的应用能力近年来备受关注。然而，这些模型对提示格式的非语义变化非常敏感，即使是微小的格式调整也可能导致性能大幅波动。这一现象在研究中被称为提示脆性（prompt brittleness）。尽管此前的研究主要集中在开发识别特定任务最优提示的技术上，但尚未找到一个简单有效的解决方案。我们提出了一种名为格式混合（MOF）的创新方法，通过多样化提示 few-shot 示例的风格，有效解决了 LLM 中的提示脆性问题。这一灵感源自计算机视觉领域，通过使用多样化风格的数据集来防止模型将特定风格与目标变量关联。实证研究表明，我们的方法不仅显著减少了由风格引起的提示脆性，还在不同数据集和提示变化下提升了整体性能。

> Large language models (LLMs) have gained popularity in recent years for their utility in various applications. However, they are sensitive to non-semantic changes in prompt formats, where small changes in the prompt format can lead to significant performance fluctuations. In the literature, this problem is commonly referred to as prompt brittleness. Previous research on prompt engineering has focused mainly on developing techniques for identifying the optimal prompt for specific tasks. Some studies have also explored the issue of prompt brittleness and proposed methods to quantify performance variations; however, no simple solution has been found to address this challenge. We propose Mixture of Formats (MOF), a simple and efficient technique for addressing prompt brittleness in LLMs by diversifying the styles used in the prompt few-shot examples. MOF was inspired by computer vision techniques that utilize diverse style datasets to prevent models from associating specific styles with the target variable. Empirical results show that our proposed technique reduces style-induced prompt brittleness in various LLMs while also enhancing overall performance across prompt variations and different datasets.

[Arxiv](https://arxiv.org/abs/2504.06969)