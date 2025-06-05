# 基于特权结构化信息的多模态表格推理

发布时间：2025年06月04日

`LLM应用` `数据分析`

> Multimodal Tabular Reasoning with Privileged Structured Information

# 摘要

> 表格推理涉及多步骤信息提取和逻辑推理，处理结构化的表格数据。尽管 recent advances have leveraged large language models (LLMs) for reasoning over structured tables，但在实际应用中，高质量的文本表示往往不可用，因为表格通常以图像形式出现。本文针对表格图像进行推理任务，利用训练过程中可获得的结构化信息，增强多模态大型语言模型（MLLMs）。主要挑战在于准确对齐结构化信息与视觉表示的复杂性，以及在输入模态差距下有效迁移结构化推理技能。为解决这些问题，我们提出了TabUlar Reasoning with Bridged infOrmation ({\sc Turbo})，一个结合特权结构化表的多模态表格推理新框架。{\sc Turbo} 基于DeepSeek-R1构建了一个结构感知推理轨迹生成器，有助于高质量的模态桥接数据。在此基础上，{\sc Turbo} 反复生成并选择有利的推理路径，进一步提升模型的表格推理能力。实验结果显示，仅使用有限的（9k）数据，{\sc Turbo} 在多个数据集上达到了最先进的性能（较前SOTA提升+7.2%）。

> Tabular reasoning involves multi-step information extraction and logical inference over tabular data. While recent advances have leveraged large language models (LLMs) for reasoning over structured tables, such high-quality textual representations are often unavailable in real-world settings, where tables typically appear as images. In this paper, we tackle the task of tabular reasoning from table images, leveraging privileged structured information available during training to enhance multimodal large language models (MLLMs). The key challenges lie in the complexity of accurately aligning structured information with visual representations, and in effectively transferring structured reasoning skills to MLLMs despite the input modality gap. To address these, we introduce TabUlar Reasoning with Bridged infOrmation ({\sc Turbo}), a new framework for multimodal tabular reasoning with privileged structured tables. {\sc Turbo} benefits from a structure-aware reasoning trace generator based on DeepSeek-R1, contributing to high-quality modality-bridged data. On this basis, {\sc Turbo} repeatedly generates and selects the advantageous reasoning paths, further enhancing the model's tabular reasoning ability. Experimental results demonstrate that, with limited ($9$k) data, {\sc Turbo} achieves state-of-the-art performance ($+7.2\%$ vs. previous SOTA) across multiple datasets.

[Arxiv](https://arxiv.org/abs/2506.04088)