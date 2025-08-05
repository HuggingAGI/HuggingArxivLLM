# CloudAnoAgent：基于LLM代理的云站点异常检测系统（采用神经符号机制）

发布时间：2025年08月03日

`LLM应用` `异常检测`

> CloudAnoAgent: Anomaly Detection for Cloud Sites via LLM Agent with Neuro-Symbolic Mechanism

# 摘要

> 云站点异常检测仍是关键且具挑战性的任务。现有仅依赖指标数据的方法常因数据不平衡而产生高假阳性率（FPR），给运维工程师带来显著负担。大型语言模型（LLMs）的最新进展为整合指标与日志数据提供了新机遇，从而实现更精准且可解释的异常检测。本文中，我们提出了CloudAnoAgent，首个基于神经符号LLM的云环境异常检测代理。CloudAnoAgent在一个统一的处理管道中同时处理结构化指标和文本日志数据，利用符号验证来验证检测假设并生成结构化的异常报告。为支持系统性评估，我们引入了CloudAnoBench，首个提供LLM生成的配对指标与日志数据的基准，数据带有细粒度的异常行为标注，填补了现有数据集的关键空白。实验结果表明，与传统基线和仅使用LLM的基线相比，CloudAnoAgent在异常分类准确率上平均提升了46.36%和36.67%，并将FPR平均降低了36.67%和33.89%。与普通LLM提示相比，CloudAnoAgent在异常类型检测准确率上提升了12.8%。这些结果展示了我们的方法在提升检测精度、降低假阳性率和增强可解释性方面的优势，从而支持其在企业云环境中的实际部署。

> Anomaly detection in cloud sites remains a critical yet challenging task. Existing approaches that rely solely on metric data often suffer from high false positive rates (FPR) due to data imbalance between normal and anomalous events, leading to significant operational overhead for system reliance engineers. Recent advances in large language models (LLMs) offer new opportunities for integrating metrics with log data, enabling more accurate and interpretable anomaly detection. In this paper, we propose CloudAnoAgent, the first neuro-symbolic LLM-based agent for anomaly detection in cloud environments. CloudAnoAgent jointly processes structured metrics and textual log data in a unified pipeline, leveraging symbolic verification to validate detection hypotheses and generate structured anomaly reports. To support systematic evaluation, we introduce CloudAnoBench, the first benchmark that provides LLM-generated paired metrics and log data with fine-grained anomaly behavior annotations, filling a critical gap in existing datasets. Experimental results demonstrate that CloudAnoAgent improves anomaly classification accuracy by 46.36% and 36.67% on average and reduces the FPR by 36.67% and 33.89% on average over traditional baselines and LLM-only baseline, with a boost on anomaly type detection accuracy by 12.8% compared to vanilla LLM prompting. These results demonstrate the strengths of our approach in improving detection accuracy, reducing false positives, and enhancing interpretability, thereby supporting practical deployment in enterprise cloud environments.

[Arxiv](https://arxiv.org/abs/2508.01844)