# DCR：量化分析大型语言模型评估中的数据污染情况

发布时间：2025年07月15日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在基准数据污染（BDC）方面的理论问题，提出了一个检测和量化BDC的框架。该研究属于模型评估和理论分析的范畴，因此归类为LLM理论。` `数据科学`

> DCR: Quantifying Data Contamination in LLMs Evaluation

# 摘要

> 大型语言模型（LLMs）的快速发展引发了对基准数据污染（BDC）的担忧，即模型可能无意中记住评估数据，导致性能指标虚高，影响了对真实泛化能力的评估。本文提出了一种名为数据污染风险（DCR）的轻量级、可解释框架，该框架能够从语义、信息、数据和标签四个维度检测并量化BDC。通过模糊推理系统综合污染分数，DCR生成一个统一的DCR因子，用于调整原始准确性，从而反映污染感知性能。在涵盖情感分析、虚假新闻检测和算术推理任务的9种LLM（0.5B-72B）上验证了该框架，结果显示，DCR框架能够可靠地诊断污染严重程度，并通过使用DCR因子调整准确性，使三个基准测试的平均误差与未受污染的基线相比控制在4%以内。DCR框架强调计算效率和透明度，为将污染评估整合到常规评估中提供了一个实用工具，从而促进了更公平的模型比较，并增强了LLM基准测试实践的可信度。

> The rapid advancement of large language models (LLMs) has heightened concerns about benchmark data contamination (BDC), where models inadvertently memorize evaluation data, inflating performance metrics and undermining genuine generalization assessment. This paper introduces the Data Contamination Risk (DCR) framework, a lightweight, interpretable pipeline designed to detect and quantify BDC across four granular levels: semantic, informational, data, and label. By synthesizing contamination scores via a fuzzy inference system, DCR produces a unified DCR Factor that adjusts raw accuracy to reflect contamination-aware performance. Validated on 9 LLMs (0.5B-72B) across sentiment analysis, fake news detection, and arithmetic reasoning tasks, the DCR framework reliably diagnoses contamination severity and with accuracy adjusted using the DCR Factor to within 4% average error across the three benchmarks compared to the uncontaminated baseline. Emphasizing computational efficiency and transparency, DCR provides a practical tool for integrating contamination assessment into routine evaluations, fostering fairer comparisons and enhancing the credibility of LLM benchmarking practices.

[Arxiv](https://arxiv.org/abs/2507.11405)