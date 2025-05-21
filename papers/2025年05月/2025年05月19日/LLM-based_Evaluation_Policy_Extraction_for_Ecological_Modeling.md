# 基于大型语言模型的评估策略提取在生态建模中的应用

发布时间：2025年05月19日

`LLM应用` `环境科学` `生态学`

> LLM-based Evaluation Policy Extraction for Ecological Modeling

# 摘要

> 评估生态时间序列对于模型性能的基准测试至关重要，尤其是在预测温室气体通量、捕捉碳氮循环动态以及监测水文循环等重要应用中。传统的数值指标（如R平方、均方根误差）被广泛用于量化模型与观测生态系统变量之间的相似性，但这些指标往往难以捕捉到对生态过程至关重要的领域特定的时序特征。因此，这些方法通常需要专家进行视觉检查，这不仅耗费大量人工，也限制了其在大规模评估中的应用。为了解决这些问题，我们提出了一种结合度量学习与基于大型语言模型（LLM）的自然语言策略提取的新型框架，用于开发可解释的评估标准。该方法通过处理成对注释并实现策略优化机制，生成和综合不同的评估指标。在多个数据集上的实验结果，包括对作物总初级生产力和二氧化碳通量预测的评估，证实了所提方法在捕捉目标评估偏好方面的有效性，涵盖了合成生成和专家标注的模型对比。该框架成功弥合了数值指标与专家知识之间的鸿沟，同时提供了可解释的评估策略，满足了不同生态系统建模研究的多样化需求。

> Evaluating ecological time series is critical for benchmarking model performance in many important applications, including predicting greenhouse gas fluxes, capturing carbon-nitrogen dynamics, and monitoring hydrological cycles. Traditional numerical metrics (e.g., R-squared, root mean square error) have been widely used to quantify the similarity between modeled and observed ecosystem variables, but they often fail to capture domain-specific temporal patterns critical to ecological processes. As a result, these methods are often accompanied by expert visual inspection, which requires substantial human labor and limits the applicability to large-scale evaluation. To address these challenges, we propose a novel framework that integrates metric learning with large language model (LLM)-based natural language policy extraction to develop interpretable evaluation criteria. The proposed method processes pairwise annotations and implements a policy optimization mechanism to generate and combine different assessment metrics. The results obtained on multiple datasets for evaluating the predictions of crop gross primary production and carbon dioxide flux have confirmed the effectiveness of the proposed method in capturing target assessment preferences, including both synthetically generated and expert-annotated model comparisons. The proposed framework bridges the gap between numerical metrics and expert knowledge while providing interpretable evaluation policies that accommodate the diverse needs of different ecosystem modeling studies.

[Arxiv](https://arxiv.org/abs/2505.13794)