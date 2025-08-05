# DBAIOps：基于知识图谱的推理增强型大语言模型数据库运维系统

发布时间：2025年08月01日

`LLM应用` `数据库`

> DBAIOps: A Reasoning LLM-Enhanced Database Operation and Maintenance System using Knowledge Graphs

# 摘要

> 数据库系统的运维（O&M）对保障系统可用性和性能至关重要，通常需要专家经验（如识别指标与异常的关系）来进行有效诊断和恢复。然而，现有的自动数据库运维方法，包括商业产品，都无法有效利用专家经验。一方面，基于规则的方法仅支持基本运维任务（如基于指标的异常检测），这些方法多为数值方程，无法有效结合字面运维经验（如手册中的故障排除指南）。另一方面，基于LLM的方法通过检索零散信息（如标准文档 + RAG）生成结果，但往往不准确或过于通用。为解决这些问题，我们提出了DBAIOps，这是一种结合推理LLMs与知识图谱的新型混合数据库运维系统，实现类似DBA的诊断。首先，DBAIOps引入异构图模型来表示诊断经验，并提出半自动图构建算法，从数千份文档中构建该图。其次，DBAIOps开发了800多个可重用的异常模型，能够识别直接告警的指标以及隐含相关的经验与指标。第三，针对每个异常，DBAIOps提出两阶段图演化机制，用于探索相关诊断路径并自动识别缺失关系。然后，DBAIOps利用推理LLM（如DeepSeek-R1）推断根本原因，并为DBA和普通用户生成清晰的诊断报告。我们在Oracle、MySQL、PostgreSQL和DM8四种主流数据库系统上的评估表明，DBAIOps优于现有基线，在根本原因和人工评估准确性方面分别提高了34.85%和47.22%。

> The operation and maintenance (O&M) of database systems is critical to ensuring system availability and performance, typically requiring expert experience (e.g., identifying metric-to-anomaly relations) for effective diagnosis and recovery. However, existing automatic database O&M methods, including commercial products, cannot effectively utilize expert experience. On the one hand, rule-based methods only support basic O&M tasks (e.g., metric-based anomaly detection), which are mostly numerical equations and cannot effectively incorporate literal O&M experience (e.g., troubleshooting guidance in manuals). On the other hand, LLM-based methods, which retrieve fragmented information (e.g., standard documents + RAG), often generate inaccurate or generic results. To address these limitations, we present DBAIOps, a novel hybrid database O&M system that combines reasoning LLMs with knowledge graphs to achieve DBA-style diagnosis. First, DBAIOps introduces a heterogeneous graph model for representing the diagnosis experience, and proposes a semi-automatic graph construction algorithm to build that graph from thousands of documents. Second, DBAIOps develops a collection of (800+) reusable anomaly models that identify both directly alerted metrics and implicitly correlated experience and metrics. Third, for each anomaly, DBAIOps proposes a two-stage graph evolution mechanism to explore relevant diagnosis paths and identify missing relations automatically. It then leverages a reasoning LLM (e.g., DeepSeek-R1) to infer root causes and generate clear diagnosis reports for both DBAs and common users. Our evaluation over four mainstream database systems (Oracle, MySQL, PostgreSQL, and DM8) demonstrates that DBAIOps outperforms state-of-the-art baselines, 34.85% and 47.22% higher in root cause and human evaluation accuracy, respectively.

[Arxiv](https://arxiv.org/abs/2508.01136)