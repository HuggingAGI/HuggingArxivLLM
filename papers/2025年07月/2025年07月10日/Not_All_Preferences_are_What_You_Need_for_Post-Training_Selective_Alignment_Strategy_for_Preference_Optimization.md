# 并非所有偏好都适用于后训练：偏好优化的选择性对齐策略

发布时间：2025年07月10日

`LLM理论` `模型优化`

> Not All Preferences are What You Need for Post-Training: Selective Alignment Strategy for Preference Optimization

# 摘要

> 大型语言模型（LLMs）的训练后对齐至关重要，因为并非所有token对模型性能的贡献相同。本文提出了一种选择性对齐策略，优先关注偏好对中的关键token，通过比较当前策略与参考模型在token级别的对数概率差异来实现。这种方法不仅降低了计算成本，还提升了对齐的精准度。我们还发现，使用更高质量的参考模型能显著提高token选择的准确性，并增强整体优化效果。在Arena-Hard和MT-Bench等基准测试中，我们的Selective-DPO方法表现优于标准DPO和蒸馏基线方法。研究结果强调了token级别优化和参考模型选择在提升LLMs偏好对齐中的关键作用。代码已开源，地址为https://github.com/Dongzhijin/SDPO。

> Post-training alignment of large language models (LLMs) is a critical challenge, as not all tokens contribute equally to model performance. This paper introduces a selective alignment strategy that prioritizes high-impact tokens within preference pairs, leveraging token-level log-probability differences between the current policy and a reference model. By focusing on these informative tokens, our approach reduces computational overhead and enhances alignment fidelity. We further explore the role of reference model quality, demonstrating that stronger reference models significantly improve token selection accuracy and overall optimization effectiveness. Comprehensive experiments on benchmarks such as Arena-Hard and MT-Bench validate the superiority of our Selective-DPO method over standard DPO and distillation-based baselines. Our findings highlight the importance of token-level optimization and reference model selection in advancing preference alignment for LLMs. The code is available at https://github.com/Dongzhijin/SDPO.

[Arxiv](https://arxiv.org/abs/2507.07725)