# 微调是否有效？重新审视非结构化数据的知识编辑

发布时间：2025年06月11日

`LLM应用

理由：这篇论文专注于改进无结构知识编辑（UKE）方法，优化微调策略，并通过实验验证其效果，属于对大型语言模型应用的优化和改进。` `数据科学`

> Is Fine-Tuning an Effective Solution? Reassessing Knowledge Editing for Unstructured Data

# 摘要

> 无结构知识编辑（UKE）是更新大型语言模型（LLMs）知识的关键技术，尤其擅长处理长文本或自由格式文本等无结构输入。尽管已有研究提出了有效方法，但两个主要问题亟待解决：UKE缺乏局部性评估，且基于微调（FT）的方法常出现异常失败。为此，我们通过扩展现有数据集，构建了UnKEBench-Loc和AKEW-Loc（CF），以系统评估模型的局部性。同时，我们深入分析了影响FT方法性能的四个关键因素，并通过实验确定了最优训练方案，为UKE任务提供了实用的训练指南。实验结果表明，最优设置下的FT-UKE方法表现惊人，超越现有最先进方法（SOTA）。在批量编辑中，其优势随规模扩大而增强，平均指标领先幅度从+6.78%提升至+10.80%。

> Unstructured Knowledge Editing (UKE) is crucial for updating the relevant knowledge of large language models (LLMs). It focuses on unstructured inputs, such as long or free-form texts, which are common forms of real-world knowledge. Although previous studies have proposed effective methods and tested them, some issues exist: (1) Lack of Locality evaluation for UKE, and (2) Abnormal failure of fine-tuning (FT) based methods for UKE. To address these issues, we first construct two datasets, UnKEBench-Loc and AKEW-Loc (CF), by extending two existing UKE datasets with locality test data from the unstructured and structured views. This enables a systematic evaluation of the Locality of post-edited models. Furthermore, we identify four factors that may affect the performance of FT-based methods. Based on these factors, we conduct experiments to determine how the well-performing FT-based methods should be trained for the UKE task, providing a training recipe for future research. Our experimental results indicate that the FT-based method with the optimal setting (FT-UKE) is surprisingly strong, outperforming the existing state-of-the-art (SOTA). In batch editing scenarios, FT-UKE shows strong performance as well, with its advantage over SOTA methods increasing as the batch size grows, expanding the average metric lead from +6.78% to +10.80%

[Arxiv](https://arxiv.org/abs/2506.09672)