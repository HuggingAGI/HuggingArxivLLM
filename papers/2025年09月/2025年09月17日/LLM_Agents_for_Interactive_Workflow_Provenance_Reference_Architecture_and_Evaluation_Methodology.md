# 面向交互式工作流溯源的LLM智能体：参考架构与评估方法论

发布时间：2025年09月17日

`Agent` `基础理论`

> LLM Agents for Interactive Workflow Provenance: Reference Architecture and Evaluation Methodology

# 摘要

> 现代科学发现愈发依赖跨边缘、云及高性能计算（HPC）连续体的数据处理工作流。这些数据的综合深度分析对假设验证、异常检测、结果可重复性及突破性发现至关重要。尽管工作流溯源技术可支持这类分析，但大规模场景下的溯源数据往往复杂难析。现有系统依赖自定义脚本、结构化查询或静态仪表板，极大限制了数据交互能力。为此，本研究提出一种评估方法、参考架构及开源实现，通过交互式大型语言模型（LLM）智能体实现运行时数据分析。该方法采用轻量级元数据驱动设计，能将自然语言转化为结构化溯源查询。针对LLaMA、GPT、Gemini、Claude的评估（涵盖多类查询及真实化学工作流）结果显示，模块化设计、提示调优与检索增强生成（RAG）技术让LLM智能体不仅能准确响应，还能提供超越记录溯源的深度洞察。

> Modern scientific discovery increasingly relies on workflows that process data across the Edge, Cloud, and High Performance Computing (HPC) continuum. Comprehensive and in-depth analyses of these data are critical for hypothesis validation, anomaly detection, reproducibility, and impactful findings. Although workflow provenance techniques support such analyses, at large scale, the provenance data become complex and difficult to analyze. Existing systems depend on custom scripts, structured queries, or static dashboards, limiting data interaction. In this work, we introduce an evaluation methodology, reference architecture, and open-source implementation that leverages interactive Large Language Model (LLM) agents for runtime data analysis. Our approach uses a lightweight, metadata-driven design that translates natural language into structured provenance queries. Evaluations across LLaMA, GPT, Gemini, and Claude, covering diverse query classes and a real-world chemistry workflow, show that modular design, prompt tuning, and Retrieval-Augmented Generation (RAG) enable accurate and insightful LLM agent responses beyond recorded provenance.

[Arxiv](https://arxiv.org/abs/2509.13978)