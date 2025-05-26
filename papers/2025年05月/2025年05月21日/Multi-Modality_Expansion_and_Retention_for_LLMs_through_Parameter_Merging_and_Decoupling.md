# 多模态扩展与保留：针对大型语言模型的参数合并与解耦方法

发布时间：2025年05月21日

`LLM理论`

> Multi-Modality Expansion and Retention for LLMs through Parameter Merging and Decoupling

# 摘要

> 使用多模态编码器在特定模态数据上对大型语言模型（LLMs）进行微调，能够扩展LLMs处理的模态范围，从而形成多模态大型语言模型（MLLMs）。然而，这一范式严重依赖资源密集型且缺乏灵活性的从头微调，使用新的多模态数据。本文提出了一种无需训练的方法MMER（多模态扩展与保留），用于有效扩展现有MLLMs的多模态能力，同时保留其原始性能。具体来说，MMER复用现有MLLMs的多模态编码器，并整合它们的LLM参数。通过比较原始和整合的LLM参数，MMER生成二进制掩码，近似分离每个模态的LLM参数。这些解耦的参数可以独立处理特定模态的输入，减少参数冲突，同时保留原始MLLMs的性能。此外，MMER还能通过类似方法缓解针对新任务微调的MLLMs的灾难性遗忘问题。大量实验表明，与基线方法相比，MMER显著提升了LLMs的多模态能力，保留了99%的原始性能，并显著缓解了灾难性遗忘问题。

> Fine-tuning Large Language Models (LLMs) with multimodal encoders on modality-specific data expands the modalities that LLMs can handle, leading to the formation of Multimodal LLMs (MLLMs). However, this paradigm heavily relies on resource-intensive and inflexible fine-tuning from scratch with new multimodal data. In this paper, we propose MMER (Multi-modality Expansion and Retention), a training-free approach that integrates existing MLLMs for effective multimodal expansion while retaining their original performance. Specifically, MMER reuses MLLMs' multimodal encoders while merging their LLM parameters. By comparing original and merged LLM parameters, MMER generates binary masks to approximately separate LLM parameters for each modality. These decoupled parameters can independently process modality-specific inputs, reducing parameter conflicts and preserving original MLLMs' fidelity. MMER can also mitigate catastrophic forgetting by applying a similar process to MLLMs fine-tuned on new tasks. Extensive experiments show significant improvements over baselines, proving that MMER effectively expands LLMs' multimodal capabilities while retaining 99% of the original performance, and also markedly mitigates catastrophic forgetting.

[Arxiv](https://arxiv.org/abs/2505.17110)