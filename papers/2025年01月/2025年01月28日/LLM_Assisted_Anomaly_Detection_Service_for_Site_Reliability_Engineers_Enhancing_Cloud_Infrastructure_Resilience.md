# LLM 辅助的异常检测服务：提升云基础设施弹性的站点可靠性工程师利器

发布时间：2025年01月28日

`LLM应用

**理由**：该论文主要介绍了如何利用大型语言模型（LLMs）来理解和建模云基础设施中的异常行为，并开发了一套异常检测服务。虽然论文涉及了时间序列数据的异常检测，但其核心创新点在于利用LLMs来增强对复杂系统的理解，并将其应用于实际工业场景中。因此，该论文应归类为LLM应用。` `云计算` `物联网`

> LLM Assisted Anomaly Detection Service for Site Reliability Engineers: Enhancing Cloud Infrastructure Resilience

# 摘要

> 本文介绍了一种可扩展的异常检测服务，专为工业时间序列数据设计，旨在帮助站点可靠性工程师（SREs）管理云基础设施。该服务能够在复杂数据流中高效检测异常，支持主动识别和解决问题。此外，本文还提出了一种创新的云基础设施异常建模方法，利用大型语言模型（LLMs）理解关键组件、故障模式和行为。我们提供了一套用于检测单变量和多变量时间序列数据中异常的算法，包括基于回归、混合模型和半监督的方法。我们提供了该服务的使用模式洞察，一年内有超过500名用户和20万次API调用。该服务已成功应用于各种工业环境，包括基于物联网的AI应用。我们还在公共异常基准上评估了系统，展示了其有效性。通过该系统，SREs可以在问题升级前主动识别潜在问题，减少停机时间并提高事件响应时间，最终提升客户体验。我们计划扩展系统，引入时间序列基础模型，实现零-shot异常检测能力。

> This paper introduces a scalable Anomaly Detection Service with a generalizable API tailored for industrial time-series data, designed to assist Site Reliability Engineers (SREs) in managing cloud infrastructure. The service enables efficient anomaly detection in complex data streams, supporting proactive identification and resolution of issues. Furthermore, it presents an innovative approach to anomaly modeling in cloud infrastructure by utilizing Large Language Models (LLMs) to understand key components, their failure modes, and behaviors. A suite of algorithms for detecting anomalies is offered in univariate and multivariate time series data, including regression-based, mixture-model-based, and semi-supervised approaches. We provide insights into the usage patterns of the service, with over 500 users and 200,000 API calls in a year. The service has been successfully applied in various industrial settings, including IoT-based AI applications. We have also evaluated our system on public anomaly benchmarks to show its effectiveness. By leveraging it, SREs can proactively identify potential issues before they escalate, reducing downtime and improving response times to incidents, ultimately enhancing the overall customer experience. We plan to extend the system to include time series foundation models, enabling zero-shot anomaly detection capabilities.

[Arxiv](https://arxiv.org/abs/2501.16744)