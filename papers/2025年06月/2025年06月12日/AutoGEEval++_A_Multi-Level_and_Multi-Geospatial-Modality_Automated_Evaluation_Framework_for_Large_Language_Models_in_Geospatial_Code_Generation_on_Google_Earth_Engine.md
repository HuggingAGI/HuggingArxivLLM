# AutoGEEval++: 一个用于Google Earth Engine上大型语言模型地理空间代码生成的多层级、多地理空间模态自动化评估框架

发布时间：2025年06月12日

`LLM应用

摘要中提到，论文讨论了大型语言模型在生成地理空间代码方面的应用，并提出了一个评估框架AutoGEEval++。该框架用于评估不同LLM在特定任务中的性能，属于LLM的应用层面。因此，这篇论文被归类为LLM应用。` `地理信息科学` `软件工程`

> AutoGEEval++: A Multi-Level and Multi-Geospatial-Modality Automated Evaluation Framework for Large Language Models in Geospatial Code Generation on Google Earth Engine

# 摘要

> 地理空间代码生成正在成为人工智能与地学分析融合的关键前沿领域，然而这一领域的标准化自动化评估工具仍然缺失。本研究提出了AutoGEEval++框架，它是基于AutoGEEval的增强版，也是首个针对大型语言模型（LLMs）在Google Earth Engine（GEE）平台上生成地理空间代码的自动化评估系统。它支持多种数据模态和不同任务复杂度。

基于GEE Python API构建，AutoGEEval++包含一个基准数据集——AutoGEEval++-Bench，该数据集涵盖了26种数据类型和三个任务类别（单元测试、组合测试和主题测试），总计6,365个测试用例。该框架还配备了提交程序和判题模块，实现了从代码生成到基于执行的验证的端到端自动化评估流水线。评估采用多维度指标，包括准确性、资源使用、运行时效率和错误类型，平衡了幻觉控制与效率，同时支持边界测试和错误模式分析。

通过AutoGEEval++，我们评估了截至2025年6月的24个最先进的LLMs，包括通用型、推理增强型、代码中心型和地学专用型模型。结果显示，不同任务类型、模型设计和部署设置下，模型在性能、稳定性和错误模式方面存在显著差异，证实了AutoGEEval++在垂直领域代码生成中的实际价值和可扩展性。本研究为基于GEE的LLM代码生成建立了首个标准化评估协议和基础基准，为性能比较提供了统一依据，并为系统化、领域特定的代码评估提供了一种方法论框架。

> Geospatial code generation is becoming a key frontier in integrating artificial intelligence with geo-scientific analysis, yet standardised automated evaluation tools for this task remain absent. This study presents AutoGEEval++, an enhanced framework building on AutoGEEval, and the first automated assessment system for large language models (LLMs) generating geospatial code on Google Earth Engine (GEE). It supports diverse data modalities and varying task complexities. Built on the GEE Python API, AutoGEEval++ features a benchmark dataset-AutoGEEval++-Bench-with 6,365 test cases across 26 data types and three task categories: unit, combo, and theme tests. It includes a submission programme and a judge module to realise an end-to-end automated evaluation pipeline from code generation to execution-based validation. The framework adopts multi-dimensional metrics-accuracy, resource usage, run-time efficiency, and error types-balancing hallucination control and efficiency, and enabling boundary testing and error pattern analysis. Using AutoGEEval++, we evaluate 24 state-of-the-art LLMs (as of June 2025), including general-purpose, reasoning-enhanced, code-centric, and geoscience-specific models. Results reveal clear performance, stability, and error differences across task types, model designs, and deployment settings, confirming AutoGEEval++'s practical value and scalability in vertical-domain code generation. This work establishes the first standardised evaluation protocol and foundational benchmark for GEE-based LLM code generation, providing a unified basis for performance comparison and a methodological framework for systematic, domain-specific code evaluation.

[Arxiv](https://arxiv.org/abs/2506.10365)