# 基于LLM的评估策略提取，应用于生态建模

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于生态时间序列数据的评估，特别是在模型性能评估方面。论文提出了一种结合度量学习和LLM的自然语言策略提取的新框架，用于生成更可解释的评估指标。这表明LLM被用作工具来解决特定领域的问题，属于LLM的应用领域。` `环境科学` `生态系统建模`

> LLM-based Evaluation Policy Extraction for Ecological Modeling

# 摘要

> 生态时间序列的评估在温室气体通量预测、碳氮循环捕捉及水文循环监测等关键应用中对模型性能评估至关重要。尽管传统的数值指标（如R平方、均方根误差）被广泛用于衡量模型与观测数据的相似性，但它们往往难以捕捉生态过程中的关键时间模式。因此，这些方法通常需要专家人工检查，这不仅耗时费力，也限制了其在大规模评估中的应用。为解决这些问题，我们提出了一种结合度量学习与基于大型语言模型（LLM）的自然语言策略提取的新框架，旨在开发更可解释的评估标准。该方法通过处理成对标注数据并优化策略生成机制，能够自动生成和组合多种评估指标。实验结果表明，在作物总初级生产量和二氧化碳通量预测的多个数据集上，该方法能够有效捕捉目标评估偏好，无论数据是人工合成还是专家标注。这一框架不仅弥合了传统数值指标与专家知识之间的鸿沟，还提供了灵活多样的可解释评估策略，充分满足了不同生态系统建模研究的需求。

> Evaluating ecological time series is critical for benchmarking model performance in many important applications, including predicting greenhouse gas fluxes, capturing carbon-nitrogen dynamics, and monitoring hydrological cycles. Traditional numerical metrics (e.g., R-squared, root mean square error) have been widely used to quantify the similarity between modeled and observed ecosystem variables, but they often fail to capture domain-specific temporal patterns critical to ecological processes. As a result, these methods are often accompanied by expert visual inspection, which requires substantial human labor and limits the applicability to large-scale evaluation. To address these challenges, we propose a novel framework that integrates metric learning with large language model (LLM)-based natural language policy extraction to develop interpretable evaluation criteria. The proposed method processes pairwise annotations and implements a policy optimization mechanism to generate and combine different assessment metrics. The results obtained on multiple datasets for evaluating the predictions of crop gross primary production and carbon dioxide flux have confirmed the effectiveness of the proposed method in capturing target assessment preferences, including both synthetically generated and expert-annotated model comparisons. The proposed framework bridges the gap between numerical metrics and expert knowledge while providing interpretable evaluation policies that accommodate the diverse needs of different ecosystem modeling studies.

[Arxiv](https://arxiv.org/abs/2505.13794)