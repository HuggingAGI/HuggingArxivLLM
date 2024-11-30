# 探究大型语言模型在罕见遗传病诊断中对基于表型指导基因优先级排序的实际应用价值进一步优化后：在罕见遗传疾病诊断过程中，本研究旨在评估大型语言模型在基于表型驱动基因优先级排序中的实用性和有效性。

发布时间：2024年03月21日

`LLM应用` `遗传学` `人工智能`

> Assessing the Utility of Large Language Models for Phenotype-Driven Gene Prioritization in Rare Genetic Disorder Diagnosis

# 摘要

> 在罕见遗传疾病的诊断过程中，根据观察到的表型进行基因优先排序至关重要。虽然过去的方法倚重于精心构建的表型-基因知识图谱，但近期大型语言模型技术的发展通过在丰富语料库上的深度学习，打开了借助 AI 进行预测的新窗口。本次研究深入对比了五种大型语言模型（包括两种 GPT 系列和三种 Llama2 系列），从任务完整性、基因预测精确度及遵循输出结构规范等三大指标对其性能进行全面评估。通过一系列多元化的实验，探究了模型组合、提示方式、输入类型和任务难度级别等因素的影响。结果显示，即便是表现出色的 GPT-4 模型，其预测精度也仅为 16.0%，仍落后于常规生物信息学工具。然而，模型参数越大，预测准确性和任务完成度均呈现提升趋势。有趣的是，对于规模小于 GPT-4 的模型，复杂提示虽能增强任务完整性，却可能导致结构合规性下降；而在 GPT-4 上并未观察到此类提示效应。此外，尽管 LLN 使用自由文本输入时的预测精度虽稍逊于 HPO 术语输入，但仍优于随机预测水平。偏见分析揭示了一些基因（例如 MECP2、CDKL5 和 SCN1A）更易名列前茅，这或许能解释在不同数据集中出现变异性现象的原因。此项研究深化了对 LLM 在基因组分析应用的理解，为探索如何将高级 LLM 引入临床工作流程提供了有价值的参考。

> Phenotype-driven gene prioritization is a critical process in the diagnosis of rare genetic disorders for identifying and ranking potential disease-causing genes based on observed physical traits or phenotypes. While traditional approaches rely on curated knowledge graphs with phenotype-gene relations, recent advancements in large language models have opened doors to the potential of AI predictions through extensive training on diverse corpora and complex models. This study conducted a comprehensive evaluation of five large language models, including two Generative Pre-trained Transformers series, and three Llama2 series, assessing their performance across three key metrics: task completeness, gene prediction accuracy, and adherence to required output structures. Various experiments explored combinations of models, prompts, input types, and task difficulty levels. Our findings reveal that even the best-performing LLM, GPT-4, achieved an accuracy of 16.0%, which still lags behind traditional bioinformatics tools. Prediction accuracy increased with the parameter/model size. A similar increasing trend was observed for the task completion rate, with complicated prompts more likely to increase task completeness in models smaller than GPT-4. However, complicated prompts are more likely to decrease the structure compliance rate, but no prompt effects on GPT-4. Compared to HPO term-based input, LLM was also able to achieve better than random prediction accuracy by taking free-text input, but slightly lower than with the HPO input. Bias analysis showed that certain genes, such as MECP2, CDKL5, and SCN1A, are more likely to be top-ranked, potentially explaining the variances observed across different datasets. This study provides valuable insights into the integration of LLMs within genomic analysis, contributing to the ongoing discussion on the utilization of advanced LLMs in clinical workflows.

[Arxiv](https://arxiv.org/abs/2403.14801)