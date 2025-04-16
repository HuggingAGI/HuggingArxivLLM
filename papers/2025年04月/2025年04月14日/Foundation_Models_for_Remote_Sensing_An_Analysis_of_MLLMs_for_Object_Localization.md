# # 基础模型在遥感中的应用：多模态基础模型在目标定位中的分析

发布时间：2025年04月14日

`LLM应用` `地球观测` `计算机视觉`

> Foundation Models for Remote Sensing: An Analysis of MLLMs for Object Localization

# 摘要

> 多模态大型语言模型（MLLMs）彻底改变了计算机视觉领域，在零样本设置下尤其表现出色。然而，这些模型的强大性能并不总能迁移到地球观测（EO）图像等分布外领域。虽然MLLMs在图像描述生成和场景理解等EO任务中表现出色，但在需要精细空间推理的任务（如物体定位）中却表现欠佳。然而，MLLMs发展迅猛，相关见解迅速过时。本研究聚焦于近期专门训练以具备精细空间推理能力的MLLMs，通过在EO物体定位任务上的基准测试，证明这些模型在某些场景下表现出色，尤其适合零样本设置。此外，我们深入探讨了提示选择、地面采样距离（GSD）优化以及失败案例分析。我们希望这项研究能为评估MLLM是否适合特定EO定位任务以及如何优化提供有价值的参考。

> Multimodal large language models (MLLMs) have altered the landscape of computer vision, obtaining impressive results across a wide range of tasks, especially in zero-shot settings. Unfortunately, their strong performance does not always transfer to out-of-distribution domains, such as earth observation (EO) imagery. Prior work has demonstrated that MLLMs excel at some EO tasks, such as image captioning and scene understanding, while failing at tasks that require more fine-grained spatial reasoning, such as object localization. However, MLLMs are advancing rapidly and insights quickly become out-dated. In this work, we analyze more recent MLLMs that have been explicitly trained to include fine-grained spatial reasoning capabilities, benchmarking them on EO object localization tasks. We demonstrate that these models are performant in certain settings, making them well suited for zero-shot scenarios. Additionally, we provide a detailed discussion focused on prompt selection, ground sample distance (GSD) optimization, and analyzing failure cases. We hope that this work will prove valuable as others evaluate whether an MLLM is well suited for a given EO localization task and how to optimize it.

[Arxiv](https://arxiv.org/abs/2504.10727)