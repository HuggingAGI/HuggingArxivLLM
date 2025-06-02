# USB: 多模态大型语言模型的全面统一安全评估基准

发布时间：2025年05月26日

`其他` `多模态`

> USB: A Comprehensive and Unified Safety Evaluation Benchmark for Multimodal Large Language Models

# 摘要

> 尽管多模态大型语言模型（MLLMs）取得了显著成就并被广泛应用，但它们暴露了严重的安全漏洞，亟需建立健壮的安全评估基准。然而，现有MLLM安全基准在数据质量、覆盖范围和模态风险组合方面存在明显不足，导致评估结果虚高且矛盾，严重阻碍了安全问题的发现和治理。此外，我们认为在MLLM安全评估中应同时考虑对有害查询的漏洞和对无害查询的过度敏感性，而此前这些问题往往是分开考虑的。

本文中，我们引入了统一安全基准（USB），这是MLLM安全领域中最全面的评估基准之一。我们的基准具有以下特点：
- 高质量的查询
- 广泛的风险类别
- 全面的模态组合
- 同时涵盖漏洞和过度敏感性评估

从风险类别和模态组合两个关键维度来看，现有基准——甚至将其中绝大多数结合起来——都远未真正全面。为弥补这一差距，我们设计了一个复杂的数据合成管道，生成广泛、高质量的补充数据，涵盖此前未探索的方面。通过将开源数据集与我们的合成数据相结合，我们的基准为61个风险子类中的每一个提供了4种不同的模态组合，涵盖漏洞和过度敏感性两个维度的中英文内容。

> Despite their remarkable achievements and widespread adoption, Multimodal Large Language Models (MLLMs) have revealed significant security vulnerabilities, highlighting the urgent need for robust safety evaluation benchmarks. Existing MLLM safety benchmarks, however, fall short in terms of data quality and coverge, and modal risk combinations, resulting in inflated and contradictory evaluation results, which hinders the discovery and governance of security concerns. Besides, we argue that vulnerabilities to harmful queries and oversensitivity to harmless ones should be considered simultaneously in MLLMs safety evaluation, whereas these were previously considered separately. In this paper, to address these shortcomings, we introduce Unified Safety Benchmarks (USB), which is one of the most comprehensive evaluation benchmarks in MLLM safety. Our benchmark features high-quality queries, extensive risk categories, comprehensive modal combinations, and encompasses both vulnerability and oversensitivity evaluations. From the perspective of two key dimensions: risk categories and modality combinations, we demonstrate that the available benchmarks -- even the union of the vast majority of them -- are far from being truly comprehensive. To bridge this gap, we design a sophisticated data synthesis pipeline that generates extensive, high-quality complementary data addressing previously unexplored aspects. By combining open-source datasets with our synthetic data, our benchmark provides 4 distinct modality combinations for each of the 61 risk sub-categories, covering both English and Chinese across both vulnerability and oversensitivity dimensions.

[Arxiv](https://arxiv.org/abs/2505.23793)