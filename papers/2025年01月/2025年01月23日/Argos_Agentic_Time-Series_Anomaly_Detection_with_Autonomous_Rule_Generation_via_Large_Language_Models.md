# Argos: 利用大型语言模型实现自主规则生成的智能时间序列异常检测

发布时间：2025年01月23日

`Agent

理由：这篇论文介绍了一个名为Argos的智能体系统，该系统利用大型语言模型（LLMs）来检测云基础设施时间序列中的异常。Argos通过多个协作代理生成和部署异常规则，强调了系统的自主性、可解释性和可重复性。因此，这篇论文主要关注的是智能体（Agent）的设计和应用，而不是纯粹的LLM理论、RAG（Retrieval-Augmented Generation）或LLM应用。` `云计算` `异常检测`

> Argos: Agentic Time-Series Anomaly Detection with Autonomous Rule Generation via Large Language Models

# 摘要

> # 摘要
云基础设施的可观测性对服务提供商至关重要，推动了异常检测系统在监控指标中的广泛应用。然而，现有系统往往难以同时实现可解释性、可重复性和自主性，这三个特性是生产环境中不可或缺的。我们推出了Argos，一个利用大型语言模型（LLMs）检测云基础设施时间序列异常的智能体系统。Argos采用可解释和可重复的异常规则作为中间表示，并利用LLMs自主生成这些规则。该系统通过多个协作代理高效训练无错误且精度有保障的异常规则，并部署这些规则以进行低成本的在线异常检测。评估结果显示，Argos在公共异常检测数据集和微软内部数据集上分别将$F_1$分数提高了$9.5\%$和$28.3\%$，表现优于现有最先进的方法。

> Observability in cloud infrastructure is critical for service providers, driving the widespread adoption of anomaly detection systems for monitoring metrics. However, existing systems often struggle to simultaneously achieve explainability, reproducibility, and autonomy, which are three indispensable properties for production use. We introduce Argos, an agentic system for detecting time-series anomalies in cloud infrastructure by leveraging large language models (LLMs). Argos proposes to use explainable and reproducible anomaly rules as intermediate representation and employs LLMs to autonomously generate such rules. The system will efficiently train error-free and accuracy-guaranteed anomaly rules through multiple collaborative agents and deploy the trained rules for low-cost online anomaly detection. Through evaluation results, we demonstrate that Argos outperforms state-of-the-art methods, increasing $F_1$ scores by up to $9.5\%$ and $28.3\%$ on public anomaly detection datasets and an internal dataset collected from Microsoft, respectively.

[Arxiv](https://arxiv.org/abs/2501.14170)